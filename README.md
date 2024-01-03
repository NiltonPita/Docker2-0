# Docker2-0
Repostório criado para liberação de scripts dos desafios

Criação de Containers e variáveis de ambiente:

Criar container para MySql:
  docker container run -d -p 3306:3306 -e MYSQL_ROOT_PASSWORD="root1234" -e  MYSQL_DATABASE=auladocker -e   MYSQL_USER=userdocker -e MYSQL_PASSWORD=auladockerpwd mysql 

Listar os containers
			docker container ls -a	

Testar
  utilizar o cliente DBeaver Community
  Nova conexão
  Selecionar MySql
  definir root e senha
  SSH - aloowPublicKeyRetrail = true
  
Eliminar o container de banco
				docker container rm -f a98f072c6072 
    

Criar container para Postgrees:
  docker container run -d -p 3306:3306 -e MYSQL_ROOT_PASSWORD="root1234" -e  MYSQL_DATABASE=auladocker -e   MYSQL_USER=userdocker -e MYSQL_PASSWORD=auladockerpwd mysql 

Listar os containers
			docker container ls -a	

Testar
  utilizar o cliente DBeaver Community
  Nova conexão
  selecionar Postgrees
  definir usuário e senha

Eliminar o container de banco
				docker container rm -f 9c8631289848  

