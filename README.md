## Library project 2

___

# Overview:

This is an upgrade of the ["library project"](https://github.com/Arkeea/library-project) with some new features and using a new stack.

Spring Data JPA is used instead of the JDBC template. Additionally, the following new functionalities have been added:

1. Pagination has been implemented
2. Sorting of books by the year of publication has been added
3. A book search page has been introduced
4. Overdue return checks for books have been implemented.

___
# How to run:

To run the application, Tomcat 9 is used. In IntelliJ IDEA, you need to go to "Run" -> "Edit Configurations" and add a "Tomcat Local Server" with the URL http://localhost:8080/. In the "Deploy" tab, add an artifact.

You also need to add your database configuration in the file "hibernate.properties.origin" and rename the file by removing the ".origin" extension.

___
# Technology stack:

Java 11, Maven, Tomcat, PostgreSQL, Spring Core, Spring MVC, Hibernate, Spring Data JPA, Thymeleaf, HTML.

___

# Pages:
__People page:__

![People page](https://github.com/Arkeea/library-project2/blob/main/img/people.gif)

__Books page:__

![Books page](https://github.com/Arkeea/library-project2/blob/main/img/books.gif)

__Search:__

![Search page](https://github.com/Arkeea/library-project2/blob/main/img/search.gif)

__Pagination:__

![Pagination](https://github.com/Arkeea/library-project2/blob/main/img/pagination.png)

__Book is expired:__

![Expired](https://github.com/Arkeea/library-project2/blob/main/img/expired.png)


