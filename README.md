# Umpire Grader
Analyzes Trackman Baseball postgame reports and delivers an analysis of how well the umpire did.

This program analyzes a CSV file containing data of baseball pitches and generates a PDF that visualizes the location of the pitches, the strike zone, and the percentage of correct calls made.

Prerequisites
This program requires Python and a few Python libraries to run. If you don't have Python installed on your computer, you will need to install it. Follow these steps:

Download Python: Visit the official Python website at https://www.python.org/ and download the latest version of Python.

Install Python: Open the downloaded file and follow the installation instructions.

You will also need to install a few Python libraries: pandas, matplotlib, and tkinter. You can install these using pip, which is a package manager for Python. To install these libraries, open a terminal or command prompt and type the following commands:

shell
Copy code
pip install pandas
pip install matplotlib
pip install tkinter
Running the Program
Download the Python script: Save the Python script to a location on your computer.

Run the Python script: Open a terminal or command prompt, navigate to the directory where you saved the Python script, and run the following command:

shell
Copy code
python script_name.py
Replace "script_name.py" with the name of the Python script.

Select a CSV file: A dialog box will open asking you to select a CSV file. Navigate to the location of the CSV file and select it. The CSV file should contain baseball pitch data with the following columns: 'PitchCall', 'PlateLocSide', 'PlateLocHeight'.

Wait for the program to process the data: The program will calculate the percentage of correct calls and create a PDF file with a scatter plot of the pitch locations.

View the PDF: After the program finishes running, a PDF file will be created in the same directory as the Python script. The PDF file will have the same name as the CSV file, but with a .pdf extension. Open this file to view the scatter plot of pitch locations and the percentage of correct calls.

Please note that this program assumes the strike zone to be a rectangle with the left edge at -0.827, right edge at 0.827, bottom at 1.5, and top at 3.2.

