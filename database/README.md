# Database migrations

## Tools

- [Golang migrate](https://github.com/golang-migrate/migrate)

## Scripts

```bash
# add new migration
sh schema.sh add <migration name>
# run migrations
sh up.sh
# rollback migrations
sh down.sh
```
