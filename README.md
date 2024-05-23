This project contains test cases written in Robot Framework that interact with a RESTful API. The tests use the RequestsLibrary to send HTTP requests and verify the responses.

Installation
Prerequisites
Python 3.7+
pip (Python package installer)
Visual Studio Code 1.89.1
Setup
Clone the repository:


--git clone <repository_url>
--cd <repository_directory>
Create a virtual environment (optional but recommended):


--python -m venv venv
--source venv/bin/activate   # On Windows use `venv\Scripts\activate`
Install the required libraries:


--pip install robotframework
--pip install robotframework-requests
Install additional libraries:


--pip install robotframework-collections
--pip install robotframework-string
Open the project in Visual Studio Code:



VS Code Extensions
For an enhanced development experience, install the following extensions in Visual Studio Code:


Running Tests
To run the Robot Framework tests, use the following command in the terminal:
--robot <path_to_your_test_file>
For example:
--robot tests/api_tests.robot
You can also run the tests directly from Visual Studio Code:

Open the test file (e.g., api_tests.robot).
Use the command palette (Ctrl+Shift+P or Cmd+Shift+P on macOS) and type Run Robot Framework Test Cases.
Select the test cases or suite you want to run.
