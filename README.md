Healthcare Data Management and Analysis System
README
January 2026


1 Project Overview

The Healthcare Data Management and Analysis System is a Python-based application devel-
oped to digitally manage healthcare-related records such as patient information, doctor details,
appointments, and billing data. Along with record management, the system provides basic
analytical insights using statistical techniques implemented entirely in Python.
The project avoids the use of databases or external libraries and instead relies on file-based
storage using text and CSV files. This approach ensures simplicity while demonstrating strong
programming fundamentals.


2 System Requirements
• Python Version: 3.7 or higher
• Supported Platforms: Windows, Linux, macOS
• External Dependencies: None


3 Project Structure
The directory structure of the project is organized as follows:
Healthcare_Data_Management_System/
healthcare.py # Main application file
patients.txt # Stores patient records
doctors.csv # Stores doctor information
appointments.csv # Stores appointment details
billing.csv # Stores billing records
README.tex # Project documentation
All files are maintained within the same directory for consistent execution.


4 Execution Guidelines
The application uses relative file paths for reading and writing data. Therefore, the source code
file and all related text and CSV files must remain in the same folder. Separating files into
different directories may lead to file handling errors.


5 Input Description
5.1 User Interaction
All inputs are taken through a menu-driven console interface. The system requires the following
information from the user:
• Patient data: ID, name, age, gender, and contact number
• Doctor data: ID, name, age, department, and consultation fee
• Appointment data: patient ID, doctor ID, and appointment date
• Billing data: patient ID, doctor ID, and billing amount
5.2 Input Validation
• Age values must be non-negative
• Billing amounts must be numeric
• Invalid inputs are handled using exception handling mechanisms
6 Execution Steps
6.1 Environment Setup
Open a terminal or command prompt and navigate to the project directory containing the
source code.
6.2 Program Execution
Run the application using the following command:
python healthcare.py
6.3 Menu Operations
Once executed, the program presents a menu allowing users to perform patient registration,
doctor addition, appointment booking, bill generation, record searching, and healthcare data
analysis.


7 Output Description

7.1 Console Output

The console displays confirmation messages for successful operations along with statistical re-
sults generated during analysis.

2

7.2 File Output
The system automatically creates and updates the following files:
• patients.txt for patient demographic data
• doctors.csv for doctor-related information
• appointments.csv for appointment records
• billing.csv for billing details
These files act as persistent records and remain available for future executions.
8 Execution Flow
The internal working of the application follows this sequence:
1. Accept input through the menu interface
2. Validate and process entered data
3. Store records in appropriate files
4. Perform statistical analysis when requested
5. Display results and update stored files
9 Notes
• No manual configuration is required before execution
• All files are automatically managed by the program
• The system can handle increasing data volume efficiently
• This project is intended solely for academic and educational use
