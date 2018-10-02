FROM postgres:9.5
ENV POSTGRES_DB postgres
COPY ./init-db.sql /docker-entrypoint-initdb.d/
RUN echo "host all all all trust" >> /var/lib/postgresql/data/pg_hba.conf
