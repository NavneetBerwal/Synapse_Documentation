
# **What is an API?**

API is acronym  for Application Programming Interface, which is a software intermediary that allows two applications to talk to each other.

In this project we are making an application using python that will help in fetching and testing APIs using various libraries of python.

# **SYNAPSE**

A search engine is a software system that is designed to carry out web searches. They search the web in a systematic way  for particular information specified in a textual web search query.

In this project we are going to build a search engine which can show us the search results it fetched from a few selected web sites.



# **APPROACH FOR BUILDING THE API TESTER:** 

An API tester is able to perform the following tasks for any given API:
- Creating the GUI
- Testing the API 
- Showing response 


### Creating the GUI:
The first step is to create a Graphic User Interface. It will allow the user to enter the API link and necessary params to be tested and also the output of the testing will be shown here.

### Testing the API:
Once we recieved the link through the GUI, the API link along with nessecary parameters, will be sent and test the API using *requests* library. 

### Showing Response:
As the name suggests, after the testing of the API, the outcome of the test is shown in the GUI created earlier.



# **LIBRARIES USED IN THE PROJECT**
- Tkinter
- Requests
- tkhtmlview
- BeautifulSoap4
- pywebcopy


##### You are welcome to use any other alternatives to the libraries mentioned above.





# **Python Installation guide**

## *For Windows* 

You have to do no more than download a file and run it . 
The python 3 version package can be downloaded from : 

[download](https://www.python.org/downloads/windows/)

Remember to select the add to path option to run it from any directory in your system.


## *For MacOS*

You can download the python 3 version package from : 

[download](https://www.python.org/downloads/macos/)

Run it to install python


## *For LinuxOS* 

Check if python is already installed:
  
```python
    python3 --version
```

If you get an output like:
```python
  Python 3.x.x
```
Skip the next part.
If you don't, follow the given commands.

### *Debian/Ubuntu*

```python
sudo apt-get update && sudo apt upgrade -y
sudo apt-get install software-properties-common
sudo apt install python3
```


### *Fedora/rpm based distros*

```python
sudo dnf install python3 python3-devel
```



# **Setting up a virtual environment**

Virtual Environment is an isolated space in the system where the user can install libraries and modules without disturbing the onces preinstalled in the system.

**For Windows**
```
pip install virtualenv
cd project_folder
virtualenv env
.\env\Scripts\activate
```

**For Linux**
```
pip install virtualenv #for version 2 and below 
pip3 install virtualenv #for version 3
cd project file
virtualenv env
source ./env/bin/activate
```

# Task

1. Install Python and setup Virtual Environment in your computer.
