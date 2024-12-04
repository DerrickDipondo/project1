# Week 1 Coding Challenge

## Instructions

-Create a repository on your GitHub account(One folder, with 3-4 files for each solution. Please note that a single file should only hold one solution).
-The solutions to this problems should be writtedn in JavaScript.
-Push the solution to the above repository once done.
-Submit the repository link for grading.
-Ensure your repository has a well written README.
-NOTE: You are required to complete ALL the challenges.

# Challenge 1: Student Grade Generator (Toy Problem)

## Feature

-This is a program that prompts the user to input student marks. The input should be between 0 and 100. The output is meant to correspond the correct grade, as shown below:
   A > 79, B - 60 to 79, C -  59 to 49, D - 40 to 49, E - less 40.

The program utilises the readline module to handle user input from the console.

## Installtion

-Clone the repository
-Navigate to the project directory
-Install Node.js if it's not already installed.

## Usage

-The program will prompt you to enter the student's mark upon running it.
-It'll then proceed to calculate the grade and display it.
-The program will not allow to engter a value outside the range of 0 to 100. It'll always prompt you to enter a valid range.

## Code Explanation

-readline functionality is major feature in this program as it allows the user to input a value from the console.
- It checks if value is valid and then proceeds to display the grade.

## License

-Not required.

# Challenge 2: Speed Detector (Toy Problem)

## Feature 

-This is a program that is meant to determine if the user's input is the appropriate speed.
-For every 5 km/s above the speed limit (70), it should give the driver one demerit point and print the total number of demerit points.

   Point in case: if the speed is 80, it should print: “Points: 2”. If the driver gets more than 12 points, the function should print: “License suspended”.

## Installation

-Clone the repository
-Navigate to the project directory
-Install Node.js if it's not already installed.

## Usage

-The program will prompt the user to enter the speed of the driverupon running it.
-If the speed is within the limit the program will print "Ok".
-If the speed exceeds the limit the program will print the number of demerit points.
-The license will be suspended if the driver accumalates more than 12 demerit points.

## Code Explanation

-readline functionality is major feature in this program as it allows the user to input a value from the console.
-The program calculates whether the driver is over the speed limit and how many demerit points they should receive.
--The license will be suspended if the driver accumalates more than 12 demerit points.

## License

-Not required.

# Challenge 3: Net Salary Calculator (Toy Problem)

## Feature 

The program calculates an individual's Net Salary by getting the inputs of basic salary and benefits. For this to be done, the program has to calcualte the payee, NHIF Deductions, gross salary and net salary.

The up to date dnumbers can obtain thhrough the following links:
..[KRA](https://www.kra.go.ke/individual/calculate-tax/calculating-tax/paye)
  [Links to an external site](https://www.aren.co.ke/payroll/taxrates.htm)

## Installation

-Clone the repository
-Navigate to the project directory
-Install Node.js if it's not already installed.

## Usage

-The program will prompt to you enter the followinf:
   (i) Basic Salary
   (ii) Benefits
-The program will then proceed to calculate the following:

   (i) Gross Salary
   (ii) PAYE Tax
   (iii) NHIF Deductions
   (iv) NSSF Deductions
   (v) Net Salary

-The program will then output a breakdown of the salary including:

   (i) Basic Salary
   (ii) Benefits
   (iii) Gross Salry
   (iv) PAYE Tax
   (v) NHIF Deduction
   (vi) NSSF Deduction
   (vii) Total Deduction
   (viii) Net Salary

## Code Explanation

-readline functionality is major feature in this program as it allows the user to input basic salary and benefits.
-The gross salary is calculated by adding the basic salary and benefits.
-The program calculates the PAYE Tax based on the Gross Salary using different tax rates for various income brackets:

   (i) Up to 24,000 Ksh: 10%
   (ii) 24,001 to 32,333 Ksh: 25%
   (iii) 32,334 to 500,000 Ksh: 30%
   (iv) 500,001 to 800,000 Ksh: 32.5%
   (v) Above 800,000 Ksh: 35%
-The NHIF Deduction is calculated based on predefined rates based on the Gross Salary ranges.
-The NSSF Deduction is calculated as 6% of the Basic Salary.
-The Net Salary is calculated by subtracting the total deductions (PAYE, NHIF, and NSSF) from the Gross Salary.
-After performing the calculations, the program outputs a breakdown of the salary, including all deductions and the final Net Salary.

## License
-No license is required













