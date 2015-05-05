# Utility-Functions-Modelling
Contains complex functions that may be referenced in other ipython notebooks

This repository contains a number of ipython notebook files (.ipynb) each containing a single cell with a number of functions defined in each.  The work flow for using these functions is as follows:
- Clone this repository to your computer
- Open the notebook containing the functions you want to use
- Edit the first line in the note book so the write file expression points to the location of library dirrectory of your anaconda instilation
- For me the first line looks like this
-%%writefile C:\Anaconda\Lib\ETFunctions.py
- Runing this cell will create a ETFunctions.py file in the right place for it to be referenced by other Ipython notebooks
- In the note book where you want to uses these functions load them as
-import ETFunctions
- Then call them as:
-ETFunctions.PenmanEO()
- Tab completion will bring up all the functions available in that library
- Shift+Tab to the right of the first bracket in the function brings up the arguments the function needs

To edit the ocntent of these functions:
- Simply change the content of the cell in the note book, either fixing errors in functions or adding new ones.
- When the changes are complete run the script to update the .py file in the library.
- Close ipython notebooks and reopen for the changes to take effect in your notebooks.
- Push any changes into the master repo so they are available to all
