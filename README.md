# SDU portal
A portal management system built using Django framework. It is designed for interactions between students and teachers. Features include attendance, marks and time table. The project was supposed to be with PL/SQL, so I firstly do with MySQL. 

## Installation

Python and Django need to be installed

```bash
pip install django
```

## Usage

Go to the College-ERP folder and run

```bash
python manage.py runserver
```

Then go to the browser and enter the url **http://127.0.0.1:8000/**


## Login

The login page is common for students and teachers.  
The username is their name and password for everyone is 'project123'.  

Example usernames:  
student- 'samarth'  
teacher- 'trisila'  

You can access the django admin page at **http://127.0.0.1:8000/admin** and login with username 'admin' and the above password.

Also a new admin user can be created using

```bash
python manage.py createsuperuser
```

## Users

New students and teachers can be added through the admin page. A new user needs to be created for each. 

The admin page is used to modify all tables such as Students, Teachers, Departments, Courses, Classes etc.

**For more details regarding the system and features please refer the reports included.**

## Update (29/11/2020)

Added method to reset attendance time range in Django Admin page.

![alt_text](https://i.imgur.com/0xOWmUZ.png)

This is present in Django Admin -> Attendance (http://127.0.0.1:8000/admin/info/attendanceclass/).  
Start Date: Start Date of Attendance period  
End Date: End Date of Attendance period

This will delete all present attendance data and create new attendance objects for the given time range. 

## Screenshots

### Teacher Page

<img width="1440" alt="Screen Shot 2022-05-23 at 17 34 44" src="https://user-images.githubusercontent.com/91027496/169810596-24125fc5-972f-42ec-b613-2c8ccfdc8a64.png">

<img width="1440" alt="Screen Shot 2022-05-23 at 17 35 52" src="https://user-images.githubusercontent.com/91027496/169810786-9c9e63b3-771b-4902-8358-bd2fc48388ce.png">


<img width="1440" alt="Screen Shot 2022-05-23 at 17 36 35" src="https://user-images.githubusercontent.com/91027496/169810927-db018263-c968-4965-9656-3f006f3e1620.png">


<img width="1440" alt="Screen Shot 2022-05-23 at 17 37 14" src="https://user-images.githubusercontent.com/91027496/169811050-752f4105-24ae-47fe-803e-a86db0b2d15e.png">


<img width="1440" alt="Screen Shot 2022-05-23 at 17 37 43" src="https://user-images.githubusercontent.com/91027496/169811139-f06b6ead-48bc-4ae6-9f5b-bbb7fa21d8e3.png">


<img width="1440" alt="Screen Shot 2022-05-23 at 17 38 15" src="https://user-images.githubusercontent.com/91027496/169811236-e978a313-6986-477d-baec-be05333e3c1e.png">


<img width="1440" alt="Screen Shot 2022-05-23 at 17 38 41" src="https://user-images.githubusercontent.com/91027496/169811296-bb4c9355-d84e-4e22-a27c-7b6721894ce1.png">


### Student Page

![alt text](https://imgur.com/isL9cjz.png)

![alt text](https://imgur.com/5pzl7m3.png)

![alt text](https://imgur.com/7zWhHZx.png)

![alt text](https://imgur.com/fu7gxk8.png)

![alt text](https://imgur.com/NZqU268.png)

### Admin Page

![alt text](https://imgur.com/sDvDc9N.png)

![alt text](https://imgur.com/tMKWx6f.png)

![alt text](https://imgur.com/PvCsNeB.png)
