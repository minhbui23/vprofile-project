FROM mysql:8.0.33
LABEL "Project"="vprofile"
LABEL "Author"="MinhBui"

ENV MYSQL_ROOT_PASSWORD="vprodbpass"
ENV MYSQL_DATABASE="accounts"

#Copy data from db_backup.sql to initialize a fresh instance 
ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql 