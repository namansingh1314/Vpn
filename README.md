# VPN Connection GUI

## Overview
This project provides a simple graphical user interface (GUI) for connecting to a VPN using Python and Tkinter. The GUI prompts the user for a server address, username, and password, and simulates a VPN connection.

## Features
- Input fields for server address, username, and password.
- Connect button to simulate connecting to a VPN.
- Informational and error message boxes to guide the user.

## Requirements
- Python 3.x
- Tkinter library (usually comes pre-installed with Python)

## Installation and Usage

### Step 1: Download the Project
1. Go to the GitHub repository hosting the project.
2. Click on the "Code" button.
3. Select "Download ZIP" to download the project files.

### Step 2: Extract the ZIP File
1. Locate the downloaded ZIP file on your computer.
2. Right-click the ZIP file and select "Extract All..." or use your preferred extraction tool to unzip the file.
3. Extract the contents to a directory of your choice.

### Step 3: Run the Application
1. Open a terminal or command prompt.
2. Navigate to the directory where you extracted the ZIP file.
3. Ensure you have Python installed by running:
    ```bash
    python --version
    ```
4. If Python is not installed, download and install it from [python.org](https://www.python.org/).
5. Run the script by executing:
    ```bash
    python vpn_connect.py
    ```
   Replace `vpn_connect.py` with the name of the Python script file if it is different.

### Step 4: Using the Application
1. A window will appear with fields for the server address, username, and password.
2. Enter the appropriate information in each field.
3. Click the "Connect" button to simulate connecting to a VPN.
4. If all fields are filled, an informational message box will display "Connected to VPN Server".
5. If any field is empty, an error message box will display "Please fill in all the fields".

## Code Explanation
The code for the application is structured as follows:

1. **Importing Modules**:
    - `tkinter` for the GUI components.
    - `messagebox` for displaying messages to the user.

2. **Defining the Connect Function**:
    - Retrieves input from the user.
    - Validates the input and displays corresponding messages.

3. **Creating the Main Window**:
    - Initializes the main Tkinter window.
    - Sets the window title.

4. **Adding Labels and Entry Fields**:
    - Creates and packs labels and entry fields for server address, username, and password.

5. **Adding the Connect Button**:
    - Creates and packs the connect button.
    - Binds the button to the `connect_to_vpn` function.

6. **Running the Main Loop**:
    - Starts the Tkinter event loop.

## Troubleshooting
- Ensure Python is installed and added to your system's PATH.
- Verify you are in the correct directory where the script is located.
- Check for any typos in the script filename or the commands you are executing.

## Contributing
Feel free to fork the project and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.
