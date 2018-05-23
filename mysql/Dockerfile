FROM mysql:5.7

MAINTAINER "xx19941215@gmail.com"

ADD startup /etc/mysql/startup

RUN chown -R mysql:root /var/lib/mysql/

ADD my.cnf /etc/mysql/conf.d/my.cnf

CMD ["mysqld"]

EXPOSE 3306