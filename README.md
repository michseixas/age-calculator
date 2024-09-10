This is a simple Age Calculator web application built with HTML, CSS, and JavaScript. The user can input their date of birth, and the application will calculate and display their exact age in years, months, and days.

Features

	•	Allows users to input their date of birth using an HTML <input type="date"> field.
	•	Calculates the user’s current age (years, months, and days) based on the selected birthdate.
	•	Ensures that users cannot select a future date using JavaScript validation.
	•	Displays the calculated age on the page dynamically without refreshing.

Usage Instructions

	1.	Open the Age Calculator in a web browser.
	2.	Input your birthdate in the date picker.
	3.	Click the “Calculate” button to see your age displayed in years, months, and days.

Code Details

	1.	HTML Structure:
	•	The layout includes an input field for the date and a button to trigger the age calculation.
	•	The result is displayed in a <p> element below the input field.
	2.	JavaScript Logic:
	•	The script calculates the difference between the current date and the selected birthdate.
	•	It adjusts for month and day overflows (e.g., when the current day/month is earlier than the birthdate day/month).
	•	The getDaysInMonth() function ensures that the correct number of days in a month is used for the day calculation.
	3.	Validation:
	•	The input’s max attribute is set to today’s date to prevent users from selecting a future date.


   Enjoy =^..^=
  
 Age Calculator:
 ![Example Image](/app-age-calculator.png)

  Pick birth date:
 ![Example Image](/pick-bdate.png)

  Display age:
 ![Example Image](/display-age.png)

 Great tutorial by GreatStack.