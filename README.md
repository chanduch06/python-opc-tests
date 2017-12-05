OPC Test

Implementation of Application that reads from OPC Interface. 

create the virtual environment

$ virtualenv venv && source venv/bin/activate

Install the required dependencies

$ pip install -r requirements.txt


Run tests

In examples folder start running

$ python server-example.py


$ python client-example.py


Project Structure
API offers both a low level interface to send and receive all UA defined structures
and high level classes allowing to write a server or a client in a few lines.
It is easy to mix high level objects and low level UA calls in one application.

The general structure is referred from:
https://github.com/FreeOpcUa/python-opcua
