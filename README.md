🔐 Login Simulator
📖 Description

The Login Simulator is a simple Java console-based program that mimics the basic functionality of a login system. It prompts the user to enter a username and password and then validates the input against predefined credentials.

If the entered username is "admin" and the password is "admin123", the program displays:
✅ Login Successful!

For any other combination, the program displays:
❌ Invalid Credentials. Please try again.

This project demonstrates how conditional statements and logical operators are used to control access in applications.

⚙️ How It Works

The program asks the user to input their username and password using the Scanner class.

It compares the entered values with the expected credentials (admin / admin123).

Using an if-else condition and the logical AND operator (&&), it validates whether both inputs match.

Based on the result, it prints either a success or error message.

💻 Example Run

✅ Successful Login:

Enter username: admin
Enter password: admin123
Login Successful!


❌ Invalid Login:

Enter username: user
Enter password: pass123
Invalid Credentials. Please try again.

📂 Key Features

Accepts username and password input from the user.

Demonstrates string comparison in Java using .equals().

Uses if-else logic for decision making.

Illustrates the use of the logical AND operator (&&).

Beginner-friendly demonstration of a simple authentication mechanism.

🎯 Learning Outcomes

By completing this program, learners will:

Understand how to handle String input in Java.

Learn how to use .equals() for comparing text values.

Gain practical experience with if-else conditions and logical operators.

Recognize how basic login systems work in applications.
