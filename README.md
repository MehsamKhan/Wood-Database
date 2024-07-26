# Wood Database
This is a database containing the non-elastic mechanical properties (such as fracture and creep) of different species of wood. It has been created as a relational database using Microsoft SQL Server. 

# To access the database, follow these steps (Instructions for Windows OS):

## Install Microsoft SQL Server Express (Free):
* Click on "Download Now" under Express from here:
https://www.microsoft.com/en-us/sql-server/sql-server-downloads

![image](https://github.com/user-attachments/assets/94fa3882-a61b-4351-b61c-02a6f12addf3)

* Open the downloaded .exe file and choose "Custom" installation:
  
![image](https://github.com/user-attachments/assets/9b9cb1c2-13df-4625-bb00-fc7f5b218dd9)

* Then click "Install" and the program will open a new pop-up window, "SQL Server Installation Center" like the one shown below:

![image](https://github.com/user-attachments/assets/e2bfac36-1348-4c8a-a735-e63f950f7e05)

* Click on "New SQL Server standalone installation or add............."

* Accept all the defaults and keep clicking next until it finishes installing

* Go Back to the window  that says "SQL Server Installation Center" and now click on "Install SQL Server Management Tools"

* It will take you to a new web-page. Click on "Download SQL Server Management Studio (SSMS) #Version Number#":

![image](https://github.com/user-attachments/assets/b5dd5223-b4f0-4d61-8073-93614c7e52bf)

* Open the downloaded .exe file and click on "Install"

## Open Microsoft SQL Server Management Studio and Import Database:

* Search for "SSMS" in the Windows Search bar and open "SQL Server Management Studio"

* Depending on your system, the first time you open SQL Server Management Studio, you might get this window:

![image](https://github.com/user-attachments/assets/e1725d9e-5de6-4065-acb9-cf451001f16a)

* If the "Server name" is unpopulated, click on "Browse for more..." under the drop-down button

* Expand the "Database Engine" option under Local Servers and click on "#your computer name#\SQLEXPRESS" and click "OK":

![image](https://github.com/user-attachments/assets/57e783f6-a0f9-489a-9bfc-b58c65084f3a)

* Check "Trust server certificate" and click "Connect":

![image](https://github.com/user-attachments/assets/30db39fd-96cf-4b85-b26e-69cc5540d416)

* Once the database engine is connected, right-click on "Database" in the Object Explorer and click "Restore Database":

![image](https://github.com/user-attachments/assets/a7b73314-1b65-4ebd-956e-3ed367415b8d)

* Check "Device" and browse for the "Wood Calibration.bak" that you have downloaded from 

![image](https://github.com/user-attachments/assets/138be298-8b6f-461a-acf3-1d8a6f48cd39)
