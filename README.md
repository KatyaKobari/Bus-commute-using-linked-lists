# Bus-commute-using-linked-lists
*  Implement a system, that is based on Linked 
  List, to assign passengers to various busses to help them commute 
  based on their scheduled times.

Functionality:
- Loading Data: The program allows loading data for buses and passengers from text files.
  
- Assigning Passengers to Buses: It assigns passengers to buses based on their availability and specific criteria like date, time, source, and destination.
 
- Printing Information: Users can print information about all buses, specific buses along with their passengers, and unmatched passengers.
  
- Adding and Deleting Passengers/Buses: It supports adding new passengers, deleting passengers by ID, and deleting buses by number.
  
Structure:
- Main Function: The main() function serves as the entry point and orchestrates the program's flow by displaying a menu and executing corresponding actions based on user input.
  
- Linked List Implementation: The program utilizes linked lists to manage buses and passengers efficiently. It defines structs for Bus and Student (passenger) and provides functions for creating, accessing, 
  modifying, and deleting nodes in these linked lists.
  
- File Handling: Functions like loadBuses() and loadStudents() read data from text files and populate the linked lists accordingly.
  
- Assignment Logic: The MainAssignStudents() function handles the assignment of students to buses, considering various conditions such as available space and matching criteria.
  
- User Interface: The printMenu() function displays a menu of options for the user to interact with the program.
  
- Helper Functions: Several helper functions assist in tasks like printing lists, finding nodes, and inserting/deleting elements from linked lists.
  
