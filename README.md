# Even Health Full-Stack Coding Assignment

## Problem Description
Build a course registrar system.  Think of online learning platforms or registering for college courses.  The system is used by administrators, students, and professors to manage courses and get students enrolled.


*Remember*: We're evaluating your design and development skills based on the code you give us.  Make sure it reflects the type of code you would write on a production software system for us.  Take your time.  Remember to refactor and write unit tests.  If these instructions are unclear, rather than ask for clarification, list your assumptions and work from them.

## User Requirements

### Registrar / Administrator
Manage (create, update, and delete) courses.  A course consists of a code (ie CS-101), a description, a professor, and a capacity.

Manage students.  A student has a student id, first name, and last name.

### Student
View a list of courses, enroll in a course, un-enroll from a course, see enrolled courses.

### Professor
See a list of courses being taught, with a list of enrolled students for each course

## Technical Requirements

**This does not need to be a completely production-ready system!**
Implementing everything you can think of will take more time than we want you to spend on this assignment.  Focus on the most important things.  It is perfectly acceptable to document (either in a readme or with code comments) where you would add additional functionality.  Authentication, Authorization, Login, Backups, Persistence, Deployments, Animations, Complicated Styles, etc are all examples of things that would be nice to document but do not need to be implemented.

**Implement what you feel best showcases your skills, and point out where the pieces you didn't implement would go**

### General
Include instructions - don't make us fight with your code to get it to run

Document your assumptions - we're going to be reviewing your solution internally so if there's something you want us to know, write it down.

Tests - they don't need to be exhaustive, but they should give a good indication that you know how to write useful tests

### Backend
Spring Boot preferred.  Some reasonable REST endpoints and in-memory persistence is totally fine.  Don't forget the tests!  Separation of concerns and maintainability are especially important.

### Frontend
Vue.js preferred.  Build a web UI that meets the requirements of the three kinds of users.  Style matters, but only insofar as it affects function.  Usability is the most important thing.
