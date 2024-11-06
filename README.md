# Data-For-Social-Group-Project-KJ-and-Pranav-
# Unit 3 - Data for Social Good Project

## Introduction 

Software engineers develop programs to work with data and provide information to a user. Each user has different needs based on the information they are looking for from data. The goal of this project is to create a data analysis program that stores and analyzes data to provide the information a user needs, specifically within a hospital context.

## Requirements 

This project applies object-oriented programming principles, one-dimensional (1D) arrays, and algorithms to create a data analysis program with the following features:
- **Write a class** – A Patient class was created to represent each patient and store data related to their health and department information. This class includes both a no-argument constructor and a parameterized constructor.
- **Create at least two 1D arrays** – The program includes two 1D arrays to store essential data: one array for patient names and another for department names.
- **Write a method** – Methods are implemented to find and manipulate data within the arrays, such as moving a patient to a new department and displaying all patient data.
- **Implement a toString() method** – A toString() method is provided in the Patient class to return detailed information about each patient's name, condition, department, and the last time they were moved.
- **Document your code** – Code comments are used throughout to explain the purpose of methods, as well as preconditions and postconditions.

## User Story 

> As a **hospital administrator or healthcare provider**, <br> 
> I want to **efficiently track and manage patient data, including current department and health conditions**, <br> 
> so that I can **ensure patients are placed in appropriate departments and their data is up-to-date for better healthcare management**.

## Dataset 

The project uses two primary data files to initialize patient and department data:

- **patient_names.txt**: This file contains a list of 50 patient names, each on a new line. The data type is `String`. These names are loaded into an array in the `PatientTracker` program.
- **departments.txt**: This file contains a list of hospital departments, including ER, ICU, General Ward, and Pediatrics. The data type is `String`. This data is used to assign each patient to a specific department initially.

Both files are read by the program to initialize data arrays, making it possible to manage patient assignments and movements.

Also, the pdf of both: patient & department names is attached along.

## UML Diagram 
![alt text](<Data for Social Good UML Diagram.jpg>)

## Description 

The **Patient Tracking System** is designed to help hospitals keep track of patient info by using a **1D array** to store details like patient names and departments. Patient data is loaded from **text files**, with each **element** in the array holding a different patient’s info. The program lets users **move** patients between departments and **view** all their details. This project covers important coding concepts like working with arrays and reading from files, making it easier for healthcare staff to manage patient data in one place.
