FROM mysql:latest

RUN echo "CREATE DATABASE IF NOT EXISTS fullcycle; USE fullcycle; CREATE TABLE IF NOT EXISTS people (id INT AUTO_INCREMENT PRIMARY KEY, name VARCHAR(255) NOT NULL); INSERT INTO people (name) VALUES ('Ruan da Silva Costa'); INSERT INTO people (name) VALUES ('Suelen Santos Costa');" > /docker-entrypoint-initdb.d/init.sql
