# _Factory_

#### By **Zach Wilson**

#### _A C# application that uses a many-to-many database to help the fictional 'Dr. Sillystringz' manage his wacky factory_

## Technologies Used

* HTML
* C#
* .NET
* Entity
* Sql

## Description

_A webpage developed by personal request of the world renowned (And nonexistant) tinkerer 'Dr. Sillystringz.' This application keeps track of all engineers currently employed by the good doctor as well as all the crazy machines his engineers are building and maintaining. Uses the Entity Framework and Sql to build databases that store information regarding engineers and machines._

## Setup/Installation Requirements

* Clone this repository to your Desktop
* Open 'Factory' in your code editor
* Use your terminal to navigate to 'Factory.Solution/Factory' and create a file called 'appsettings.json'
* Fill your appsettings.json file with the code below:

{
"ConnectionStrings": {
"DefaultConnection": "Server=localhost;Port=3306;database=zach_wilson;uid=root;pwd=[YOUR PASSWORD];"
}
}

* Download MySQL and MySQL Workbench to set up a local database
* Once installed, open MyMql Workbench and open a local server
* In the Navigator, select the Administration tab and then select Data Import/Restore
* Under Import Options, select Import From Self-Contained File, and then select the "zach_wilson.sql" file which can be found in Factory.Solution
* In the Default Schema to be Imported To option, select New
* Enter the name 'zach_wilson' for your database and select OK
* Click Start Import to begin database import

* Run 'dotnet restore' in your terminal to install bin & obj folders.

* Use your terminal to navigate back to 'Factory.Solution/Factory' and run 'dotnet run' to activate application.
* Use the user interface provided by the webpage to manage stylists and clients.

## Known Bugs

Currently no known bugs.

## License

MIT License

Copyright (c) [2021] [Zachary Wilson]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

### Feel free to fix/edit all contained code to your liking. If you encounter and problems, contact me at zwilson22495@gmail.com