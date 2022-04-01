# Iron Wired

Mobile App Development 2022

By Shreenija Daggavolu & Shreni Jain

View the most recent ReadMe with image-filled installation instructions: https://github.com/Shreenijad/ironW

The Homestead High School Library App is designed to provide a mobile interface that works alongside a stable backend database structure to provide users with information about available books, their holds, and their checkouts. Additionally, it implements a scanner that connects to web APIs in order to allow users to discover and hold books with their phone cameras. The app was developed in conjunction with Homestead High School's library to ensure our app would be useful in a real world situation.

This application was programmed entirely in Apple's Swift language. The backend was coded with MySQL.

Key Features
Robust backend relational database to store information
Book barcode scanner using RESTful APIs to generate book information
Well commented database access code
Checkout with your phone for ease of access
Intelligent keyword search algorithm to look for books
Hold system that lets you reserve a book to pick up later
Customized map with genre pins to identify book locations
Bug reporting to enable continuous development
Smart resource management to reduce database calls and memory leaks
Facebook integration to allow for a social aspect to our application
Getting Started
The following are the best ways to test HHS Library given your access to certain devices.

Mac OS Computer
Download XCode from the Mac App Store and create a free developer account on Apple's Developer Portal

XCode is a large download so you can test HHS Library on your personal Apple device with TestFlight in the meantime.
Once you are done downloading XCode, consult the Installation and Use section of this ReadMe.

Windows and iPhone
The best solution for adjudicators with a Windows and iOS device is to open the code on a text editor (we recommend Atom or Sublime Text) in Windows and test app functionality on a personal iOS device.

Download link to Atom Text Editor
Download link to Sublime Text Editor Install HHS Library on your personal device with these instructions.
Windows Without an iOS Device
The only way to view Swift code on a Windows device is through a text editor. These will not be able to build the project, but coding style and class structure is visible. Our code compiles without warnings or errors.

Download link to Atom Text Editor
Download link to Sublime Text Editor.
To experience the app in use, please watch this video showing the application in use:  
https://github.com/Eric-Cf/MAD-2018/wiki/TestFlight-and-YouTube-Video-Information
Prerequisites
To view the code

-Mac OS
-XCode
-Alternative Swift IDE (i.e. AppCode for Mac OS, text editor like Atom or SublimeText on Windows)
To run the application on your computer

-Mac OS
-XCode
-Developer signing
To run the application on your personal device

-iOS 9.0 or newer
-TestFlight application (available on the App Store)
Downloading on Personal Device with Apple's Testflight
testFlightIcon

TestFlight Logo

Follow this process to get HHS Library running on your personal device. Support: iPhones with iOS 9.0 or newer, most iPads should be able to run the application in scaled mode

Download Apple's official TestFlight application from the App Store
Continue through introduction pages until page with "Redeem" in upper right-hand corner appears
Select "Redeem" and enter one of the codes on the linked page into the text box *https://github.com/Eric-Cf/MAD-2018/wiki/TestFlight-and-YouTube-Video-Information
If the first code you select is unavailable, it was most likely entered by another adjudicator or has expired. If this is the case, please try one of the other provided codes.

Download the application and enjoy.
Note: TestFlight has been having documented issues recently. If the application does not work on your device, follow the installation and use instructions.
Installation and Use
A step by step series of how to run our project assuming prerequisites are met.

Open Xcode and select "Open another project..."
Locate the submission folder and enter the MAD folder inside, clicking on the white MAD.xcworkspace file proj2
After clicking open, click on the uppermost blue MAD file. You may see some red errors. proj3
Change the provisioning profile to your own developer account. proj4
It may say “Failed to create provisioning profile.” proj5
Edit the bundle identifier by adding a number to the end and click “Try Again.” proj6
You can now view all the classes and storyboards that go into the application.
[Make sure xcode is opening a simulator of a valid and modern iPhone.] proj8
To directly download the app onto your phone, plug your own phone into the computer and select your phone to download the app on your phone. You may have to approve the application on your iPhone.
After the application opens, log in with school id “1234567” and password “test.”
Feel free to browse the app! The scanner portion of the app only works on an actual phone where a camera can be accessed.
You can log in with facebook within the Onboarding Pages or the Profile Page. Please use the following login information to see how our app uses facebook friend systems to enhance user experience.
Email: dmcallister452@student.fuhsd.org
Password: fblaJudgeLogin img_5589 Onboarding Page On First Launch
Below is an example barcode to be used with the scanner.
You can also scan any book not found in the library to pull up information about it from online api's.
We encourage you to try this out with books around your house!
barcode

If you ever run into any issues, submit a bug report at the bottom of the "My Books" page.
Logging in
Application login credentials

Student ID: "1234567"
Password: "test"
Facebook login credentials

Email: dmcallister452@student.fuhsd.org
Password: fblaJudgeLogin
Database Structure
Database is a relational MySQL database running the InnoDB engine. It uses various foreign key checks to ensure the integrity of the data and eliminate potential errors in database calls. You can see our design schema here

Deployment
This application is supported by a server side script, so any user just has to connect with their account (made with the library when they join the school)

Built With
MySQL server hosted with bluehost.com
PHP access code hosted with bluehost.com
Swift code for UI and implementation
CocoaPods for library dependency management
Lottie by Airbnb for in-app animations
Adobe Photoshop CC for app graphics
XCode Integrated Development Environment
