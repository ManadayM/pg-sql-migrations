# PostgreSQL Schema Migrations

## Create a new migration file

```npm run migrate create table comments```

### Run migration script to push changes
```DATABASE_URL=postgres://postgres:password@localhost:5432/socialnetwork npm run migrate up```

### Run migration script to rollback changes
```DATABASE_URL=postgres://postgres:password@localhost:5432/socialnetwork npm run migrate down```
