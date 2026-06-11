# Course-Enrollment-system
Course Enrollment System implemented in C++ using OOP and STL. Supports course registration, prerequisite validation, slot conflict detection, enrollment limits, waitlist management, and automatic seat allocation.
# Course Enrollment System

## Overview

Course Enrollment System is a console-based C++ application that simulates the academic course registration process followed in universities. The system manages students, courses, prerequisites, enrollment limits, timetable slot conflicts, and waitlists using Object-Oriented Programming principles and STL containers.

This project was implemented as a solution to a problem statement inspired by a senior batch's Object-Oriented Programming (OOP) laboratory assignment at IIT Madras.

---

## Problem Statement

Design and implement a Course Enrollment Management System that supports:

* Student registration with completed course records.
* Course creation with prerequisites, capacity constraints, and timetable slots.
* Course enrollment subject to prerequisite completion.
* Prevention of timetable slot clashes.
* Prevention of duplicate enrollments.
* Waitlist management when a course reaches maximum capacity.
* Automatic enrollment of waitlisted students when seats become available.
* Viewing enrolled students for a course.

The system should be implemented using Object-Oriented Programming concepts and appropriate STL data structures.

---

## Features

### Student Management

* Add new students
* Maintain completed course history
* Track enrolled courses
* Track occupied timetable slots

### Course Management

* Add new courses
* Define prerequisites
* Set course capacity
* Assign timetable slots

### Enrollment System

* Prerequisite validation
* Slot conflict detection
* Capacity checking
* Duplicate enrollment prevention
* Automatic waitlist handling

### Course Withdrawal

* Drop enrolled courses
* Automatically fill vacant seats from the waitlist

---

## Technologies Used

* C++
* Object-Oriented Programming (OOP)
* STL Containers

  * Map
  * Set
  * Queue
* Dynamic Enrollment Logic

---

## Data Structures

| Structure       | Purpose                                            |
| --------------- | -------------------------------------------------- |
| map             | Student and course lookup                          |
| set             | Prerequisites, completed courses, enrolled courses |
| queue           | Waitlist management                                |
| map<int,string> | Enrollment ordering                                |

---

## Supported Operations

* Add Student
* Add Course
* Enroll Student
* Drop Course
* Print Enrolled Students

---

## Learning Outcomes

This project demonstrates:

* Class Design and Encapsulation
* Friend Classes
* STL Container Usage
* Constraint-Based Validation
* Queue-Based Waitlist Management
* Academic Registration System Modeling

---

## Note

This implementation is based on a problem statement provided by senior students as part of the Object-Oriented Programming laboratory practice at IIT Madras. The code represents an independent implementation of the required functionality.

## Author

Developed as part of OOP practice and coursework preparation.
