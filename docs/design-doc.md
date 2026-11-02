Design Document

1.1: The Problem:
Planning trips can be overwhelming because there are many things to organize, including destinations, activities, transportation, and expenses. I want to create a program that helps users organize their travel plans and keep track of estimated costs so they can stay organized and within their budget.

1.2: Project Idea (The Solution):
I will build a Java-based travel planner that allows users to create trips, organize destinations and activities, and keep track of estimated expenses. The program will calculate the total cost of each trip and help users stay within their travel budget.

2.1: Eisenhower Matrix:

Important and Urgent:
- Add trips with destinations and travel dates.
- Add activities to each trip.
- Calculate and display total estimated trip expenses.

Important but Not Urgent:
- Add weather forecasts for destinations.
- Generate suggested travel itineraries.
- Compare expenses across multiple trips.

Not Important but Urgent:
- Use Java's built-in date/time tools to manage dates.
- Use Java's built-in file handling to save trip information.
- Use Java's built-in sorting tools to organize activities.

Not Important and Not Urgent:
- Create a social media feature to share trips.
- Add hotel and flight booking capabilities.
- Create a complicated graphical user interface.

2.2: Tech Stack:

Language: Java
Libraries, Packages, and External Tools:
- java.util.ArrayList - To store multiple trips and activities
- java.io - To read and write trip information to files
- java.time - To manage travel dates
- java.util.Scanner - to collect user input through the terminal
Data Storage:
- A CSV or text file to save trip information, destinations, activities and expenses
- Data will be loaded when the program starts and saved when changes are made
External Data sources:
- no external APIs
Development tools:
- IntelliJ IDEA - to write and test Java code.
- Git and GitHub - to track changes and store the project


2.3: Chunked Build Plan:
- Set up the GitHub repository and Java project.
- Create the Trip class with destination and travel date fields.
- Add functionality to create and store trips.
- Add functionality to add activities to trips.
- Create a method to calculate total trip expenses.
- Implement file handling to save and load trip information.
- Test all features, fix errors, and update the README.

2.4: System Diagram:
The system diagram shows how the main components of the Travel Planner interact, including the menu, user input, Trip class, Activity class, Expense Calculator, and File Storage.
See System Diagram.
