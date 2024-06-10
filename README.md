# JPA-HIBERNATE-POSTGRESQL-basicImplement
Uma implementação básica e simples de integração de banco de dados utilizando Eclipse e PostgreSQL.

POSTGRESQL DATABASE:
-- Database: aulajpa

-- DROP DATABASE IF EXISTS aulajpa;

CREATE DATABASE aulajpa
    WITH
    OWNER = postgres
    ENCODING = 'UTF8'
    LC_COLLATE = 'Portuguese_Brazil.1252'
    LC_CTYPE = 'Portuguese_Brazil.1252'
    LOCALE_PROVIDER = 'libc'
    TABLESPACE = pg_default
    CONNECTION LIMIT = -1
    IS_TEMPLATE = False;
