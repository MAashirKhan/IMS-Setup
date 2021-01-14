# <p align="center"><img src="https://github.com/AashirKhan21/IMS-Setup/blob/main/IMS_SplashScreen.png"/><hr/></p>
## Inventory Master
* So, Basically its a desktop application based on C# programming language and SQL Server. It's a complete Inventory and Point Of Sale Software have all the functionalities and features which is required in a proper POS Software.

## User Installation Guide

### Pre-Requisite

* First of all, it has some pre-requisite for using this software you must have SQL Server Management Studio 2018 and Visual c++ redistributable for visual studio 2015 (64-bit).

[SQL Server Express 2019](https://www.microsoft.com/en-us/download/details.aspx?id=101064 "SQL Server Express 2019")

<p align="center"><img src="./media/sqlexpress2019.png"/></p>

[SQL Management Studio 2018](https://docs.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver15 "SQL Management Studio 2018")

<p align="center"><img src="./media/sms2018.png"/></p>

[C++ Redistributable for VS-2015](https://www.microsoft.com/en-pk/download/details.aspx?id=48145 "C++ Redistributable for VS2015")

<p align="center"><img src="./media/C++package.png"/></p>


* After that you download the zip file of the setup and extract the files after that there is IMS.sql file you simply double click on it so it will be open in your SQL Management Studio

#### Double Click on IMS.sql

<p align="center"><img src="./media/IMSSQL.png"/></p>

#### View In SSMS Execute Code

<p align="center"><img src="./media/sqlview.png"/></p>


* Once its open you have to execute that particular file step by step. After complete execution your Database is ready to go. Now you refresh your SQL Management Studio all the tables are appear there. Now right click on the Userstbl and select edit top to 200 Rows and insert data in particular columns.

#### Step one

<p align="center"><img src="./media/usertbl1.png"/></p>

#### Step Two (Write details Same as it is)

<p align="center"><img src="./media/usertbl2.png"/></p>

* After that now back to your setup folder and run the setup file and do all the basic settings.

<p align="center"><img src="./media/setupwizard.png"/></p>

* After the successful completion you are ready to go. 

<p align = "center"><img src="./media/splashscreen.png"/></p>

#### Login With Username and Password that you set in Database
<p>Username = admin , Password = admin</p>

<p align="center"><img src="./media/login.png" width= "250" height="400"></p>

## Admin Dashboard
<p align="center"><img src="./media/dashboard.png"></p>

## Cashier Dashboard / POS Dashboard
<p align="center"><img src="./media/POS.png"></p>

<p> Note: I already have some products and stock but when you install all things are zero</p>

### Features and Functionalities ###
* Notifier For Critical Stock
* Product Management
* Brand Management
* Categories
* Stock Management
  * Stock Entry
  * Stock Adjustment
* User's Settings
  * Create Account
  * Activate / Deactivate Account
  * Change Password
* System Settings
* Point of Sales
  * Generating Bill Reciept
  * Change Password 
  * Auto Calculated Tax Value
* Records
  * Generating Critical Stock Report 
  * Generating Top Selling Items Report
  * Inventory Report
  * Stock History Report


### Developed By Webisoft Pakistan ###
* If you like the project please give me a star
* Follow Us:
[Webisoft Pakistan](http://www.facebook.com/WebisoftPakistan/ "Webisoft Pakistan")
