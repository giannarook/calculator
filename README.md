# Calculator

A Python 3 calculator used from the Terminal, built step by step in SCCM4910.

## What it will do
Add, subtract, multiply and divide two numbers; display the result.
## How to run it

Run: python3 calculator.py
or ./run.sh in the calculator directory, or ~/h-drive/calculator/run.sh
in any other folder

Enter the first number, operator (+ - * /), then second number.
The program prints Result: followed by the answer.

## How to test it

By activating the SCCM4910 virtual environment, you are able to run the
./check.sh script to check whether the calculator meets a set of 5 requirements
for each operation

Run in terminal:
source /opt/python-venv/sccm-4910/bin/activate
./check.sh and echo $? immediately after running!! to check the exit status (0 if it succeeded, 1 if 
tests failed, 5 if no tests are collected)
