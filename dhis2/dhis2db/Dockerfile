FROM postgres:10

ENV POSTGRES_USER dhis
ENV POSTGRES_PASSWORD dhis
ENV POSTGRES_DB dhis

RUN apt-get update \
    && apt-get install -y postgresql-10-postgis-2.4 \
    && rm -rf /var/lib/apt/lists/*
