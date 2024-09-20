# Hospital-Management-Database
This project is a hospital management database for tracking hospitals, job positions, candidates, and their skills. It manages interviews, recording dates and required skills for positions. The schema features interconnected tables with foreign key constraints to maintain data consistency and reliability.

Hospital Management Database
Project Overview

This project implements a hospital management database that handles information regarding hospitals, job positions, candidates, and interviews. The database structure uses a series of interconnected tables with foreign key constraints to maintain data integrity, making it a reliable resource for managing complex relationships between entities such as hospitals, job openings, and candidate applications.

Database Structure
The database includes the following key tables:

Hospitals: Contains information about different hospitals.

Candidates: Details of candidates including their contact information and skills.

Positions: Tracks available positions, linking them to respective hospitals.

Interviews: Logs interviews conducted, connecting positions, candidates, hospitals, and interview details.

InterviewDates: Stores dates for interviews linked to specific interview records.

Skills: Lists available skills in the system.

CandidateSkills: Links candidates to the skills they possess.

PositionSkills: Links positions to the skills they require.

Key Features

Referential Integrity: Foreign key constraints ensure that all relationships between tables are maintained, preventing invalid data entry.

Modular Design: The schema is structured to allow easy extensions and modifications.

Data Management: Simplified approach to handling complex data relationships.

Assumptions and Limitations

Basic Information: Only fundamental details are included. Additional information such as educational background, work experience, or salary details is not covered.

Interview Scheduling: Supports a single interview date per interview record.

Position-Hospital Relationship: Each position is associated with a single hospital, with no provisions for shared or multi-hospital roles.

Binary Offer Status: The current implementation only tracks whether an offer is made or not, without intermediate states such as negotiations or pending decisions.

Data Population

The database is populated with sample data created using a combination of stored procedures and external tools (like ChatGPT) to generate realistic mock data for testing purposes. This includes details such as hospital names, candidate information, interview schedules, and required skills.
