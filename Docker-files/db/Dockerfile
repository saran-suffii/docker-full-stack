FROM mysql:5.7.25

LABEL "Project"="Vprofile"
LABEL "Author"="saran"


ENV MYSQL_ROOT_PASSWORD="vprodbpass"
ENV MYSQL_BATABASE="accounts"

ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql
