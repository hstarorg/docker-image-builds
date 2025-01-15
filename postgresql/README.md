# Postgresql with pig

- https://pigsty.io/zh/blog/pg/pig/ Pig Intro
- https://hub.docker.com/_/postgres Base image

## Image tag

## Usage

1. Must set env: `POSTGRES_PASSWORD`
2. Recommend set volumes
   - /var/lib/postgresql/data
3. Recommend set port binding

## Advance

1. Install postgresql extenstion
   - `pig ext install vector` - https://github.com/pgvector/pgvector
   - `pig ext install pg_cron` - https://github.com/citusdata/pg_cron, Need require
