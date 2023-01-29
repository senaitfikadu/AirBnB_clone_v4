0x06. AirBnB clone - Web dynamic

Learning Objectives

At the end of this project, you are expected to be able to explain to anyone, without the help of Google:
General

    How cool it is to request your own API
    How to modify an HTML element style
    How to get and update an HTML element content
    How to modify the DOM
    How to make a GET request with JQuery Ajax
    How to make a POST request with JQuery Ajax
    How to listen/bind to DOM events
    How to listen/bind to user events

Before starting the project…

You will work on a codebase using Flasgger, you will need to install it locally first before starting the RestAPI:

$ sudo apt-get install -y python3-lxml
$ sudo pip3 install flask_cors # if it was not installed yet
$ sudo pip3 install flasgger

If the RestAPI is not starting, please read the error message. Based on the(ses) error message(s), you will have to troubleshoot potential dependencies issues.

Here some solutions:
jsonschema exception

$ sudo pip3 uninstall -y jsonschema
$ sudo pip3 install jsonschema==3.0.1

No module named 'pathlib2'

$ sudo pip3 install pathlib2
