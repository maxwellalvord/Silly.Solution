# Dr. Sillystringz's Factory

### This is a basic MVC webpage to all a factory to manage their machines and engineers.

## By Maxwell Alvord


## Technologies Used

* .Net 5.0
* HTML
* C#
* CSS
* EntityFrameWork
* MySQL WorkBench

## Description

This is a MVC Webpage that have many to many functionality within the MySQL database and the program built. The user may add Machines and/or Engineers and have them organized in such a way that a machine may have multiple engineers assigned to it and a engineer can be assigned to multiple different machines. 

## Setup/Installation Requirements 🖊️

* $ git clone <https://github.com/maxwellalvord/Silly.Solution>
* $ cd Silly.Solution
* $ touch appsetting.json 
* Open the appsetting.json file and enter:

```
{ 
  "ConnectionStrings": { 
    "DefaultConnection": "Server=localhost;Port=3306;database=[Database-Name];uid=root;pwd=[YOUR-PASSWORD];" 
  } 
}
```
* Download MySQL WorkBench
* run dotnet tool install --global dotnet-ef --version 5.0.1 globally
* $ cd Factory
* $ dotnet add package Microsoft.EntityFrameworkCore -v 5.0.0
* $ dotnet add package Pomelo.EntityFrameworkCore.MySql -v 5.0.0-alpha.2
* $ dotnet add package Microsoft.EntityFrameworkCore.Proxies -v 5.0.0
* $ dotnet restore
* $ dotnet build
* $ dotnet ef migrations add Initial
* $ dotnet ef database update
* $ dotnet run
* Visit  <http://localhost:5000>

## Known Bugs

* N/A

## License
[MIT](https://opensource.org/osd)

Copyright &copy;
2022 Maxwell Alvord

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

<br>

## Contact Information
Contact me with questions and bugs at: <br>
[A link to my issues page on GitHub](https://github.com/maxwellalvord/maxwellalvord/issues)<br>
or email me at <a href = "mailto:maxwellalvord@gmail.com">maxwellalvord@gmail.com</a>