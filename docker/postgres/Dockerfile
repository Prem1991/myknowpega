FROM pegasystems/postgres-pljava-openjdk:11

## Create a new directry for persisting postgres data volume

RUN mkdir -p /var/lib/postgresql-persist/data

ENV PGDATA var/lib/postgresql-persist/data