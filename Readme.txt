Hi today im disscussing about How to integrate Python Script in Uipath Tool and 
How to run it...

step 1
	we must install the Uipath studio 
	and need to download the package Uipath.python.Activites package
	need to have python script 
	i just have simple python Script to get the file size of the file.

Let's get started.

this is the packge we should installed in our Uipath Studio.


Create a new Sequence .
now open the activities pane and search for the python

we need to starts from the Pyhton Scope 

we need to give the path and select version of the Python which is installed in our machine

i will install my python in locally so we need to give the path in the path 
or else we can create a varible and store the path of the python.
i have installed 32 bit so i will sellect the 32 bit option and version 36

python path successfully done 

now we need to load the python script in it.
it will ask you the path of the python sript.
you can directly search by click here 
myt script was loaded successfully.
lets see muy Script.
what i have given the instruction 


i just want to print the size of a file.

here we need to create a variable to load the python script content in it.

now we need to invoke the python method to get python object from the python Script.

it has instance = python object, 
input perameters = file location, 
name = function name
result = .net object.

so need to give the instance is python object

and the object name is getFileSize

input perameter is file location what file do you want to get the file size.



this is the file location i will give the input perameter.

here we are sending the object formate of input perameters so we need to keep the path inside of the {""}


it will return an python object so we need to convert it to .net object
now inseart get python object.

now inseart the log message to display the information which is loaded to the object.



now display the pop up with result

now run the task


Thank you watching

all the best for your happy automation...............!



