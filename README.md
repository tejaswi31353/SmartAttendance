# SmartAttendance
## Application Name: SAMS(Smart Attendance Management System)

---
## Team Members: &nbsp;
Manikanta Vasana <br>
Tejaswi Gannamaneni <br>
Shiva Krishna Myakala <br>
Jahnavi Dammannagari <br>

---
## Problem Statement:
Now, the attendance system being used in most of the universities is either the excel sheet or written on a piece of a paper. For classes, the graduate assistant must check all the class to take note of the attendance and there might be a chance of loss of data, it is a time taking process and is prone to human errors, hence recording incorrect data.

---
## Introduction:
The main objective of this application is to Automate the traditional way of recording attendance and provide an innovative and efficient way to visualize the attendance. A better way to store and retrieve attendance records. Drastically decrease the time taken to take attendance in class, thereby increasing the productivity in class.

---

## Activities:
Login page: Generic login page for Student and Professor.

### Professor Dashboard:
* Professor Class list.
* Processor Class-wise attendance list.
* Professor Student-wise attendance list for a particluar class.
* Generate class-wise bar code for scanning.
* Settings -> Logout, Edit profile.

### Student Dashboard:
* Student class list.
* Representation of attendance in the form of Pie Chart.
* Select class -> Scan Professor Barcode page.
* Student Class wise Attendance progress.
* Settings -> Logout, Edit profile.

---
### Advantages:
1. User-Friendly, <br>
2. Easy Attendance Reporting,
3. Reduced Paperwork, <br>
4. One-Stop Attendance Solution. <br>

---
## API/Libraries used

### API:
- Google Vision API

### Libraries:
- Butter Knife
- Multidex
- Glide
- CircleImageView
- Timber
- Zxing
- MPAndroidCharts
- Retrofit
- Gson

---
## App Usage Guidelines
#### **Professor**
- Login with the test credentials.
- Once the dashborad is opened, you'll see the list of actions.
- List of the classes professor teaches.
- Able to check the attendance.
- Generate Barcode for particular class.
- Settings where you are able to update contact, Status and Logout.

Note: Generate BarCode only once per a day for each class. 

#### **Student**
- Login with the test credentials.
- Once the dashborad is opened, you'll see the list of actions.
- will be able to view the list of classes registerd for semester.
- will be able to check the attendance in the form of pie chart.
- will be able to scan the barcode which is genrated by the professor.
- Settings where you are able to update contact, Status and Logout.

---
### Test Credentials:
**Professor:** <br>
User ID: professor <br>
Password: 123456 <br>

**Student:** <br>
User ID: student <br>
Password: 123456 <br>

---
## Supported Devices
MinSdk 21 <br>
targetSdk 32 <br>
Version "1.0" <br>

---
## Technical Stack:
**Android:** Java, Xml. <br>
**Server:** Heroku <br>
**Backend:** Nodejs with MongoDB. <br>

---
## Important Links:
[Icons](https://icons8.com/ "Icons8") <br>
[Heroku](https://samsandroid.herokuapp.com/ "Server Link") <br>
[NodeJs](https://github.com/uma0441/samsandroid.git "NodeJS for SAMS")



