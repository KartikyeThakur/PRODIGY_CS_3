# PRODIGY_CS_3
A tool that assesses the strength of a password based on specific criteria and provides real-time feedback. The interface features a dark theme with neon lights for an attractive and user-friendly experience. It also includes a button to copy the password to the clipboard.

# Password Complexity Checker with Dark Background and Neon Lights

## Description
The **Password Complexity Checker** is a tool designed to assess the strength of a password based on specific criteria and provide real-time feedback. It features an attractive dark theme with neon lights to enhance user experience. The tool evaluates passwords based on their length, presence of uppercase and lowercase letters, numbers, and special characters, and provides a visual indication of password strength. Additionally, it includes a button to copy the password to the clipboard.

## Features
- **Real-time Password Strength Assessment**: The password is evaluated as the user types, providing immediate feedback.
- **Detailed Criteria**: Checks for length, uppercase letters, lowercase letters, digits, and special characters.
- **Dark Theme with Neon Lights**: An eye-catching design that is both modern and user-friendly.
- **Copy to Clipboard**: Easily copy the password to the clipboard with a single button click.
- **User-friendly Interface**: Intuitive and easy to use.

## Installation

### Prerequisites
Ensure you have Python installed on your system. If not, you can download it from [python.org](https://www.python.org/).

### Install Tkinter
Tkinter is a standard GUI library for Python and comes pre-installed with Python. If it is not installed, you can install it using pip:
```bash
pip install tk
```

## Usage

### Running the Script
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/KartikyeThakur/PRODIGY_CS_3.git
   ```
2. **Navigate to the Directory**:
   ```bash
   cd password-complexity-checker
   ```
3. **Run the Application**:
   ```bash
   python password_checker.py
   ```

### Using the Tool
1. **Enter Password**: Type your password into the entry field.
2. **View Feedback**: Real-time feedback will be displayed, indicating the password's strength and which criteria it meets.
3. **Copy Password**: Click the "Copy Password" button to copy the password to the clipboard.

## Demo
![Screenshot (127)](https://github.com/user-attachments/assets/129aa4a0-d1cd-4c36-86db-64d83dfde381)

## Detailed Functionality

### Password Complexity Check
The tool assesses the complexity of a password based on the following criteria:
- **Length**: The password should be at least 8 characters long.
- **Uppercase Letter**: The password should contain at least one uppercase letter.
- **Lowercase Letter**: The password should contain at least one lowercase letter.
- **Digit**: The password should contain at least one digit.
- **Special Character**: The password should contain at least one special character (e.g., `!@#$%^&*()-_+=`).

### Real-time Feedback
As the user types, the tool evaluates the password and provides feedback on the following:
- Overall password strength (Weak, Medium, Strong).
- Specific criteria met (e.g., presence of uppercase letters, digits).

### Copy to Clipboard
A button is provided to copy the entered password to the clipboard for convenience.

## Code Explanation

### Main Application Setup
The Tkinter library is used to create the GUI, set up the main window, and configure its appearance.

### Password Strength Function
This function evaluates the password based on the criteria mentioned above and returns the strength and details of the criteria met.

### Feedback Update Function
This function updates the feedback label in the GUI with real-time information about the password's strength and criteria met.

### Copy to Clipboard Function
This function copies the password from the entry field to the clipboard and provides a confirmation message.

## Lessons Learned
- **Real-time Feedback**: Implementing real-time feedback mechanisms in a Tkinter application.
- **User Experience**: Enhancing user experience with customized themes and intuitive design.
- **Clipboard Integration**: Adding clipboard functionality to Tkinter applications.

## Optimizations
- **Add Strength Meter**: Incorporate a visual strength meter to represent password strength.
- **Password Suggestions**: Provide users with suggestions to improve password strength.

## Run Locally

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/password-complexity-checker.git
   ```
2. **Navigate to the Directory**:
   ```bash
   cd password-complexity-checker
   ```
3. **Run the Application**:
   ```bash
   python password_checker.py
   ```

## Running Tests
Currently, no tests are implemented. Future enhancements can include unit tests for the password complexity function.

## Usage/Examples
Example passwords and their expected feedback:
- `Password123!`: Strong
- `pass123`: Medium
- `password`: Weak
## Sample Output
![Screenshot (130)](https://github.com/user-attachments/assets/36cad774-929b-43f5-9961-0d4e16b7ab06)
![Screenshot (129)](https://github.com/user-attachments/assets/65e9fe60-b244-4d86-81d6-87a985666b5a)
![Screenshot (128)](https://github.com/user-attachments/assets/e81039db-bf4e-4c57-af47-1c86aa1ae027)
![Screenshot (127)](https://github.com/user-attachments/assets/d9c0b733-be68-439a-8f85-e919513f9d65)

