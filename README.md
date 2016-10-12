# passgen
A simple program written in Python to generate a cryptographically secure password

Passgen is a Python script that uses the os.urandom Python function to generate a password, which is then printed to your terminal.

Dependencies
Passgen uses the following standard Python libraries.
os, which includes the os.urandom function
sys, to write the generated password to the terminal
random, for other functions that deal with pseudo-random numbers generations.
All three dependencies are standard Python libraries, so there's no need to install additional dependencies.

Installation
Linux
Download the file "passgen" to your computer.

Run the command
sudo mv /PATH/TO/THE/FILE/passgen /usr/bin/passgen
This will allow you to run it as you would normally run any command-line program

Run the command
sudo chmod +x /usr/bin/passgen

You can then run the program by typing passgen in your terminal

OS X

Download the file "passgen" to your computer.
Run the command
sudo chmod +x /PATH/TO/THE/FILE/passgen
