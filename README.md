**Project Name**

Automated Data Extraction and User Creation

**Description**

This project automates the process of data extraction and user creation using UiPath Studio. It performs a series of steps, including reading an email, downloading an Excel file, creating an account on a website, enabling a VPN, extracting data from the Excel file, saving the data, calling an API to add user information, and sending result files via email. The process will be stopped if no email is received for 5 minutes.

**Usage**

Run the project by clicking on the Start button in UiPath Studio or pressing F5.
Wait for the test email to arrive in your inbox and read it. Download the attached Excel file and place it in the specified output folder.
Open the hide.me VPN desktop application and enable the VPN without signing in.
Follow the instructions given in the project output to create or update your account on the hide.me website. Solve the captcha image if prompted.
The project will read the data table from the downloaded Excel file.
For each record in the data table, the project will perform the following steps: a. Generate random user information using the Fake Name Generator website. b. Save the extracted data in the result Excel file. c. Call the specified API to add user information and retrieve the ID from the response. d. Save the data in the result Excel file and summary CSV file.
Once all records are processed, the project will send the result Excel file and summary CSV file via email to the specified receiver emails.
The project will wait for a new email, and if no email is received for 5 minutes, the process will be stopped.
