# Student ERP System
This is a Simple Student Management System developed using the concepts taught in class.


## Technologies Used
1. [Front-end Template](http://adminlte.io "Admin LTE.io")

2. [Python](https://www.python.org/ "Python")

3. [Django](https://www.djangoproject.com/ "Django")

3. [sqllite](https://www.sqlite.org/index.html "sqllite")

## Features of this Project

### A. Admin Users (HOD) Can
1. See Overall Summary Charts of Students Performances, Staff Performances, Courses, Subjects, Leave, etc.
2. Manage Staff (Add, Update and Delete)
3. Manage Students (Add, Update and Delete)
4. Manage Course (Add, Update and Delete)
5. Manage Subjects (Add, Update and Delete)
6. Manage Sessions (Add, Update and Delete)
7. View Student Attendance

### B. Staff/Teachers Can
1. See the Overall Summary Charts related to their students, their subjects, leave status, etc.
2. Take/Update Students Attendance
3. Add/Update Result

### C. Students Can
1. See the Overall Summary Charts related to their attendance, their subjects, leave status, etc.
2. View Attendance
3. View Result

---

## _How to Run this project_

### **Install Python** 3.6 or above

You can download **Python** from [*here*](https://www.python.org/downloads/ "Python Download").

Alternatively,
on Windows you can install python using the [*chocolatey*](https://chocolatey.org/ "chocolatey") package manager.

```
$ choco install python
```

### **(Optional)** Create Virtual Environment

1. Open a terminal **_in the project directory_**.
2. Run the following command to install virtualenv.
```
$ pip install virtualenv
```
3. Create a virtual environment.
```
$ virtualenv venv
```
4. Activate the virtual environment.
```
$ venv\Scripts\activate
```

### **Install Dependencies**

1. Open a terminal **_in the project directory_**.
   - **_(Optional)_** Activate the virtual environment using the command above.
2. Run the following command to install dependencies.
```
$ pip install -r requirements.txt
```

### **Run the Project**

1. Open a terminal **_in the project directory_**.
   - **_(Optional)_** Activate the virtual environment using the command above.
2. Run the following command to initialize the database.
```
$ python manage.py makemigrations
$ python manage.py migrate
```
3. Run the following command to create the static files.
```
$ python manage.py collectstatic
```
4. Initial Login Credentials
   - Create Super User (HOD) using the following command
   ```
   $  python manage.py createsuperuser
   ```
   - _**Note:**_ You can use *admin@admin.com* as email and *admin* as password for this.

   - Then Add Email and Password

   - Later, you can use the GUI to add more users.

5. Run the following command to run the project.
```
$ python manage.py runserver
```
6. Open the following link in your browser.

[http://127.0.0.1:8000/]()

_**Note:**_ You can use the images provided in the *Sample Profile Pics* folder as profile pictures.

---