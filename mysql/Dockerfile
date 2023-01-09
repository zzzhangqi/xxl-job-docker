FROM mysql:5.7

ADD xxl-job.sql /docker-entrypoint-initdb.d/xxl-job.sql

ENV MYSQL_DATABASE=xxl_job \
    MYSQL_ROOT_PASSWORD=root_pwd
    
VOLUME [ "/var/lib/mysql" ]
