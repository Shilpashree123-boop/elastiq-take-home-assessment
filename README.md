Overview
This project contains a Python script (qa_selenium_test.py) that automates testing the Table Search Demo on the Selenium Playground. The test case validates that searching for "New York" filters the table correctly to show 5 entries, and ensures that there are 24 total entries in the table.

Approach
Environment Setup: Uses the Selenium WebDriver to automate interactions with a web browser.
Search Simulation: Inputs the text "New York" in the search box.
Validation: Confirms the number of visible rows matches the expected result and verifies the total row count in the table
