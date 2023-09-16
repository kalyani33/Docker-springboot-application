# Docker-springboot-application
dockering springboot MYSQL CRUD application

<img width="600" alt="image" src="https://github.com/kalyani33/Docker-springboot-application/assets/37569003/1691cd44-4c8d-4c24-bec6-d58572e658f4">


1.docker pull mysql<br/>
2.docker network create springboot-mysql-net  
3.docker network ls  
4.docker run --name sprinbootdb --network springboot-mysql-net -e MYSQL_ROOT_PASSWORD=root -e MYSQL_DATABASE=employeedb -d mysql  
5.docker ps  
6.docker exec -it 4c60 bash  
7.mysql -u root -p  
