# TodoApp
This is a basic Todoapp with Spring Security where user can register, login and do CRUD operations on his/her todo list.
# Instructors

-Clone the project


-Create a schema in MySQL Workbench


-Head into application.properties and modify username and password for your database and replace "db" in jdbc:mysql://localhost:3306/"db" with your schema name.

  spring.datasource.url=jdbc:mysql://localhost:3306/db
  
  spring.datasource.username=YOUR USERNAME HERE
  
  spring.datasource.password=YOUR PASSWORD HERE
  

-Run the test UserRepositoryTests and it will create the database table for you.


-Head into application.properties file again and modify "create" in spring.jpa.hibernate.ddl-auto="create" with "none".


-You are good to go!
