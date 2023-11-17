# MariaDB

### MySQL(MariaDB) 접속

  - mysql -u root -p

### 데이터베이스 확인

  - SHOW DATABASES;

### 데이터베이스 생성

  - CREATE DATABASE <database_name>;

### 아이디 생성

  - CREATE USER '<user_id>'@'%' IDENTIFIED BY '<user_password>';

### 사용자 권한 할당

  - GRANT ALL PRIVILEGES ON <database_name>.* TO '<user_id>'@'%';

### 새로 고침

  - FLUSH PRIVILEGES;
