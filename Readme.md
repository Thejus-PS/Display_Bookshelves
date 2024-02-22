#Display Bookshelves

**Project Overview**
 
This project is a Maven-based Java project that uses Selenium WebDriver, TestNG, and Extent Reports to test the functionality of the website ‘Display Bookshelves’.
 
*The project consists of the following test cases:*

•	Display the name & price of first 3 Bookshelves below Rs. 15000, with Category type as Kids Bookshelves & exclude out of stock,Sort by price "High 	to Low", fetch the top 3 items & print all details in console output.

•	From Living, retrieve all items under any one of sub-menu items like  "Seating & Chairs" or "Living Storage". Also print the same in console output.

•	Gift cards - choose "Birthday/Anniversary"; fill customize the gift card; fill from to details with any one input invalid (example: email); Capture 	& display the error message
 
**Project Structure**
 
1.Maven Repository
 
- Version: 3.12.1
- Purpose: Used for project Management and dependency resolution.
 
2.Dependencies
  
TestNG
- Version: 7.9.0
- Purpose: Framework for test automation that allows for parallel execution and flexible test configuration.
 
Extent Report
- Version: 5.1.1
- Purpose: Generates interactive and detailed HTML reports to enhance test result analysis.
 
Selenium
- Version: 4.15.0
- Purpose: Enables interaction with web elements, navigation, and form submission in the browser.

 
**Automation Test Flow**
 
1. Open Chrome/Edge browser

- Search for the urbanladder.com website.
 
2. Search for Bookshelves

- Select "kids Bookshelves" under categrory.
- Restrict the price of the bookshelves to maxiumun of Rs.15000 through the slider.
- Exclude out of stocks.
- Sort by price High to Low 
- Fetch the top 3 items & print all details in console output.

3. Hover on the "Living" menu

- Retrieve all items under any one of sub-menu items like  "Seating & Chairs" or "Living Storage"
- Print all the options in the console.

4. Click on Gift Cards option.

- Hover to Birthday/Anniversary
- Click "Choose this" button.
 
5. Under Customize your gift card

- Enter amount between Rs.1000 and Rs.500000.
- Select month.
- Click Next button.

6. Under Nice! So who is this lucky person?

- Enter all the details with any one invalid input(ex:email).
- Capture the error message and also print the same in the console.
- Correct the invalid input by giving correct one.
- Enter a message.
- Click on Confirm button.

7. Under Confirm the details

-Validate all the provided details is correct or not.


**Screenshots**

- Taking the screenshot for every requirement.

**How to Run the Tests**
 
1. Open Eclipse IDE:
- Launch Eclipse IDE on your machine.
 
2. Import Project:
- Select 'File' -> 'Import' from the menu.
- Choose 'Existing Maven Projects' and click 'Next'.
- Browse to the directory where you cloned the repository and select the project.
 
3. Update Maven Project:
- Right-click on the project in the Project Explorer.
- Choose 'Maven' -> 'Update Project'.
- Click 'OK' to update dependencies.
 
4. Run Test Suite:
- Locate the test suite file (e.g., 'src/test/java/TestSuite.java').
- Right-click on the file and choose 'Run As' -> 'TestNG Suite'.
 
6. View Reports:
- After execution, open the 'report' folder.
- Find the Extent Report HTML file ('myReport.html') for detailed test reports.
 
**Author Information**
 
- Thejus P S(2303482)


**Disclaimer**
 
This project is intended for educational and testing purposes only. The authors are not responsible for any unauthorized use or modification of the code. Use at your own risk.
