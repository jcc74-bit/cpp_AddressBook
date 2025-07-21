# cpp_AddressBook

## Person Student Staff- Where I first learned inheritance
####  Write a program that manages information about Persons, Students, Staff, Teacher, and Administrative Staff. The system must use inheritance to reflect the real-world relationships between these roles.
##### Person Class (Base Class) This class will be the foundation for other types of people like students, teachers, and staff with private attributes: name, age, and gender.
##### Student Class (Derived from Person) inherits from Person. It should represent students in the system. Add new private attributes: studentID, major, and GPA.
##### Staff Class (Derived from Person) This class will act as a middle-level class between Person and AdminStaff. Add new private attributes: staffID(string) and position(string). Override displayInfo() by calling the base class displayInfo() using Person::displayInfo().
##### Teacher Class (Derived from Staff) inherits from Person. It should represent teachers in the system. Add new private attributes: employeeID, department, and an array of up to 5 courses they teach. Override displayInfo() to include the teacher’s department and courses. Add a method called addCourse(string courseName) that adds a course to the list.
##### AdminStaff Class (Derived from Staff) Add new private attributes: officeNumber and adminLevel (integer from 1 to 5). Add a method called promote() that increases adminLevel by 1 (maximum 5), and prints the new level.

###### Store them in an array or vector of Person and call displayInfo() using polymorphism.

## Address Book System

#### In this assignment, I designed and implemented an AddressBook class in C++ that allows users to store, retrieve, and manage contact information. The goal is to practice object-oriented programming (OOP) concepts, including constructors, getters, setters, dynamic memory management, and basic file handling. This was done in multiple parts and combined into a bigger project. 


### Part 1 : The Contact Class 
#### Attributes (Private):
##### name (string) – Full name of the contact
##### phoneNumber (string) – Contact's phone number
##### email (string) – Email address
##### address (string) – Home address with house number, street, city state and zip
###### Include public getters and setters and constructors for the Contact class.

## Part 2: The AddressBook Class
#### The AddressBook class stores multiple contacts in a vector or array.
### Methods to Implement:
#### Constructor(s): Initialize an empty address book.
#### Add a new contact: A method to add a contact to the address book.
#### Search for a contact: Find a contact by name and return the details.
#### Display all contacts: Print a list of all stored contacts.
#### Delete a contact: Remove a contact by name.


## [Part 3] The Address class
### The Address class contains the following attributes:
#### houseNumber, streetName, city, state, zip, country

## [Part 4] - Creating an AddressBook with External Data.
#### Reading a file and create contact objects for each entry. 

## [Part 5] - Sorting out the Address Book
#### Write the sortByLastName() method that sorts the vector elements in AddressBook class by their last name (then by first name) alphabetically.
##### Did not use the built in sorting method for vectors.


## [Final] - Address Book Application
#### Made a Menu System and mini menus within menus to ensure address book had every feauture from being able to add/delete contacts to being able to change certain things about a contact.
