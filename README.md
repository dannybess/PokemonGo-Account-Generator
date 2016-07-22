# Pokemon Trainer Account Mass Account Generator 

## Installation Instructions
1. Install virtualenv (if you do not yet have it).
```
pip install virtualenv
```
2. Setup a working directory.
```
mkdir account_generator
```
3. Setup and activate your virtual environment. 
```
virtualenv venv
source venv/bin/activate
```
or if you want to use a specific version of python, 
```
virtualenv -p /usr/bin/python2.7 venv
source venv/bin/activate
```
4. Install dependencies.
```
pip install selenium
```
5. Create an output file, named accounts.txt in /account_generator.
6. Run the script!

NOTE: When the script runs, a Firefox window will popup. Expand the window to make sure the script functions properly. (Otherwise, you will end up with an error along the lines of: 
```
Element is not clickable at point (..., ...)
```

