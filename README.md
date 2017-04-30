# bash-diff-testing
A bash shell script that compares the output of a program to a specified _"expected-output"_ file.  

## Usage
This script was put together in a few minutes for a Computer Science course at my university so don't
expect it to be very sophisticated (yet).  

The script loops through every directory in its working dir. All those directories need to contain are:
* **in**
  This is the input file which specifies what kind of userinput should be emulated.__
* **out**
  This is the file with the expected output written down.__

Then simply run the script from within the folder containing all your subfolders/testcases. The executable needs to be named **"d3"**.
