# CodingEditor
# Python Code Editor with Terminal Integration

This project provides a Python code editor running in the browser with an integrated terminal to run Python code. The editor uses Monaco Editor for code editing and Pyodide to run Python code directly in the browser without the need for a server. The terminal displays the output of the Python code, including custom print statements and handling for user input via `input()`.

## Features
- **Python Code Execution**: Run Python code directly in the browser using Pyodide.
- **Monaco Editor**: A fast and feature-rich code editor with syntax highlighting for Python.
- **Input Handling**: Dynamic input fields generated from `input()` calls in the code, with user validation.
- **Error Handling**: Displays error messages in the terminal if inputs are missing, with validation split into two lines for clarity.
- **Terminal Output**: Custom terminal to show Python program output and errors.

## Demo
You can try out the editor and run Python code directly from the browser. Check out the live demo at:  
[**Live Demo URL**](https://your-hosted-url-here.com)

## Getting Started

### Prerequisites
To run this project locally, you need a modern web browser that supports JavaScript. No server-side setup is required because everything runs directly in the browser.

### Installation

1. Clone this repository or download the files to your local machine.
2.*Open the index.html file in your preferred browser.

open index.html

This will launch the Python editor in your browser.

###Usage
1. Write Python Code:
You can write Python code inside the Monaco editor. For example:

name = input("Enter your name: ")
print("Hello, " + name)

2. Input Fields:
Based on the input() calls in your code, corresponding input fields will appear below the editor. Enter the required input for each field.

3. Run Code:
After writing your code and providing the necessary inputs, click the Run Code button to execute your Python program.

4. See Output:
The terminal below the code editor will display the output or any error messages. If you leave an input field blank, you will see a validation error with the missing input prompts displayed on two lines for better clarity.

###How It Works
1. Monaco Editor: The code editor uses Monaco Editor, which provides a rich, fast, and customizable code editing environment with syntax highlighting for Python.

2. Pyodide: Pyodide is used to run Python code directly in the browser. It is a WebAssembly port of CPython and allows running Python code in the browser without needing a server-side interpreter.

3. Input Field Detection: The code editor scans for Python input() function calls in the code and dynamically generates input fields for each input() prompt. These fields are labeled based on the prompt text inside the input() calls.

4. Custom Print Function: The standard Python print() function is replaced with a custom function that captures the output and displays it in the terminal.

5. User Input Validation: If an input field is left empty, the terminal shows an error message indicating which input is missing, with the message split across two lines for better readability.

###Contributing
1. Fork the repository.

2. Create a new branch (git checkout -b feature-name).

3. Make your changes and commit them (git commit -am 'Add new feature').

4. Push to the branch (git push origin feature-name).

5. Create a new Pull Request.

###License
This project is licensed under the MIT License - see the LICENSE file for details.

###Acknowledgements
- Monaco Editor: A fast, lightweight code editor developed by Microsoft.

- Pyodide: A Python interpreter compiled to WebAssembly, enabling Python code to run in the browser.

- Open Source Libraries: Various libraries like Monaco Editor, Pyodide, and others are used in this project to provide a seamless code editing and execution experience.


### Key Sections:
- **Project Overview**: This section provides a summary of the project's functionality and key features.
- **Demo**: Link to a live demo of the application.
- **Getting Started**: Step-by-step instructions for setting up the project locally.
- **Usage**: Explains how to use the editor, run Python code, provide input, and see the output.
- **How It Works**: A breakdown of how Monaco Editor, Pyodide, input handling, and validation are integrated into the project.
- **Contributing**: Instructions on how others can contribute to the project.
- **License**: Information about the project's licensing.

---

 
