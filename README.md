# Steps to run the project

    1.Download and extract the zip file submitted.
    2.Open your mysql client and create a database named “OTTDataBase” using the following command:
        ```
        CREATE DATABASE OTTDataBase;
        ```
    3.Use the database and run the MediaManagementSystem.sql script which is present in the src folder in the extracted folder using  the following commands:
        ```
        USE OTTDataBase;
        ```
        then
        ```
        SOURCE <path/to/extracted/folder/src/ MediaManagementSystem.sql>;
        ```


    4.Open VS Code. Click on File > Open Folder. In the pop up window, select the folder extraced in the previous step.
    5.Open the “MMS_Factory.java” file and change the username and password to your mysql username and password.
    6.On the bottom left of the window, click on JAVA PROJECTS -> Referenced Libraries.
    7.In case the jar file does not show up under “Referenced Libraries”, click on the “+” sign next to the “Referenced Libraries” and select the jar file which is in the lib folder.
    8.Open the “MMS_Demo.java” file and click on “Run” that appears above the main function.
    9.In the terminal you will see a menu. An “O” next to the option indicates that only the Owner can execute that option while “O/U” indicates both Owner and User can execute that option.

# Switching between Owner and User

    1. Option 9 is used to switch between user and owner.
    2. The password for “User” is “User” and the password for “Owner” is “Owner”.
