# Google CloudBuild config for Hasura metadata and migrations

Uses https://github.com/sharescape/hasura-cli-docker

## Substitutions
- `_HASURA_GRAPHQL_SERVER_HOST`: Required if a config.yaml is not mounted. The
    Hasura endpoint to pass to the Hasura CLI
- `_HASURA_GRAPHQL_ADMIN_SECRET`: Optional
- `_HASURA_GRAPHQL_ENV_FILE`: .env filename to load ENV vars from (default ".env")
