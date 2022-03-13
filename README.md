# _**Eau Claire's Hair Salon**_

### by _**Cesar Lopez**_

### _March 11, 2022_

#### _Eau Claire's Hair Salon is an ASP.NET Core MVC Web application using a SQL database, wherein the user can add a list of stylists working at the salon, and for each stylist, add clients who see that stylist. The stylists are unique, so each client can only see (belong to) a single stylist._

![]()

## Technologies Used

- _C#
- _.NET
- _ASP.NET MVC
- _SQL
- _MySQL Workbench

## Project Title: Eau Claire's Hair Salon

#### MVP Objective

Create a ASP.NET MVC web application using a SQL database that stores a list of clients under the respective stylist.

### User Interface

The web application will provide a form, which asks the user for the stylist's name, then asks the user for to enter a client and day. Once the client is entered, the user can choose a stylist for the client from a dropdown menu. The user can also add another stylist, enter a new client, or view a list of current clients for each stylist.

## Project Setup/Installation Instructions

1. Download .NET 5.0 SDK for : <a href="https://dotnet.microsoft.com/download/dotnet/thank-you/sdk-5.0.102-windows-x64-installer" target="_blank">Windows</a>

1. Download .NET 5.0 SDK for Mac: <a href="https://dotnet.microsoft.com/download/dotnet/thank-you/sdk-5.0.100-macos-x64-installer" target="_blank">Mac</a>

2. Clone the appliction to your computer by entering: `git clone https://github.com/wowgr8/HairSalon` in the terminal
3. Open the repository in editor 
4. Import cesar_lopez.sql database into MySql by following these steps 
5. Launch MySql Workbench 
6. Select MySql intance in the middle under MySqlConnections
7. Select Navigator>Administration then select DataImport/Restore 
8. Select Import from Self- contained File 
9. Click the 3 dots at the end of Self-Contained file and in the pop up choose the cesar_lopez.sql file
10. In the Default Schema to be Imported to section select new and a pop up will appear, name the schema cesar_lopez 
11. Click start import within the import progress if on windows, if on mac it will be in the same window
12. Once complete, refresh and it will appear

## Setup for appsettings.json
1. In the terminal, cd into the file HairSalon
2. Create a new file by entering `touch appsettings.json`  in the terminal
3. Enter the following code below. Be sure to replace [Password] with the password for MySql workbench that you have set up. Do the same for [userid], the uid is the user id you've set up in MySql workbench.
4. 
```
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=localhost;Port=3306;database=cesar_lopez;uid=[userid];pwd=[Password];"
  }
}
```  

5. After that is complete, run the application by cd'ing into HairSalon and enter `dotnet run` in your terminal 
6. when it finishes you should see `Now listenin on: http://localhost:5000 ` CTRL click the link to view the application in your browser.

## Additional Setup/Installation Note for Windows Users

- None

## Known Bugs

- _None._

## License

[MIT License](https://opensource.org/licenses/MIT) Published _**2022**_ by _**Cesar Lopez**_

## Contact Information

If you encounter any issues with this site, please contact the dev team:

- Cesar Lopez at [Lopez.cesar.aug@gmail.com](mailto:lopez.cesar.aug@gmail.com)