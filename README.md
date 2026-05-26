  WasteWise Installation Guide
1. Introduction
The WasteWise System is a waste collection monitoring and management platform designed for Ormoc City. The system is accessible through both web and mobile platforms to support System Administrators, ENRO Staff, Garbage Collectors, Barangay Officials, and Residents.

The system consists of:
 A Web Application hosted on Vercel
A Backend Server hosted on Render
A Mobile Application developed using React Native
 Real-time communication using WebSocket technology
The deployment setup allows users to access operational dashboards, truck tracking, route monitoring, notifications, and reporting tools using desktop computers and Android mobile devices.
2. System Requirements
 2.1 Web Application Requirements
Recommended browsers:
Google Chrome (Latest Version)
 Microsoft Edge
Minimum Requirements:
 Stable internet connection
 Desktop or laptop computer
 Updated web browser
 2.2 Mobile Application Requirements
Supported Platform:
Android Devices
Minimum Requirements:
Android Version 8.0 and above
 At least 3 GB RAM
- 200 MB free storage space
*Stable internet connection
3. WasteWise Web Application Access
The WasteWise Web Application is used by:

System Administrators
ENRO Staff
Barangay Officials

Web Application URL
Access the system using the following link:
https://waste-wise-ormoc-ddm.vercel.app/
Steps to Access the Web Application

1. Open a web browser.
2. Enter the official WasteWise URL.
3. Wait for the login page to load.
4. Enter your registered Email and Password.
5. Enter the One-Time Password (OTP) sent to your email.
6. Click Verify to access the system dashboard.

4. Backend Server Deployment Information
The WasteWise backend server is deployed using Render.
The backend server handles the following:
API requests
Database connections
Real-time WebSocket communication
Authentication and OTP verification
Data synchronization
Complaint and report management
Purpose of the Backend Server:
The backend server ensures smooth communication between the web application and mobile application. It enables real-time updates for truck tracking, route completion, attendance monitoring, and report notifications.

5. WasteWise Mobile Application Installation
The WasteWise Mobile Application is designed for:
Garbage Collectors
Residents
The application is distributed as an APK file for Android devices.
6. Downloading the APK File
The WasteWise APK file can be downloaded through:
Direct APK distribution
Google Drive link: https://drive.google.com/drive/folders/1_revsnfxy2QukNsfrXYOmoXKTEomaCwb?usp=sharing

Steps to Download the APK
1. Open the provided Google Drive link.
2. Locate the latest WasteWise APK file.
3. Tap Download.
4. Wait for the download process to complete.

Note:
Depending on your device settings, Android may display a warning before downloading APK files from external sources.

7. Enabling Installation from Unknown Sources
Because the application is installed outside the Google Play Store, Android devices may require permission to install applications from unknown sources.

Steps to Enable Installation Permission
1. Open your Android device Settings.
2. Navigate to:
   Security → Install Unknown Apps.
3. Select the browser or file manager used to download the APK.
4. Enable:
   Allow from this source
5. Return to the downloaded APK file.

8. Installing the WasteWise Mobile Application
Step-by-Step Installation
1. Open the Downloads folder or File Manager.
2. Locate the WasteWise APK file.
3. Tap the APK file.
4. Tap Install.
5. Wait for the installation process to complete.
6. Tap Open to launch the application.

System Result:
The WasteWise mobile application is successfully installed on the Android device.

9. Logging In to the Mobile Application
Garbage Collector Login
1. Open the WasteWise mobile application.
2. Enter your Email and Password.
3. Tap Login.
4. Check your email for the OTP.
5. Enter the OTP.
6. Tap Verify OTP.
Resident Access
Residents can access the tracking and reporting features directly through the mobile application.
Features Available:
Track garbage trucks
View collection logs
Submit complaints
Monitor schedules and routes
10. Updating the Mobile Application
To update the WasteWise mobile application:
1. Download the latest APK version from the provided Google Drive link.
2. Open the updated APK file.
3. Tap Install.
4. The system will automatically replace the older version while keeping user data intact.
Note:
Users are advised to install the latest version to receive new features, bug fixes, and security improvements.

11. Troubleshooting Guide

Problem: Cannot Access the Website
Possible Causes:
No internet connection
Incorrect URL
Server maintenance

Solutions:
Check internet connectivity
Re-enter the official URL
Contact the system administrator

Problem: OTP Not Received
Possible Causes:
Incorrect email address
Delayed email delivery
Poor internet connection
Solutions:
Verify the registered email address
Check Spam or Junk folders
Request a new OTP

 Problem: APK Installation Blocked
Possible Causes:
Unknown Sources permission disabled
Solutions:
Enable installation from unknown sources in Android settings

Problem: Application Not Opening
Possible Causes:
Unsupported Android version
Corrupted APK file
Solutions:
Re-download the APK file
Update Android software if possible
Restart the device and try again
12. Security Reminders
To ensure account security:
Do not share your password or OTP.
Always log out after using the system.
Install only official APK files provided by authorized personnel.
Regularly update the application.


 WasteWise User Manual
Monitor. Manage. Maintain.
From Collection to Operation.
Together, we track, act, and help keep Ormoc City clean.

    ══════ACCESSING THE WASTEWISE SYSTEM (WEB APPLICATION)══════
The WasteWise Web Application is used by System Administrators and ENRO Staff to manage waste collection operations.
Available Actions on the Login Page
Login – Access the system using your credentials
Request Account Access – For eligible users only
Forgot Password – Reset a forgotten password
1. Request Account Access (ENRO Staff and Barangay Officials Only)
Button Used: Request Account Access
Step-by-Step Instructions:
Open the WasteWise login page.
Click the Request Account Access button.
Enter the following details:
Full Name
Gender
Mobile Number
Email Address
Role(s)
Click Submit Request.
System Action:
The request is sent to the System Administrator for review.
If Approved:
Open your email.
Read the approval notification.
Return to the login page.
Enter your Email and Password.
Enter the OTP sent to your email.
Click Verify to access the system.

══════ FORGOT PASSWORD (WEB APPLICATION) ══════
3. Button Used: Forgot Password
Step-by-Step Instructions:
On the login page, click Forgot Password.
Enter your registered email address.
Click Send Code.
Check your email for the OTP.
Enter the OTP in the system.
Create a new password.
Click Save Password.
Click Login to access your account.
4. Mobile Application Access Overview
The WasteWise Mobile Application supports two user types:
Garbage Collector
Resident
Each user has different buttons, pages, and actions.

══════ GARBAGE COLLECTOR USER MANUAL (MOBILE APP) ══════
4.1 Login (Garbage Collector)
Buttons Used: Login, Verify OTP
Step-by-Step Instructions:
Open the WasteWise mobile app.
Enter your Email and Password.
Tap Login.
Check your email for the OTP.
Enter the OTP.
Tap Verify OTP to proceed.
4.2 Dashboard
The dashboard displays your daily work overview.
4.3 Attendance Page (Before Starting Collection)
Buttons Used: Clock In, Clock Out
Step-by-Step Instructions:
Open the Attendance Page.
Tap Clock In to start your shift.
Confirm the action when prompted.
System Result:
Status changes to On Duty.
The button changes to Clock Out.
ENRO Staff and Residents can now see that collection has started.
4.4 Schedule Page
Button Used: View Schedule
Step-by-Step Instructions:
Tap the Schedule Page.
View your assigned route for the day.
Scroll to see upcoming schedules.
4.5 Route Page
Buttons Used: Map View, Check
Step-by-Step Instructions:
Open the Route Page.
View the highlighted route line on the map.
Follow the route from Start Point to End Point.
When a collection point is completed, tap Check.
System Result:
Status changes from Pending to Completed.
Updates are reflected in real time across all systems.
4.6 Report Page (Garbage Collector)
Buttons Used: Report, Submit Report
Step-by-Step Instructions:
Open the Report Page.
Tap Report.
Select a Report Type:
Vehicle Issue
Equipment Problem
Route Issue
Safety Incident
Select the Specific Issue.
Enter notes or remarks.
Tap Submit Report.
System Result:
ENRO Staff are automatically notified.
4.7 Settings Page
Buttons Used: Edit Profile, Login History
Available Actions:
Update personal information
View login activity (device, time, status)

══════ RESIDENT USER MANUAL (MOBILE APP) ══════
5.1 Track Page
Buttons Used: Search, Filter
Step-by-Step Instructions:
Open the WasteWise mobile app.
The Track Page opens by default.
Tap Search to enter:
Truck ID
Route Name
Barangay
Tap Filter to select:
Truck Status
Garbage Type
Schedule Day
Apply filters to update the map view.
5.2 Logs Page
Buttons Used: View Logs, Filter
Step-by-Step Instructions:
Tap the Logs Page.
View collection status (Completed / Incomplete).
Use Filter to refine results.
5.3 Report Page (Resident Complaint)
Buttons Used: Submit Complaint
Step-by-Step Instructions:
Open the Report Page.
Tap Submit Complaint.
Select complaint type:
Uncollected Garbage
Overflowing Garbage
Illegal Dumping
Missed Route
Others
Select garbage type.
Enter notes.
Tap Submit.
System Result:
Complaint is sent directly to ENRO Staff.
6. Forgot Password (Mobile App – Garbage Collector)
Button Used: Forgot Password
Step-by-Step Instructions:
On the login screen, tap Forgot Password.
Enter your registered email address.
Tap Send Code.
Enter the OTP received via email.
Create a new password.
Tap Save.

══════SYSTEM ADMINISTRATOR USER MANUAL══════
7.1 User Management
Buttons Used: Add New User, Save
Step-by-Step Instructions:
Open User Management.
Click Add New User.
Enter user details.
Assign role(s).
Click Save.
System Result:
Credentials are emailed to the user.
7.2 Role Action Management
Buttons Used: Add Role Action, Save
Step-by-Step Instructions:
Open Role Action Management.
Click Add Role Action.
Select role.
Set permissions and capabilities.
Click Save.

══════ ENRO STAFF USER MANUAL ══════
8.1 Barangay Management
Buttons Used: Barangay Management, Add Barangay, Save
Step-by-Step Instructions:
Navigate to Barangay Management from the sidebar.
View the list of all barangays in Ormoc City.
Click Add Barangay if a new barangay needs to be added.
Enter the barangay details.
Click Save.
Purpose:
Barangays serve as references for route creation and schedule assignment.
8.2 Truck Management
Buttons Used: Truck Management, Add New Truck, Save
Step-by-Step Instructions:
Open Truck Management.
Click Add New Truck.
Enter the following information:
Truck ID
Truck Status (Active, On Route, Inactive, Under Maintenance)
Assign Garbage Collector
Click Save.
System Result:
The truck becomes available for route and schedule assignment.
8.3 Route Management
Buttons Used: Route Management, Add New Route, Add, Save Route, Clear Route
Step-by-Step Instructions:
Navigate to Route Management.
Click Add New Route.
Enter the Route Name.
Select one or multiple Barangays.
Choose a Polyline Color for the route.
On the map, click to define the Start Point.
Continue clicking to draw the Complete Route Path.
Click the last point to set the End Point.
Click Save Route.
Purpose:
Defines the official route followed by garbage trucks.
Routes are displayed to Garbage Collectors and Residents.
8.4 Schedule Management
Buttons Used: Schedule Management, Add New Schedule, Save
Step-by-Step Instructions:
Open Schedule Management.
Click Add New Schedule.
Select a Route (automatically loaded from Route Management).
Assign a Garbage Collector.
Verify the Truck Status (auto-linked).
Select the Garbage Type.
Choose the Collection Days.
Click Save.
System Result:
The schedule becomes active and visible to collectors and residents.
8.5 Garbage Report Management
Buttons Used: Garbage Report Management, View, Update Status
Step-by-Step Instructions:
Navigate to Garbage Report Management.
View complaints submitted by residents.
Select a report to view details:
Barangay
Report content
Date submitted
Update the complaint status (e.g., Pending, In Progress, Resolved).
Save changes.
System Result:
Residents can see updates on their submitted complaints.
8.6 Garbage Site Management
Buttons Used: Garbage Site Management, Add New Garbage Site, Save
Step-by-Step Instructions:
Open Garbage Site Management.
Click Add New Garbage Site.
Select the Barangay.
Enter the Site Name.
Use the map to mark the Drop-off Point.
Click Save.
System Result:
Garbage drop sites are visible to residents in the mobile app.
8.7 Collector Report Management
Buttons Used: Collector Report Management, View, Update Status
Step-by-Step Instructions:
Navigate to Collector Report Management.
View reports submitted by garbage collectors.
Open a report to see the issue details.
Update the issue status (Resolved / Unresolved).
Save the update.
8.8 Collector Attendance Management
Buttons Used: Collector Attendance Management, View
Step-by-Step Instructions:
Open Collector Attendance Management.
Monitor collector attendance status:
Clocked In (Started Route)
Clocked Out (Completed Route)
Use this information for operational monitoring.
8.9 Truck Map
Buttons Used: Truck Map, Search, Filter
Step-by-Step Instructions:
Open Truck Map.
View all trucks and routes displayed on the map.
Use Search to find a specific truck, route, or barangay.
Use Filter to refine results by:
Truck Status
Route
Barangay
Purpose:
Provides real-time visibility of garbage collection operations.
8.10 Profile and Login History
Buttons Used: Profile, Edit Profile, Change Password, Login History
Step-by-Step Instructions:
Open Profile.
Click Edit Profile to update personal information.
Click Change Password to set a new password.
Open Login History to view: (Login timestamps, Device information, Login status)
