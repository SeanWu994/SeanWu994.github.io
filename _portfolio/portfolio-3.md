---
title: "Hybrid Database Design for a Fitness Application"
excerpt: "Designed a hybrid MongoDB and BigQuery database architecture to support fitness tracking and business analytics."
collection: portfolio
permalink: /portfolio/fitness-database-design/
---

# Hybrid Database Design for a Fitness Application

**Project Type:** Academic Project | Purdue University  
**Tools:** MongoDB, Google BigQuery, Database Design, ERD

## Project Overview

In this project, I designed a hybrid database architecture for a fictional fitness application called FitTrack.

The application needed to support daily user activities, such as workout logging and trainer-client management, while also making data available for business analytics.

The goal was to identify which database technology would be most appropriate for different business needs.

## Business Problem

A fitness application handles different types of data and operations.

Users need to record workouts, update exercise details, and manage their training activities. These operations require flexible data structures and efficient updates.

At the same time, the business needs structured data for reporting and analyzing user activity.

Using only one database system may not be the best solution for both needs.

## What I Did

### 1. Identified Database Requirements

I analyzed the application's features and separated operational needs from analytical needs.

I focused on two areas:

- Workout logging
- Trainer-client management

### 2. Designed MongoDB Collections

I designed document structures to support operational activities.

For example, workout sessions could contain nested exercise and set information, allowing related data to be stored together.

I also designed a trainer-client collection to manage relationships between trainers and their clients.

### 3. Designed BigQuery Tables

I created relational data models for analytical reporting.

For workout logging, the design included:

- Users
- Workout sessions
- Exercises
- Workout sets

For trainer-client management, the design included:

- Trainers
- Clients
- Trainer-client relationships
- Training programs

### 4. Created Entity Relationship Diagrams

I created ERDs to explain the relationships between different tables.

The diagrams helped visualize primary keys, foreign keys, and one-to-many or many-to-many relationships.

## Results

- Designed a hybrid architecture combining MongoDB and BigQuery
- Created document models for workout logging and trainer-client management
- Designed relational schemas for analytical reporting
- Developed two ERDs to explain the database relationships
- Identified trade-offs between flexible operational storage and structured analytical reporting

## What I Learned

This project helped me understand that database design should depend on business requirements.

MongoDB can support flexible document structures and operational workflows, while BigQuery is useful for large-scale analytical queries.

I also learned that using multiple databases introduces challenges, including data consistency and synchronization between systems.

The project strengthened my understanding of database modeling and how technical architecture supports business operations.

## Project Scope

This was a database design project, not a fully deployed production application. The results represent the proposed architecture and completed design deliverables.
