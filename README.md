# ASP.NET-MVC-4-Entity-Framework-Scaffolding-and-Migrations


Nuget Command :- 

  Install-Package MvcScaffolding -Version 1.0.8-vs2013 -Pre

  Install-Package EntityFramework -IncludePrerelease   //Install-Package EntityFramework -Version 6.0.0 -IncludePrerelease

In code first approach. When you changed model then you have to run the following commands for changing database.

Firstly,

  Enable-Migrations -ContextTypeName DemoDbContext

Secondly,

  add-migration InitialCreate

Thirdly,

  update-Database
