# Scripts Directory

This directory contains utility scripts for the Aracely-IA project.

## seed.ts

This script is used to seed the database with initial data.

### Prerequisites

- Node.js installed
- Project dependencies installed (`pnpm install`)
- TypeScript installed globally or locally (`pnpm add -g typescript`)

### Usage

To execute the seed script, run the following command from the project root directory:

```bash
npx tsx scripts/seed.ts
```

Or using ts-node:

```bash
npx ts-node scripts/seed.ts
```

### Notes

- Make sure your database is running and properly configured before running the seed script.
- The script will populate the database with initial data as defined in the seed file.
- For development purposes, you might need to adjust the database connection settings in your environment variables.
