# Loan Qualifier Application

This application allows users to input specific credit data in order to receive a list of loans they qualify for based on their 
1) credit score
2) monthly debt
3) monthly income
4) home value
5) amount of desired loan
Based on this data, a comprehensive selection will be provided to the user.

---

## Technologies

The technologies incorporated in this application are 'sys', 'fire', 'pathlib' and 'questionary' as primary. These libraries allow for the data input by the user to go through a series of evaluation calculations while comparing those results to a set datasheet of possible loans and banks from which the results will pick individually tailored loan options for the user. 

---

## Installation Guide

1. Download folder containing files.
2. Open new terminal/CLI and input "python app.py" to run application
3. provide filepath to 'daily_rate_sheet.csv' located in 'data' folder included in application folder.

---

## Usage

User will be prompted by dialog text to input specific data pertaining to different evaluation points. 
Once data is input, command line will show the number of qualifying loans available to the user. 
User will be prompted to save or disregard a copy (.csv) of the list of qualifying loans.
System will save a copy of the data as a .csv file in user selected file path then proceed to exit the application.
-If user decides to disregard the copy of loans, exit message will display and system will exit application.

---

## Contributors

Juan Bohorquez
jsbohorquez92@gmail.com

---

## License

When you share a project on a repository, especially a public one, it's important to choose the right license to specify what others can and can't with your source code and files. NO changes to be made to this code***
