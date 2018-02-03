# Entity Management System

## Problem Statement
Create a simple entity management system that provides a REST endpoint to manage any entity (e.g. a product in a catalog, patient information in healthcare etc.).

The system should allow for the following capabilities:

1.	It should be able to adapt to any kind of entity with minimal code changes
2.	Adding, removing, modifying the attributes of an entity should be simple
3.	It should allow for nested attributes (sub-entities) e.g Patient  -> Consulting doctor
4.	Each attribute or sub-entity in the entity can have a set of business rules
5.	Each attribute in the entity can have UI rendering rules (you do not have to build the User interface but design your system/solution for it) e.g. some attributes are multi value, others are single value, some are select from a list kind of attributes other are free text

## Deliverables
REST endpoints to create, update, delete and display the entity. (NOTE: You do not need to create a user interface but build it to allow for a User interface to be hooked on). Use any kind of data store that you feel it appropriate (can be a database or simply a file)


## How to start ?

```
$ mvn spring-boot:run
```

## Swagger-UI
* After starting the application Click on [Swagger-home](http://localhost:8080/api/swagger-ui.html)


