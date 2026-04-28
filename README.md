Medical Practice Directory Management
Description
This project is a console-based Medical Practice Directory Management system developed in C. It is designed to manage persistent data for doctors and patients by combining the power of C structures and binary file handling. The system allows for efficient data organization, storage, and retrieval, serving as a robust database for small medical practices.

Features
Structured Data: Uses custom struct types to organize doctor and patient records.

Persistent Storage: Data is stored using binary files (doctors.dat and patients.dat) to ensure information is saved on disk.

Interactive Menu: A user-friendly looping text interface for managing records.

Operations:

Create and add new entries.

Display full lists of doctors and patients.

Getting Started
Prerequisites
You will need a C compiler installed (like gcc via MinGW).

Installation & Compilation
Download the code or clone this repository.

Open your terminal or VS Code in the project directory.

Compile the code using the following command:

Bash
gcc main.c -o MedicalDirectory.exe
Run the program:

Bash
./MedicalDirectory.exe
Usage
Upon running the application, you will see a main menu:

Add Doctor: Enter registration details, specialty, and contact information.

Display Doctors: View all saved doctor records.

Add Patient: Enter ID, personal details, illness type, and appointment date.

Display Patients: View all saved patient records.

Exit: Safely terminate the application.

Project Structure
Doctor Struct: Stores Registration Number, Name, Specialty, Address, Phone, and Email.

Patient Struct: Stores ID, Name, Age, Address, Illness Type, Phone, and Appointment Date.

Binary Files: The system writes and reads binary data to ensure data integrity and persistence.

License
Developed as part of the Algorithmic and Data Structure 2 module at the University of Mustapha Stambouli, Mascara.
