# Bus-Ticket-Vending-Machine
Backend of the Bus Ticket Vending Machine in NISER

## Virtual Environment

### Setting up a virtual environment
Set up a virtual environment so that you don't have to install every package in your local system. 
You may use the command `python3 -m venv .venv` to create a virtual environment in the directory `.venv`. Then to activate the vitual environment, use the following command in Terminal 
- `source .venv/bin/activate` in Mac and Linux
- `./.venv/bin/activate` in  Windows
A list of librariess required for the app will be maintained in `requirements.txt`. 
Use the command `pip3 install -r requirements.txt` to install all those in your virtual environment.

## Adding more files to requirements.txt
Whenever you install a package required for the file, add it into the requirements file using the command
`pip freeze > requirements.txt`. Make sure that you already have all the existing packages in requirements installed.