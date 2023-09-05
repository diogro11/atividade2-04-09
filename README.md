# atividade2-04-09
 CREATE TABLE co_identificador (
nome varchar(200),
cpf varchar(200),
cargo varchar(200),
salario int
);



INSERT INTO cod_identificador (nome,cpf,cargo,salario) VALUES ('pedro','23223273746','conferente','1780,00');
 INSERT INTO cod_identificador (nome,cpf,cargo,salario) VALUES ('diogo','452262737','analista de dados','4000,50');
 INSERT INTO cod_identificador (nome,cpf,cargo,salario) VALUES ('augusto','176252439','gestor rh','5497,87');
 INSERT INTO cod_identificador (nome,cpf,cargo,salario) VALUES ('mateus','448374739','motorista','2800,75');
  INSERT INTO cod_identificador (nome,cpf,cargo,salario) VALUES ('mariana','463748438','aux administrativo','2500,98');
 
 SELECT nome,cpf,cargo,salario FROM cod_identificador;
