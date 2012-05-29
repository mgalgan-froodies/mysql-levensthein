# Levensthein for MySQL

This is an implementation of Levensthein distance calculation in MySQL.

#### Installation

```
$ mysql database-name < levensthein.sql
```

#### Usage

```sql
SELECT levenshtein("Levensthein", "Levenstein");

Result: 1
```

```sql
SELECT levenshtein_ratio("Levensthein", "Levenstein");

Result: 91
```