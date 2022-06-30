# Health-Tracker-Database
The application of this database focuses on health tracking. 
The database is comprised of data involving water intake history, weight history, exercise history, and meal history.

This database was created using SQLite3.

# Database Requirements
Consider a health tracker database where users input their daily exercise, meals, weight, and water intake. The data requirements are summarized as follows:

Each user has an username and an ID that uniquely identifies them. The user has a water history that tracks the ounces of water they drink on a particular day.The user has a weight history that tracks their weight (in pounds) on a particular day. The user has an exercise history that tracks their workout on a particular day which includes: exercise name, number of sets, number of reps, and can track the amount of weight they are lifting (if applicable). The user has a meal history that tracks what they are eating on a particular day which includes: calories, amount of carbohydrates, amount of fats, amount of proteins, food name, timestamp, and date. The user has a water history that tracks the total ounces of water consumed on a given date. The history for a particular user is referenced by the user ID.

Entity Relationship Diagram for Database:
<img width="544" alt="Capture" src="https://user-images.githubusercontent.com/76569535/176791442-6db1a3e5-ea86-4800-b885-71d001422f24.PNG">

# Database Relations
All relations are in BCNF. Due to the database design each relation only has one functional dependency.

# Example Select Statements
Note: Due to the time sensitivity of using date(‘now’), which references the current day’s date, SQL statements will return nothing as the data is “out of date”. Currently, the data only goes up to the date 12/13/2021. However, these queries worked as of testing, 12/13/21. 

# Lesson Learned
Follow a consistent naming convention from the start, since a lot of time was spent correcting this issue.
