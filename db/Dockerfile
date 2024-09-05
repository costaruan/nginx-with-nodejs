FROM mysql:latest

RUN echo "CREATE DATABASE IF NOT EXISTS fullcycle;" > /docker-entrypoint-initdb.d/init.sql \
    && echo "USE fullcycle;" >> /docker-entrypoint-initdb.d/init.sql \
    && echo "CREATE TABLE IF NOT EXISTS people (id INT AUTO_INCREMENT PRIMARY KEY, name VARCHAR(255) NOT NULL);" >> /docker-entrypoint-initdb.d/init.sql \
    && echo "INSERT INTO people (name) VALUES ('Ruan');" >> /docker-entrypoint-initdb.d/init.sql