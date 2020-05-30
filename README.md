# Letzzstudy

APP NOTIFICATION SYSTEM

Introduction:
        To gain access to multiple courses and enrich their knowledge in those. The notification model will notify the client when a new course is added, when they read the course and to differentiate the list of  unread courses and inform them.
       
Pre-Requisites:  
	Visual Studio, MS Access.
Software used for testing:
	 Visual Studio 2012, Microsoft Office Access 2007, Internet Explorer.
Folder Structure: 
1. Database File: Notification_System\Notification_System\App_Data\NotificationSystem.accdb
Flow:
 1. Admin->Add courses, View courses, Update courses.
 2. User->View courses, Change Password, See Notifications, Read Course.
Steps:
1. To execute application, click Notification_System\Notification_System.sln
2.  In the Solution Explorer, under the Notification_System click on Web.config file and execute this file using Internet Explorer option which is available in Taskbar.

System we have prepared, consist of 2 types of user. 
1.	Admin
2.	User
User Capability:

1.	Admin: 
•	Can add a new course in the course list along with details about the course and a reference link to understand the concept deeper. 
•	Can update course details, when we furnish our site with more concepts regarding the course.
•	Can view the existing courses, to check if any details provided, requires additional data to be furnished without procrastination, so that we can avoid bad user experience because of outdated data.

2.	User: 
•	View list of available courses to check which courses suits their need and they wish to browse the content.
•	User can change the password of their login. This is to provide better user experience.
•	Will have a capability to see newly added courses in a notification list and click on them to navigate to the course content table.
•	Will have a provision to check which all notifications have been read and which are not, using lavender and green colour differentiation.(Among which, lavender is for the read notifications and green for the unread notifications.

Home Page:
	Home page will have 3 tabs through which we can either "Contact" , "Register" or "Login" .

Register Page:
	In this page, User will have facility to create a new account of his or her choice  with following details, among which they will use email id and password for login purpose.

	Name: 		Student Name
	Password: 		Should be at least 8 characters
	Confirm Password: Should be same as password.
	Phone Number: 	Should have 10 digits
	Email ID: 		Should be proper account
	College: 		No Validation

Clicking on submit button after providing the required details will provide the user with a popup stating "Registered Successfully". If the above details are not proper it will not allow you to register. After registering, it will display 

Admin Login:
In order to login as Admin, we have to use below credentials, to have admin specific capabilities.
	Username: admin
	Password: admin@123

After adding the new course details, it will display message in a popup stating "Added Successfully.
Similarly updating the course details will result in a popup stating "Updated Successfully".

User Login:
	User can view the courses that are uploaded by the admin by clicking "View Courses" tab and they can change the password by clicking "Change Password" tab correspondingly.

Notification:
After logging in, User can see bell icon at the top right corner of the page.
If the user completed all the courses and does not have any notification, the bell icon will be shown without a dot.   .
If the user has some notifications, the bell icon will be shown with a dot.
After clicking this icon, list of courses will be displayed.
Once the user click any of the courses it will move on to the "View Courses" page.
From there, by clicking any of the courses, it will display the content of the courses.
After completing the course, User have a option to click "Submit" button.
Once the "Submit" button is clicked, pop up will be disabled and will display "Courses Submitted Successfully".
Once the user click the bell icon with a dot, which informs the user that they have some unread notifications which will be shown in Green colour.
The read notification will be displayed in lavender for differentiation.
