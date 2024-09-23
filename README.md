# ZOO Management Database System

## Overview

This project showcases my SQL expertise through the design of a robust database system for managing Zoo operations. Conceptualized and created entirely by me, this database efficiently handles animal registration, diet plans, and feeding schedules. It empowers Zoo employees to track essential data, ensuring the well-being of the animals.

The primary goal of this project is to establish a structured relational database that enables employees to maintain accurate records of animals, their specific dietary needs, and any adjustments made to their diets. This solution provides a centralized system for easy access to animal care data while ensuring accurate and efficient information retrieval.

## Project Scope

- **Customer**: Local Zoo  
- **Users**: Zoo employees responsible for animal registration, dietary planning, and feeding records.  
- **Purpose**: To maintain and control animal diets, including modifications based on health and ingredient availability.

## Achievements and Highlights

### Database Design

The database structure is crafted from scratch, addressing real-world requirements of a Zoo management system. Key components include:

- **Entity-Relationship Diagram (ERD)**: Visualizes the structure and relationships between key entities such as animals, diets, cages, and employees.
- **Entity Table Creation**: Each entity, including Animals, Diets, Cages, and Employees, is defined with relevant attributes.
- **Relationship Mapping**: Establishes connections between animals, their diets, and the responsible employees.
- **Normalization**: Ensures efficient data storage by avoiding redundancy through relational schema principles.

### Complex Scenarios

The database supports various real-life scenarios, including:

- Animal registration, location checks, and cage management.
- Dynamic diet planning based on animal health, pregnancy, or ingredient availability.
- Automated registration of substitutes when certain ingredients are unavailable.

### Database Queries

I designed and tested several advanced SQL queries to fulfill typical requests from Zoo staff, such as:

- Tracking the number of animals registered in the past month.
- Viewing changes in an animal’s diet.
- Calculating the amount of food (e.g., vegetables) required for the next month.
- Checking how many animals live in a specific zone or cage.
- Identifying substitute ingredients for specific meals.

### Optimization and Assumptions

The database is built with key operational assumptions and limitations, focusing on animal registration and feeding control while excluding non-essential elements like animal health records, employee salaries, and ticket sales.

## Scenarios Supported

- **New Animal Registration**: Employees can register new animals, assign them to available cages, and update their diets.
- **Diet Modifications**: Employees can create or adjust diets for animals based on health and ingredient availability.
- **Pregnancy and Special Diets**: Special dietary needs for pregnant animals are managed.
- **Animal Lifecycle Management**: Track events such as birth, death, and relocation of animals.

## Key Features

- **Dietary Tracking**: Employees can log all dietary changes, ensuring each animal receives proper nutrition at the right time.
- **Substitute Ingredients**: The system allows for substitutions when necessary and tracks these adjustments.
- **Cage Management**: Prevents overcrowding and ensures proper animal placement in available cages.
- **Popular Diet Tracking**: Employees can monitor which diets are most frequently used across the Zoo.
