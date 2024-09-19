# PostgreSQL GitHub Action

This [GitHub Action](https://github.com/features/actions) sets up a PostgreSQL database.

# Usage

See [action.yml](action.yml)

Basic:
```yaml
steps:
- uses: lolfoollor/postgresql-action@v1.1
  with:
    postgresql version: "16.4"
    postgresql db: {NAME_OF_DB}
    postgresql user: {NAME_OF_USER}
    postgresql password: ${{ secrets.{SECRET_PASSWORD_IN_GITHUB} }}
    postgresql port: 5432 
```

# License

The scripts and documentation in this project are released under the [MIT License](LICENSE)
