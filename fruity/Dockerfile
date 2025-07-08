FROM docker.io/library/clickhouse:25.4
LABEL version="0.3.1"

COPY readonly.xml /etc/clickhouse-server/users.d/

COPY fruity/datasets/ /docker-entrypoint-initdb.d/
