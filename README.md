
This codebase was created to demonstrate a fully fledged fullstack application built with Spring Boot including CRUD operations, authentication, routing, pagination, and more.

# How it works

> The application uses Spring Boot 3 and Java 21 for all its architecture.

### What Can it Do?
Here's the functionalities of the API:

* __User Authentication via JWT:__ It lets users sign in securely using JSON Web Tokens (JWT).
* __Users:__ Provides operations to create, read, and update user profiles.
* __Articles:__ Enables users to create, read, and delete articles.
* __Comments:__ Enables users to create, read, and delete comments on articles.
* __Article Listings:__ Offers paginated lists of articles with ``offset`` and ``limit`` params.
* __Article Favoriting:__ Allows users to mark articles as favorites.
* __User Following:__ Enables users to follow and unfollow other users profiles.
* __Article Feed:__ Offers a feed endpoint to see articles from followed users.

### What's Under the Hood?

Here's the technologies used for the implementation:

 * __Spring Data JPA__ for efficient data management.
 * __Spring Security__ with __JWT tokens__ for authentication.
 * __JUnit5__ and __Mockito__ for testing.
 * __MySql__ for the database.
 * __Flyway__ for the database migrations.
 * __[modelmapper](https://modelmapper.org/)__ for the DTOs.
 * __[spring-arg-resolver](https://github.com/tkaczmarzyk/specification-arg-resolver)__, for dynamic param filtering.


