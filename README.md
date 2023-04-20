# Create EXE 
Create exe from pyton file

## Description

this instructions allow you to create a exe file from a python file
note: make sure to change directory to where you want exe created

## Installation

### Step 1: Install PyInstaller

Open a command prompt or terminal window and run the following command to install PyInstaller using pip:
~~~bash
pip install PyInstaller
~~~

### Step 2: Create the .exe file

Save your Python script as `your_script_name.py`. Then, open a command prompt or terminal window and navigate to the directory where your Python script is located. Run the following command to create an executable from your Python script:

~~~bash
pyinstaller --onefile your_script_name.py
~~~

Replace `your_script_name.py` with the name of your Python script.

The `--onefile` option tells PyInstaller to create a single executable file instead of a directory with multiple files.

PyInstaller will create a standalone .exe file in the `dist` subdirectory within the directory where your Python script is located. The name of the .exe file will be the same as your Python script name.

## Usage

[Provide instructions on how to use your script, including any command-line arguments, input/output formats, or other requirements]

## License

[Include license information for your script, if applicable]

## Credits

[Give credit to any external libraries, resources, or individuals whose work you have used or referenced in your script]

## Contact Information

[Provide your contact information or ways to reach you for questions, feedback, or support]
