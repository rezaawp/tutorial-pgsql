# tutorial-pgsql

## Login super user tanpa diminta password
`sudo -u postgres psql`

## Perintah CLI
- `\l` melihat list database
- `\c database_name` konek database
- `\dt` melihat daftar tables pada database
- `\d table_name` melihat struktur table
- `\q` keluar dari perintah CLI
- pg_dump -U user -h localhost -p 5432 db_name > output.sql
