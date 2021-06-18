# Belajar Fundamental Aplikasi Back-End
Install Package yang dibutuhkan
npm install
npm install pg
npm install dotenv
npm install node-pg-migrate


Create table migration
* npm run migrate create "create table notes"
Run a migration 
* npm run migrate up

File .env
# server configuration
HOST=localhost
PORT=5000
NODE_ENV=development
# node-postgres configuration
PGUSER=postgres
PGHOST=localhost
PGPASSWORD=masterkey
PGDATABASE=notesapp
PGPORT=5432

File .prod.env
# server configuration
HOST=0.0.0.0
PORT=5000