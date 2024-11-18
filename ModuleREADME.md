Vehicle Builder


Description
The Vehicle Builder project allows users to create and manage vehicles, highlighting OOP principles in action while utilizing TypeScript.

Key Features:
Inheritance: A base Vehicle class is extended to create specific types like Car, Truck, and Motorbike.
Polymorphism: Implemented through methods such as start, accelerate, decelerate, stop, turn, and reverse.
Composition: The Truck class introduces specialized methods (e.g., towingCapacity and tow).
This project serves as an educational tool for modeling real-world systems using OOP concepts.

Table of Contents
Installation
Usage
License
Contributing
Tests
Questions

Installation

Clone the Repository:
Run the following command in your terminal to clone the repository:

bash
Copy code
git clone <repository_url>
Replace <repository_url> with the actual URL of the repository.

Navigate to the Project Directory:

bash
Copy code
cd <project_directory>
Replace <project_directory> with the project folder's name.

Install Dependencies:

bash
Copy code
npm install
Run the Project:

bash
Copy code
npm run start
This compiles the TypeScript files into JavaScript and runs the application.

Usage
Steps to Use the Application:
Select “Create a new vehicle” or “Select an existing vehicle”.
If creating a new vehicle:
Choose from Car, Truck, or Motorbike.
Enter the required details.
Perform actions for the selected vehicle, such as “Tow another vehicle” for a truck.
Follow the prompts for specific actions and view results in the command interface.
To exit, select “Exit”.

License
This project is licensed under the MIT License.

Contributing
Author:
Parker Speares

Tests
Creating a Vehicle:
Run the application, create a vehicle, and perform an action.
Verify the correct output for the action.

Using an Existing Vehicle:
Select an existing vehicle and perform an action.
Ensure the output matches expectations.

Exiting the Application:
Choose “Exit” and confirm the application closes properly.

Invalid Inputs:
Test with incorrect inputs (e.g., a non-existent vehicle type).
Verify error messages and prompts for retry.

Edge Cases:
Test minimum/maximum attribute values (e.g., speed for a car).
Ensure unavailable actions for certain vehicles are handled gracefully.

Questions
Feel free to contact me with any questions!





