# Modelagem.comp

#Modelagem Conceitual

![image](https://github.com/IlbertoDomingos/Modelagem.comp/assets/107081757/8e3a4ffa-83c5-45b3-b67e-90e90b1c3479)

#Modelagem Logica

![image](https://github.com/IlbertoDomingos/Modelagem.comp/assets/107081757/15aaaf71-61fb-474e-87b0-ab8a97e44791)

#Modelagem Fisica

```SQL
--criação banco de dados
create database ilberto.Teste

-- criação de tabela
CREATE TABLE Alunos 
( 
 Codigoaluno INT PRIMARY KEY,  
 nomealuno VARCHAR(80),  
 email VARCHAR(50), 
curso VARCHAR (50),
 whatsapp VARCHAR(11),  
 codigoSede INT
); 

CREATE TABLE Sede 
( 
 codigosede INT PRIMARY KEY,  
 nomesede VARCHAR(100),  
 endereço VARCHAR(100)
); 

-- consultar tabelas
select * from alunos;

select * from sede;

drop table alunos

-- inserindo dados 
-- sede
insert into sede (codigosede, nomesede, endereço) values (1, 'DC Sul', 'Av. WS...');
insert into sede (codigosede, nomesede, endereço) values (2, 'DC Aldeota', 'Av. SD...')
-- alunos
insert into alunos (codigoaluno, nomealuno, email, curso, whatsapp, codigosede ) values (1, 'aaaa', 'a@fjfj', 'DA Analytics', '3333333', 1);
insert into alunos (codigoaluno, nomealuno, email, curso, whatsapp, codigosede ) values (2, 'bbbb', 'a@fjfj', 'DA Analytics', '3333333', 2),
insert into alunos (codigoaluno, nomealuno, email, curso, whatsapp, codigosede ) values (3, 'Aluno 4', 'a@fjfj', 'DA Analytics', 3333333,	1),
insert into alunos (codigoaluno, nomealuno, email, curso, whatsapp, codigosede ) values (5, 'Aluno 5', 'a@fjfj', 'DA Analytics', 3333333,	2),
insert into alunos (codigoaluno, nomealuno, email, curso, whatsapp, codigosede ) values (4, 'Aluno 6', 'a@fjfj', 'Marketing', 3333333,	2);

```

