# Library_Management_System
LMS is about organizing,managing the library and library-oriented tasks.It involves maintaining the database of records of books issued,student records etc..

Library Management System
Application:
LMS is designed to automate routine library tasks such as adding new books,adding user data,issuing books and updating the database etc..It helps to provide real-time access to library resources such as books,journals etc..All the library tasks are performed with the help of a menu interface.It is developed using c++ programming language.Books,students(users) and books issued to the students are stored in avl trees.Employee data and books issued by a individual student are stored in the form of a linked list.

It is a project developed and run on a windows operating system.Changing the file path (replacing backward slash by forward slash) may help to execute the project on any system.


How to setup the project on a local machine?

1.Download the project onto the local machine(PC).
2.Change the file path(if not windows OS).
3.Compile and execute the main.cpp file.
4.Enter the necesssary data(id and password) from the txt files available so that one can get access to the menu.
5.Choose the action appropriately to perform different library tasks.

cpp files   : main.cpp,load_data.cpp,input_action.cpp,book.cpp,student.cpp,issue_book.cpp,student_functions.cpp,emp_functions.cpp     
text files  : book.txt,student_info.txt,lib_emp.txt,book_issue.txt       
              book_issue_dup.txt,student_info.txt(duplicate files used inorder to update data in the above txt files).       
header file : header.h

Detailed explanation of the files and the functions:

header.h : It contains the definition of the nodes to store the data in the form of avl trees and the functions are defined to perrform various tasks.

load_data.cpp:loads the data and stores it in the form of avl trees so that searching and retrieval of information gets easier.All the root nodes are updated after executing this functions.

input_action.cpp:displays the menu and verifies the id and password of the user or the library employee.

book.cpp,student.cpp and issue_book.cpp:contains the functions to insert node and balance the respective avl tree.

student_functions.cpp:contains functions that performs student tasks such as      
1.search books by book_id      
2.search books by book_name    
3.search books by author_name   
4.view all the books available   
5.books issued by the student   
6.Calculate Fine             

emp_funtions.cpp:performs tasks that can be done by a librarian such as   
1.Add new students    
2.Add new books               
3.Issue the book                 
4.Return the book             
5.Renew the book                 
6.Delete student record         
7.Show Students(Users)
