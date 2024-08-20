FROM mysql:8.0.33
LABEL "Project"="Vprofile"
LABEL "Author"="Mangong"

ENV MYSQL_ROOT_PASSWORD="vprodbpass"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql Docker-entrypoint-initdb.d/db_backup.sql
