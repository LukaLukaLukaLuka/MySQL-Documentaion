# Sql
- Semicolon language
- Capatalization Dosen't Matter
- Binary Bools (1 = True, 0 = False)
---
## 1. [Databases](#lection-1-databases)
## 2. [Tables](#lection-2-tables)
     1. [Columns](#1-columns)\
     2. [Rows](#2-rows)

---
## Lection 1: Databases
- `CREATE [DATABASENAME]` - Creates a database
- `USE [DATABASENAME]` - Uses [DATABASENAME] for the entire file
- `ALTER Database [DATABASENAME] Read Only = 1` - Makes the database read only
- `DROP [DATABASENAME]` - Removes a Database
---
## Lection 2: Tables
### 1. Columns
- **Info types**:
    - **INT** - Integer
    - **VARCHAR** - String
    - **DATE** - Date
    - **DECIMAL** - Float
- `ALTER Database [TABLENAME] CREATE` - Creates a database, to see syntax of creating databases see [Code Gallery Picture 1.](Code%20Gallery.md#1-)
- `SELECT * From [TABLENAME]` - Acces everything from a table
- `RENAME Table [TABLENAME] To [TABLENAME]` - Rename a Table
- `ALTER Table [TABLENAME]` - Begin Altering a Table
-  `ADD [DATANAME] [INFOTYPE]` - Add something to a table
- `RENAME Column [COLUMN] to [NEWCOLUMNNAME]` - Renames a Column
- `MODIFY Column [COLUMN] [NEWINFOTYPE]` - Modifys a column
- **The Following Commands are to be used after:  `MODIFY Column [COLUMN] [NEWINFOTYPE]`**
- `AFTER [COLUMN]` - Puts a column after another column
- `FIRST` - Puts a column first
- `DROP Column [COLUMN]` - Delete a column
### 2. Rows
- The Following Commands are to be used after: `INSERT Into [DATABASENAME]`
- `VALUES ([DATA], [DATA], [DATA]) ([DATA], [DATA], [DATA]) ([DATA], [DATA], [DATA]) ([DATA], [DATA], [DATA])` - Add rows to your sql table, to see the full syntax of `VALUES` look at the [Code Gallery Picture 2.](Code%20Gallery.md#2-)
