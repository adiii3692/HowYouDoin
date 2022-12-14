# HowYouDoin

## Tech Used:
1. Python(Flask)
1. HTML
1. CSS
1. SQLITE

## Description:
This project is a simple hospital management system inspired by the famous fictional character Dr.Drake Ramoray ;) The user can log in as either a doctor, a patient or an admin, with each having different features.

### Patient Features:
* A patient can login if they are registered, or else create an account by registering.
* After logging in, the patient can book an appointment with a specific doctor at a specific date and time
* The patient can also view their appointment history

### Doctor Features:
* A doctor can login using the email id and password they registered with. The registration can however only be done by the admin
* After logging in, the doctor can view their appointments

### Admin Features:
* The admin can view the list of registered patients
* The admin can view the list of registred doctors
* The admin can view the list of all appointments
* The admin can also register a new doctor using the details the doctor provides them with
```
admin username: admin
```
```
admin password: admin123
```

## How to install?
* It is recommended to open all the files in a code editor such as VS Code or Sublime Text
* Before running a server, the user needs to install the necessary libraries
* If not already downloaded, the user needs to ensure they have downloaded the latest version of [Python](https://www.python.org/downloads/).
* After downloading Python and the necessary code editor, the user needs to open the Terminal on their device
* Upon opening their Terminal the user needs to type in the following commands in order to install the necessary libraries:

```
pip3 install cs50
```
```
pip3 install Jinja2
```
```
pip3 install Flask
```
```
pip3 install Flask_session
```
```
pip3 install Werkzeug
```
* After installing the necessary libraries, the user needs to go back to the code editor and open the terminal in the directory in which the files are located. After starting the terminal the user needs to type in the following command to start a server and click on the link which will be provided:

```
flask run
```
## Main Files
1. app.py: Python file that utilises flask library to run the backend
1. patients.db: SQLITE database that stores the deatails of the patients, doctors and appointments made
1. helpers.py: Python file that contains helpful functions 

## Credits
* The icon was taken from [favicon](https://favicon.io/)
* The gif used in the index has been taken from [gyfcat](https://gfycat.com/)


