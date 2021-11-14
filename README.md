# _Pierre's Sweet and Savory Treats_

#### By _**Carlos Urquiza**_

#### _MVC web application for Pierre's Sweet and Savory Treats._

## Technologies Used

* _C#_
* _MVC_
* _Razor View Engine_
* _RESTful Routing_
* _.NET 5.0_
* _Entity Framework_
* _Pomelo Entity Framework_
* _MySQL Workbench_
* _Identity_
* _Git_

## Description

_This MVC web application has the following functionality:_

* _The application has user authentication. A user can log in and log out. Only logged in users have create, update and delete functionality. All users have read functionality_
* _There is a many-to-many relationship between Treats and Flavors. A treat can have many flavors and a flavor can have many treats._
* _The user can navigate to a splash page that lists all treats and flavors. The user can click on an individual treat or flavor and see all the treats/flavors that belong to it._

## Setup/Installation Requirements

#### **Before taking the following installation steps, ensure you have [C#, .NET](https://www.learnhowtoprogram.com/c-and-net-part-time-c-and-react-track/getting-started-with-c/installing-c-and-net), [dotnet script](https://www.learnhowtoprogram.com/c-and-net-part-time-c-and-react-track/getting-started-with-c/installing-dotnet-script) and [MySql](https://www.learnhowtoprogram.com/c-and-net-part-time-c-and-react-track/getting-started-with-c/installing-and-configuring-mysql)    installed on your computer.** 

* _Clone this repository._
* _Open your terminal._
* _Navigate to the directory (such as your Desktop folder) where you want the cloned repository to be housed._
* _Run `git clone https://github.com/webquiza/PierresTreats.Solution.git`._
* _Press Enter._

#### **Connect database**

* _Connect the database to the project by creating a `appsettings.json` file inside `PierresTreats.Solution/PierresTreats`._
* _Within your new `appsettings.json` file, add the following piece of code. Note that you will need to enter the password you created for your specific MySQL configuration ( remove the [ ] ):_

```
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=localhost;Port=3306;database=carlos_urquiza;uid=root;pwd=[YOUR-PASSWORD-HERE];"
  }
}
```

* _Navigate to `PierresTreats` directory._
* _Run `dotnet restore` to retrieve and install the packages we listed in .csproj._
* _Run `dotnet build` to build the project._
* _Update the database by running `dotnet ef database update` (ensure you have MySQL Workbench open)._ 
* _Run `dotnet run` to start up your local host (http://localhost:5000)._

## Known Bugs

* _No known bugs._

## License

MIT License

Copyright (c) 2021 Carlos Urquiza

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

## Contact Information

_Feel free to contact me at webquiza@gmail.com with any questions regarding this webpage._