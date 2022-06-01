# Assignment2
Waterfall
Requirements definition 
Services – the user can do certain actions depending on what type of user they are 
Constraints – the user can only select one of three choices identifying themselves, no other option would work 
Goals – to allow the user to go through the system and complete anything they need to do with their schedule, roster, courses, etc. 

System and Software Design 
System Architecture - Leopard Web 
The user can enter their first name, last name and id number to login to the system 
They will enter the system to which they can choose what they want to do 

Implementation and system testing 
Create a user, student, instructor and admin 
Each will inherit attributes from the other, the admin can use everything that the instructor and student can use 

Integration and system testing 
Test system 
Enter name and id 
Identify as a student, instructor or admin 
Options will be put up and the user selects the action they want to execute on the system 
Those specific actions will be executed, and the user can continue to use the system 

Operation and maintenance 
When run, edit any error that may occur 

Incremental
Step 1: 
The user interface will allow the user to enter their name and id to get them into the system 

Step 2:  
Create 4 classes, user, student, instructor, admin with the specific attributes and methods 
Each class will inherit one another's methods and attributes 

Step 3: 
The student and instructor will have a space where all the classes are stored and for the instructor, their class roster  
It will also include a database that all the information that the student and teacher do will be saved to 

Step 4:  
The admin will have control over the entire system, having the ability to add/remove users, add/remove courses, etc. 
The database for the admin will include all that they have plus the student and the instructor 

Step 5: 
The final version will consist of classes that allow the specified user to successfully go through the system and do the tasks they need to do 

Integrate and Configure
Other school websites have similar requirements that will allow the user to do what they need to do 
Adding address and phone number to the database to be saved 
Parts of the classes would be revised to accommodate the standards of needing certain user information 
The database would store information from the modified version of the program 
