# UniversityEventManagementApplication
Making a University Event Management system with java-Spring-Boot and H2 database

## Framework and Language used
* Springboot
* Java
* H2 Database
* Spring JPA

## Project Summary
* This is a SpringBoot-based project for managing Student and Events, with endpoints for adding, retrieving, updating, and deleting information.

## Student Model
* studentId
* firstName
* lastName
* age
* department

## Event Model
* eventId
* eventName
* locationOfEvent
* date
* startTime
* endTime

## controller
* StudentController
* EventController

## Service
* StudentService
* EventService

## Model
* Student
* Event

## Repository
* StudentRepository
* EventRepository
* Used CrudRepository and Custom Query method

## Data Structure used
* ArrayList

## Validation
* First character of first name should be capital.
* All characters of last name must be alphabets
* Age must be between 18 to 25.

