# Elevate-Labs_TASK1
Task 1: Data Cleaning and Preprocessing

 ### Objective: Clean and prepare a raw dataset (with nulls, duplicates, inconsistent formats).
 For my Data analytics task i have taken "Medical Appointment No Shows" dataset from kaggle.
 my goal is to prepare the dataset by resolving inconsistencies, missing values, and formatting issues.
 so i have used following steps,
 1) Identified missing values using .isnull() in Python by importing pandas and used dropna() to drop rows which contain null values
    or we can use fillna() to fill null values with appropreate like mean,mode.
 2) Used .drop_duplicates() to remove duplicate rows.
 3) Cleaned categorical fields like Gender and Neighbourhood by applying consistent casing (e.g., uppercase for gender and title for nighbourhood).
 4) Converted date fields (ScheduledDay, AppointmentDay) into consistent dd-mm-yyyy format.
    and ensured datetime fields were correctly recognized as datetime64 in Pandas.
 5) Renamed all column headers to lowercase and replaced spaces with underscores for consistency and compatibility.
 6) Verified and enforced correct data types:
    Age as integer, 
    ScheduledDay and AppointmentDay as datetime

After cleaning, the dataset is well-structured, consistent, and ready for exploratory analysis.This foundation ensures more accurate modeling, better insights, and reduced risk of data quality issues.
