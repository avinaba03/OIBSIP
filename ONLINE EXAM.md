# OIBSIP
OASIS INFOBYTE INTERNSHIP

TASK 4
ONLINE EXAM

The  code is a Java program for an online exam application. It consists of three classes: login, OnlineTestBegin, and OnlineExam.
The login class is a JFrame-based class that represents the login form for the online exam application. It contains two text fields for username and password input, along with a submit button. When the submit button is clicked, it checks if the password is not empty. If it is not empty, it creates an instance of the OnlineTestBegin class and passes the username as a parameter. Otherwise, it sets the password text field to "Enter Password" and recursively calls the actionPerformed method to handle the empty password case.
The OnlineTestBegin class is also a JFrame-based class and represents the main exam window. It displays a question with multiple-choice answers and allows the user to select an answer. It keeps track of the user's score and the current question. The class uses a timer to display the remaining time for the exam. The user can navigate through the questions, save the current question for later review, or submit the exam to get the final score. The class extends JFrame and implements the ActionListener interface to handle button clicks and other actions.
The OnlineExam class is the entry point of the program. It creates an instance of the login class and sets its size and visibility.
Overall, the code provides a basic structure for an online exam application with a login form, a timer, and a set of multiple-choice questions.
