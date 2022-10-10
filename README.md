# Cadastro de funcionarios - Trabalho avaliativo 2

Sistema para realizar cadastro de funcionários em Node.js no padrão MVC e ORM sequelize

1. Executar comando <br />
npm install express express-handlebars mysql2 sequelize nodemon

2. Criar usuario no mysql<br />
CREATE USER 'ruan'@'localhost' IDENTIFIED BY 'binderruan';
ALTER USER 'ruan'@'localhost' IDENTIFIED WITH mysql_native_password BY 'binderruan';
GRANT ALL PRIVILEGES ON * . * TO 'ruan'@'localhost';
flush privileges;

3. Criar database rh_funcionarios <br />
create database rh_funcionarios;
