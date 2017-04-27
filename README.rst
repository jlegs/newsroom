sudo su - postgres
psql
create database newsroom;
create user newsroomuser with password 'password';
grant all privileges on database newsroom to newsroomuser;

