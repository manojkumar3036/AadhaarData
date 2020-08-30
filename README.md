# Aadhaar Data Analyze

## Problem Statement: Write a MapReduce program that performs the following on the Aadhaar dataset:
1. Count the Male Residents and Female Residents in each state who have enrolled in Aadhaar
2. Count the rejected residents in each state
3. Count the rejected residents in each state and then calculate the average of the rejected residents in India (You have to write two MR jobs that takes output of first job as input to the second job)

## Dataset: 
aadhaar_data.csv

## Data Fields:
- Registrar
- Enrolment agency
- State
- District
- Sub District
- Pin Code
- Gender
- Age
- Aadhar generated
- Enrolment Rejected- If the value '1'  it indicates that resident is rejected
- Residents providing email
- Resident providing mobile number
