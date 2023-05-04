# Automation Testing Readme for https://qa-admin.trado.co.il/ using Python and PyCharm
This document provides an overview of the automation testing strategy, tools, and frameworks used for testing the dashboard, orders, products, users, and department sections of the website https://qa-admin.trado.co.il/ using Python and PyCharm. The tests will be written using Selenium WebDriver and pytest and will be organized and reported using Allure. PyMongo will be used for interacting with the database to ensure data integrity and consistency.

# Automation Testing Strategy
The automation testing strategy for https://qa-admin.trado.co.il/ using Python and PyCharm focuses on ensuring that all critical features and functionalities of the dashboard, orders, products, users, and department sections are thoroughly tested. The tests will be designed to cover both positive and negative scenarios, with an emphasis on the following areas:

User authentication and authorization
Navigation and usability
Form validation and submission
Error handling and reporting
Data integrity and security
The tests will be run on a regular basis to ensure that any bugs or issues are detected and resolved as soon as possible.

# Tools and Frameworks
The following tools and frameworks will be used for automation testing of https://qa-admin.trado.co.il/ using Python and PyCharm:

Selenium WebDriver: A popular open-source tool for automating web browsers. It will be used for testing user interactions and verifying that the website behaves as expected.
PyCharm: An integrated development environment (IDE) for Python that provides a range of features for debugging, testing, and code analysis. It will be used for writing, organizing, and running the test suite.
pytest: A Python-based testing framework that provides a simple and powerful way to write and run tests. It will be used for organizing and running the test suite.
Allure: An open-source framework for generating interactive HTML reports for test results. It will be used for organizing and reporting test results.
PyMongo: A Python library for interacting with MongoDB databases. It will be used for ensuring data integrity and consistency.
# Running the Tests
To run the automated tests for https://qa-admin.trado.co.il/ using Python and PyCharm, follow these steps:

Clone the repository to your local machine.
Install Python and PyCharm if you haven't already done so.
Open PyCharm and create a new project from the cloned repository.
Install the required Python packages by running the following command in the terminal:
Copy code
pip install -r requirements.txt
Once the packages are installed, navigate to the tests directory and open the desired test file.
Right-click on the test file and select "Run 'pytest in test_file.py'" to run the tests.
The tests will be run in the default browser (Chrome) and the results will be displayed in the console and in the HTML report located at allure-report\index.html.
# Conclusion
By following the above steps, you can automate the testing of the dashboard, orders, products, users, and department sections of the website https://qa-admin.trado.co.il/ using Python and PyCharm, and leveraging Selenium, pytest, Allure, and PyMongo to ensure data consistency and accuracy. This approach can save time and effort while ensuring that the website functions as expected and meets the requirements.