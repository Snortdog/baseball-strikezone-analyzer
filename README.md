# Umpire Grader

This program analyzes raw Trackman CSV files and generates a PDF that visualizes the location of the pitches, the strike zone, and the percentage of correct calls made.



Prerequisites:

This program requires Python and a few Python libraries to run. If you don't have Python installed on your computer, you will need to install it. Follow these steps:

Download Python: Visit the official Python website at https://www.python.org/ and download the latest version of Python.

Install Python: Open the downloaded file and follow the installation instructions.

You will also need to install a few Python libraries: pandas, matplotlib, and tkinter. You can install these using pip, which is a package manager for Python. To install these libraries, open command prompt and type the following commands:

'pip install pandas'

'pip install matplotlib'

'pip install tkinter'




Running the Program:

Download the umpireGraderV3 file.

Extract the files to somewhere on your computer.

Open command prompt.

cd to the directory that contains uGraderV3.py (the easiest way to do this is to open the directory that contains the uGraderV3.py file, click on the dropdown menu above the file, copy the file location, type 'cd' into command prompt followed by a space, then paste the file location, then press 'Enter')

type 'py uGraderV3.py' to run the program

A box will open asking you to select a CSV file. Navigate to the location of the CSV file and select it. The CSV file should contain baseball pitch data with the following columns: 'PitchCall', 'PlateLocSide', 'PlateLocHeight'.
.
Wait for the program to process the data: The program will calculate the percentage of correct calls and create a PDF file with a scatter plot of the pitch locations.

View the PDF: After the program finishes running, a PDF file will be created in the same directory as the Python script. The PDF file will have the same name as the CSV file, but with a .pdf extension. Open this file to view the scatter plot of pitch locations and the percentage of correct calls.



Please note that this program does not normalize the strike zone for batter height, so the top and bottom of the strike zone will be the same for all hitters. This may cause the program's analysis to be inaccurate at times. 

