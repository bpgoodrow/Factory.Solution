# _Factory_

#### By _**Ben Goodrow**_

#### _This is a simple C# database project. _

## Technologies Used

* Git
* C#
* .NET 6.0
* ASP.NET
* Entity Framework Core
* MVC
* BootStrap
* MySQL Workbench
* Razor view Engine

## Description

_This is a C# MVC application to allow a manager to add engineers and machines to their app. The engineers can then be assigned to machines._


## Setup/Installation Requirements


* _Clone this project with the following commands $ git clone https://github.com/bpgoodrow/Factory.Solution_
* _Open MySQLWorkBench and import SQL schema file included in root directory.
* _Create appsetting.json file and add the following code: $ "ConnectionStrings": {
    "DefaultConnection": "Server=localhost;Port=3306;database=[the name of your datbase];uid=root;pwd=[YOUR-PASSWORD-HERE];"
  }
* _Navigate to the root of the directory you want to save the project_
* _Open project in the command $ code ._
* _Navigate to the sub-directory of the project $ cd Factory_
* _Restore and install packages listed in the csproj in the command $ dotnet restore_
* _Build your dependencies in your command $ dotnet build_
* _Next we will execute this compiled code in command $ dotnet run_

## Known Bugs

N/A

## License

MIT License

Copyright (c) [2022] [Ben Goodrow]

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