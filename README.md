# RaceDay – Part 1

## Project Overview

RaceDay is a web-based road event management system designed to support the management of running, walking and cycling events in South Africa.

The system allows organisers to create and manage events, categories and participant results. Participants can create accounts, browse available events, enter events and track their personal results.

## User Roles

### Organiser

An organiser can:

- Create events
- Edit events
- Delete events
- Manage event categories
- Capture participant results
- View event enrolments

### Participant

A participant can:

- Create an account
- Browse available events
- Enter an event by selecting a category
- View their enrolments
- Track their personal results

## Part 1 Deliverables

### Section A – Entity Relationship Diagram

The ERD represents the main entities and relationships required by the RaceDay system.

The database contains the following entities:

- Organiser
- Participant
- Event
- Category
- Enrolment
- Result

The ERD includes primary keys, foreign keys, attributes and relationship cardinalities.

### Section B – RESTful API Endpoint Plan

The API Endpoint Plan defines the RESTful API that will be implemented in Part 2.

The plan covers:

- Authentication
- User Profile
- Events
- Categories
- Enrolments
- Results

For each endpoint, the plan specifies the HTTP method, route, description, required role, request body and expected response.

### Section C – SQL Database

The SQL database script creates the RaceDay database and all required tables.

The script includes:

- Primary keys
- Foreign keys
- NOT NULL constraints
- UNIQUE constraints
- DEFAULT constraints
- CHECK constraints
- Sample data

The database script is designed for Microsoft SQL Server.

## Technologies

- C#
- ASP.NET
- RESTful API
- Microsoft SQL Server
- SQL Server Management Studio
- GitHub
- GitHub Actions

## Repository Structure

```text
RaceDay/
│
├── README.md
│
├── docs/
│   ├── RaceDay_ERD.drawio.png
│   ├── RaceDay API Endpoint Plan.docx
│   └── RaceDay_Database_Script.sql
│
└── Future Development
    ├── Part 2 – RESTful API
    └── Part 3 – MVC Web Application
