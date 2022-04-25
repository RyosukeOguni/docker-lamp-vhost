FROM mysql/mysql-server:5.7

ENV MYSQL_DATABASE=skya \
  MYSQL_USER=root \
  MYSQL_PASSWORD=12345678 \
  MYSQL_ROOT_PASSWORD=12345678 \
  TZ=Asia/Tokyo

COPY ./my.cnf /etc/mysql/conf.d/my.cnf
RUN chmod 644 /etc/mysql/conf.d/my.cnf
