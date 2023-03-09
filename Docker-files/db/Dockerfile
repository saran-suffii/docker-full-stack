FROM mysql:5.7.25

LABEL "Project"="Vprofile"
LABEL "Author"="saran"


ENV MYSQL_ROOT_PASSWORD="VPRODBPASS"
ENV MYSQL_BATABASE="accounts"

ADD db_backup.sql docker-entrypoint-init.d/db_backup.sql
