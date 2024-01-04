FROM mysql
ENV TZ Asia/Seoul
ENV MYSQL_ROOT_PASSWORD=12345
ENV MYSQL_DATABASE=PetShoppingMall
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone
ADD db_user.sql /docker-entrypoint-initdb.d/01_db_user.sql
ADD insertData.sql /docker-entrypoint-initdb.d/02_insertData.sql
WORKDIR /
EXPOSE 3306