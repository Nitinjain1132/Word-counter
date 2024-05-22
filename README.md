Overview
The Char Word Count Tool is a Java Swing application that allows users to count the number of characters and words in a given text. Additionally, it provides options to change the background color and text color of the input area using a color chooser dialog.

Features
Character Count: Displays the total number of characters in the text area.
Word Count: Displays the total number of words in the text area.
Background Color Change: Allows users to change the background color of the text area.
Text Color Change: Allows users to change the text color of the text area.
Components
The application consists of the following components:

Labels:
lb1: Displays the count of characters.
lb2: Displays the count of words.
Text Area:
ta: A JTextArea for user input.
Buttons:
b: Button to trigger character and word count.
pad: Button to open the color chooser for changing the background color.
text: Button to open the color chooser for changing the text color.
Class Details
CharCount
This is the main class that extends JFrame and implements ActionListener.

Constructor
The constructor sets up the UI components and their properties:

Initializes and positions labels, text area, and buttons.
Adds action listeners to buttons.
Sets the frame size, layout, visibility, and default close operation.
Methods
actionPerformed(ActionEvent e): Handles the button click events.
When the "click" button is pressed, it counts the characters and words in the text area and updates the labels.
When the "Pad Color" button is pressed, it opens a color chooser dialog to select a background color for the text area.
When the "Text Color" button is pressed, it opens a color chooser dialog to select a text color for the text area.
Main Method
main(String[] args): Instantiates the CharCount class to run the application.
Usage
Run the application. A window titled "Char Word Count Tool - JTP" will appear.
Enter text into the provided text area.
Click the "click" button to count the characters and words in the text area.
The character count will be displayed in the "Characters: " label.
The word count will be displayed in the "Words: " label.
Click the "Pad Color" button to change the background color of the text area.
Click the "Text Color" button to change the text color of the text area.
Dependencies
Java Development Kit (JDK)
Swing library (included in JDK)
Installation
Ensure that you have JDK installed on your machine.
Copy the provided code into a file named CharCount.java.
Open a terminal or command prompt.
Navigate to the directory containing CharCount.java.
Compile the program using the command:
sh
Copy code
javac CharCount.java
Run the program using the command:
sh
Copy code
java CharCount
Contact
For any queries or support, please contact kartikjan2580@gmail.com.

Enjoy using the Char Word Count Tool!





