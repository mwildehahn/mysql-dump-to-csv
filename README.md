# mysql-dump-to-csv
Quickly put together script to parse a mysql dump and generate CSVs for all of the tables in the dump.

Example:

`python mysql_dump_to_csv.py dump.sql output`

Should output a CSV file for each table that has data within the dump file.
