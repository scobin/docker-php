FROM mysql:8.0

ENV TZ=Asia/Tokyo \
  MYSQL_DATABASE=develop \
  MYSQL_USER=my-user \
  MYSQL_PASSWORD=my-password \
  MYSQL_ROOT_PASSWORD=secret

COPY ./my.cnf /etc/my.cnf
