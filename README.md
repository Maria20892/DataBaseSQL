## ZOO Management Database System
Overview 

This project showcases my SQL expertise by designing a robust database system to manage a Zoo's operations. The database, entirely conceptualized and created by me, is built to efficiently handle animal registration, diet plans, and feeding schedules. It helps Zoo employees track essential data and ensure the well-being of the animals.

The goal of this project is to create a structured relational database that allows employees to maintain precise records of animals, their specific dietary needs, and any adjustments made to their diets. This solution provides a centralized system for easy access to animal care data while ensuring accurate and efficient information retrieval.

Project Scope
Customer: Local ZOO
Users: Zoo Employees responsible for animal registration, dietary planning, and feeding records.
Purpose: To maintain and control animal diets, including diet modifications based on various factors such as health and availability of ingredients.
Achievements and Highlights
Database Design:
The entire database structure is designed from scratch based on the real-world requirements of a Zoo management system. This includes:

Entity-Relationship Diagram (ERD) to visualize the structure and relationships between key entities such as animals, diets, cages, and employees.
Entity Table Creation: Each entity, such as Animals, Diets, Cages, and Employees, has been defined with relevant attributes.
Relationship Mapping: Designed relationships between animals, their diets, and the employees responsible for managing them.
Normalization: The database is structured to avoid redundancy and ensure efficient data storage using relational schema principles.
Complex Scenarios:
The database supports various real-life scenarios, including:

Animal registration, location checks, and cage management.
Dynamic diet planning based on animal health, pregnancy, or ingredient availability.
Automated registration of substitutes when certain ingredients are unavailable.
Database Queries:
I designed and tested several advanced SQL queries to fulfill typical requests from Zoo staff, such as:

Tracking the number of animals registered in the past month.
Viewing changes in an animal’s diet.
Calculating the amount of food (e.g., vegetables) required for the next month.
Checking how many animals live in a specific zone or cage.
Identifying substitute ingredients for specific meals.
Optimization and Assumptions:
The database is built with key operational assumptions and limitations in mind, focusing on animal registration and feeding control while excluding non-essential elements like animal health records, employee salaries, and ticket sales.

Scenarios Supported
New Animal Registration: Employees can register new animals, assign them to available cages, and update their diets.
Diet Modifications: Employees can create or adjust diets for animals based on their health or availability of ingredients.
Pregnancy and Special Diets: Special dietary needs for pregnant animals are managed.
Animal Lifecycle Management: Track events such as birth, death, and relocation of animals.
Key Features
Dietary Tracking: Employees can log all dietary changes, ensuring each animal gets the proper food at the right time.
Substitute Ingredients: When necessary, the system allows substitutions for ingredients and tracks these adjustments.
Cage Management: The system prevents overcrowding and ensures proper animal placement in available cages.
Popular Diet Tracking: Employees can track which diets are used most frequently across the Zoo.

