# Sales Database Setup

This repository contains SQL scripts for setting up a sales database system.

## Files

- `answers.sql` - Main SQL script containing database operations

## SQL Script Contents

The `answers.sql` file performs the following operations:

1. **Creates a new database** called `salesDB`
2. **Deletes an existing database** called `demo`

## Usage

1. Execute the SQL script in your database management system (MySQL, PostgreSQL, SQL Server, etc.)
2. The script will:
   - Create a new sales database for your application
   - Remove the demo database (if it exists)

## Important Notes

- Be cautious when running DROP DATABASE commands as they permanently delete databases
- Make sure you have appropriate permissions before executing these commands
- Consider backing up important data before running destructive operations

## Database Compatibility

This script uses standard SQL syntax that should work with most relational database systems, though you may need to adjust for specific database dialects.
