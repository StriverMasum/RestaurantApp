# Restaurant Management Application

## 1) Frameworks and Language Used

This restaurant management application is developed using the following frameworks and languages:

- **Framework**: Spring Boot
- **Language**: Java

## 2) Data Flow (Functions Used in ...)

### Controller Layer
- **getRestaurants()**: This function retrieves a list of all restaurants.
- **getRestaurant(Integer id)**: Retrieves a specific restaurant by its ID.
- **addRestaurant(Restaurant r)**: Adds a new restaurant to the list of restaurants.
- **addRestaurants(List<Restaurant> r)**: Adds a list of restaurants to the existing list.
- **updateSpecialty(Integer id, String updatedSpecial)**: Updates the specialty of a restaurant with the given ID.
- **deleteRestaurant(Integer id)**: Deletes a restaurant with the given ID.

### Service Layer
- **getAllRestaurants()**: Retrieves a list of all restaurants.
- **getRestaurant(Integer id)**: Retrieves a specific restaurant by its ID.
- **addRestaurant(Restaurant r)**: Adds a new restaurant to the list of restaurants.
- **addRestaurants(List<Restaurant> r)**: Adds a list of restaurants to the existing list.
- **updateSpecialty(Integer id, String updatedSpecial)**: Updates the specialty of a restaurant with the given ID.
- **deleteRestaurant(Integer id)**: Deletes a restaurant with the given ID.

### Repository Layer
- **getRestaurants()**: Retrieves a list of all restaurants.
- **addRestaurant(Restaurant r)**: Adds a new restaurant to the list of restaurants.

## 3) Data Structures Used in Project

- **List**: Lists are used to store and manage the collection of restaurants.
- **Restaurant**: A custom data structure or class representing a restaurant with attributes such as ID, name, specialty, etc. (You can provide more details about the structure of the `Restaurant` class here.)

## 4) Project Summary

The Restaurant Management Application is built using the Spring Boot framework and Java programming language. It allows users to perform various operations related to restaurants, including retrieving restaurant information, adding new restaurants, updating specialties, and deleting restaurants. The application utilizes a layered architecture with a Controller layer to handle incoming HTTP requests, a Service layer to implement business logic, and a Repository layer to manage restaurant data.

Data is primarily stored in lists, and the application provides RESTful endpoints for interacting with restaurant data. Users can retrieve a list of all restaurants, get details of a specific restaurant by its ID, add new restaurants, add multiple restaurants in bulk, update the specialty of a restaurant, and delete restaurants by their IDs.

