FROM mysql:lts
VOLUME /var/lib/mysql
EXPOSE 3306
RUN touch /var/log/mysql.log
RUN chown mysql:mysql /var/log/mysql.log
COPY ./build/database/conf/myconf.cnf /etc/mysql/conf.d/.
