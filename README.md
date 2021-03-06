# iConnect

### What is iConnect?
iConnect is a java based program developed using the Android Studio IDE that makes everyday life easier for people to stay connected with friends, family, professionals, and other acquaintances. The iConnect app provides users the ability to make connections made of groups and individuals with a notification sent to connect with the specified individual after so many days. The use of this application takes away the stress of remembering to stay in contact with those who are in your circle of friendship, allowing you to dedicate your time and energy to other important tasks. 

### iConnect in Action
![](Images/MainActivityPic.png)
![](Images/AddNewConnectionPic.png)
![](Images/GroupAdd.png)
![](Images/PersonAddPic.png)
![](Images/groupActivityPic.png)
![](Images/PersonPic.png)
![](Images/NotificationPic.png)


### How it Works
The iConnect app includes the following features and functionality:
SQLite database, buttons, textviews, linear layouts, edit text entries, and custom list views and adapters to provide the user interface throughout 6 activity screens. The 6 screens include:
* Main: The user can see and add their immediate individuals and groups that are of the up most importance to stay in contact with. 
* Add connection: The user can select if they want to add a new group or a new person to their connection list.
* Add group: A new group can be created by simply typing in the name of the group and clicking the finish or add person buttons that will provide the feature of adding a person to the just recently created group. When the finish or add person buttons are clicked the data entered will be saved to the SQLite database where it will be listed in the Group or Main activity screens when the Add group screen is exited.
* Add person: A new person is created here with the following fields of information: name, subtitle, contact frequency, and note. When the name, contact frequency, and subtitle fields are filled out and the finish or add person buttons is clicked the information will be saved to the SQLite database where it will be read and displayed to different degrees in the Edit person, Main, and Group activity screens.
* Person: The selected person, attached note, and the amount of days till a reminder is sent is displayed with two buttons, the blue one being the connected button that confirms the user connected with the specified person after which the days number will be reset using the SQLite database and will continue counting down once more to the reminding day. The orange dismiss button confirms that the user did not connect with the following person.
* Group: The user can see the group they clicked on from main and the individuals assosciated with that group. Here the user can create additional connections within this group. 

### Android Studio Setup Instructions
Go to the Android Studio official site at this link https://developer.android.com/studio. Download Android Studio Open Android Studio and upon launching it should prompt you to create a new project where you can select the type of template for your new project in which case you would select the empty activity template. If you are not prompted to create a new project go the top left hand corner of the screen where it says file and click new and then new project, afterwhich it will prompt you to select your project template where you will select empty activity to get started.

### How to Launch an App from Android Studio
To launch your application in android studio you can either use a plug-in android device or a virtual device. To set up a virtual device click the green triangle button at the top of the screen. You may be taken directly to virtual device configuration screen where you will click the phone tab or you will be taken to the Android virtual device manager where you will click create virtual device. Once in the virtual device configuration screen and you have selected the phone tab you will select the pixel 2 option and select next. Select the release name R and click next and then finish on the next screen. After configuring the virtual device you should be able to test and run your app, but there is a chance that could get the following error "Intel HAXM is required to run this AVD.VT-x is disabled in BIOS. Enable VT-x in your BIOS security settings". To enable BIOS look up the instructions for your laptop/operating system. This link is helpful as well for enabling BIOS https://www.youtube.com/watch?v=mW_HNKiS3_8

### Helpful Links Used in Android Studio Development:
* Adding multiple columns to your ListView three parts: https://www.youtube.com/watch?v=8K-6gdTlGEA&t=381s , https://www.youtube.com/watch?v=hHQqFGpod14 , https://www.youtube.com/watch?v=jpt3Md9aDIQ 
* How to Create Multiple Tables in SQL Lite Database in Android Studio: https://www.youtube.com/watch?v=lQIoxBq10xA&t=734s 
* Saving data with SQLite and adding it to a ListView: https://www.youtube.com/watch?v=SK98ayjhk1E 
* Android Listview Onitemclick Example: https://www.youtube.com/watch?v=wSCIuIbS-nk&t=578s 
* How to Pass data from One to another Activity || Android studio tutorial: https://www.youtube.com/watch?v=Yi8mxXsroJ4&t=169s 
* Custom ListView Adapter For Displaying Multiple Columns: https://www.youtube.com/watch?v=E6vE8fqQPTE 
* How to Remove the ActionBar from Specific Activities (Or All Activities): https://www.youtube.com/watch?v=A9rcKZUm0zM 
* Editing and deleting data from an SQLite database [Beginner Android Studio Example]: https://www.youtube.com/watch?v=nY2bYJyGty8
* How to Start a Foreground Service in Android (With Notification Channels): https://www.youtube.com/watch?v=FbpD5RZtbCc&t=1045s
