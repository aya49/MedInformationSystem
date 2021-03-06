# Medical Information System

This is a demo of a medical information intended for a doctor's office. This information system is supported by an SQL database back-end. The system was built on Oracle APEX.

+ [SQL_tables](./SQL_tables) includes the sql and plsql used to build the information system. Some features include patient appointment scheduling, drug-drug reaction warnings, and patient information summary including a patient's history.
+ [oracle_APEX_UI](./oracle_APEX_UI) contains pieces of code used in the profile page UI.
+ [trigger_adverseDrugAffect](./trigger_adverseDrugAffect) is the plsql used to create a trigger when clinicians prescribe drugs that may produce adverse effects when taken together.
+ [db_interaction.jpg](./db_interaction.jpg) is the interaction diagram that describes the human computer interaction that
+ [database.sql](./Database.sql) is the sql used to make the database.
 would occur between a medical professional (user) and the information system.
+ [ERD.jpg](./ERD.jpg) is the ERD (Entity Relationship Diagram) that displays the design of the database.
+ More materials to come :)

## System Preview: (Patient Profile)

Oracle APEX Login: http://apex.oracle.com/pls/apex/
 + Workspace: H201
 + User: Silverlo@Uvic.ca
 + Password: 123sjx
 + Application: H201 The Hospital

Note: online preview has expired

![PP](./patient_profile.png)
