
user@DESKTOP-O8C3BFH MINGW64 /c/dev/mysql/microarch/mysqltest/sqlserverconn (sql-server-connection-string-chnage)
$ dotnet new help
Getting ready...
Usage: new [options]

Options:
  -h, --help          Displays help for this command.
  -l, --list          Lists templates containing the specified name. If no name is specified, lists all templates.
  -n, --name          The name for the output being created. If no name is specified, the name of the current directory is used.
  -o, --output        Location to place the generated output.
  -i, --install       Installs a source or a template pack.
  -u, --uninstall     Uninstalls a source or a template pack.
  --nuget-source      Specifies a NuGet source to use during install.
  --type              Filters templates based on available types. Predefined values are
"project", "item" or "other".
  --force             Forces content to be generated even if it would change existing files.
  -lang, --language   Filters templates based on language and specifies the language of
the template to create.


No templates matched the input template name: help.

Templates                                         Short Name         Language          Tags
----------------------------------------------------------------------------------------------------------------------------
Console Application                               console            [C#], F#, VB      Common/Console
Class library                                     classlib           [C#], F#, VB      Common/Library
Unit Test Project                                 mstest             [C#], F#, VB      Test/MSTest
NUnit 3 Test Project                              nunit              [C#], F#, VB      Test/NUnit
NUnit 3 Test Item                                 nunit-test         [C#], F#, VB      Test/NUnit
xUnit Test Project                                xunit              [C#], F#, VB      Test/xUnit
Razor Page                                        page               [C#]              Web/ASP.NET
MVC ViewImports                                   viewimports        [C#]              Web/ASP.NET
MVC ViewStart                                     viewstart          [C#]              Web/ASP.NET
ASP.NET Core Empty                                web                [C#], F#          Web/Empty
ASP.NET Core Web App (Model-View-Controller)      mvc                [C#], F#          Web/MVC
ASP.NET Core Web App                              razor              [C#]              Web/MVC/Razor Pages
ASP.NET Core with Angular                         angular            [C#]              Web/MVC/SPA
ASP.NET Core with React.js                        react              [C#]              Web/MVC/SPA
ASP.NET Core with React.js and Redux              reactredux         [C#]              Web/MVC/SPA
Razor Class Library                               razorclasslib      [C#]              Web/Razor/Library/Razor Class Library
ASP.NET Core Web API                              webapi             [C#], F#          Web/WebAPI
global.json file                                  globaljson                           Config
NuGet Config                                      nugetconfig                          Config
Web Config                                        webconfig                            Config
Solution File                                     sln                                  Solution

Examples:
    dotnet new mvc --auth Individual
    dotnet new webapi
    dotnet new --help

user@DESKTOP-O8C3BFH MINGW64 /c/dev/mysql/microarch/mysqltest/sqlserverconn (sql-server-connection-string-chnage)
$

user@DESKTOP-O8C3BFH MINGW64 /c/dev/mysql/microarch/mysqltest/sqlserverconn (sql-server-connection-string-chnage)
$ dotnet add package Microsoft.EntityFrameworkCore.Design
Could not find any project in `c:\dev\mysql\microarch\mysqltest\sqlserverconn\`.
Usage: dotnet add <PROJECT> package [options] <PACKAGE_NAME>

Arguments:
  <PROJECT>        The project file to operate on. If a file is not specified, the command will search the current directory for one.
  <PACKAGE_NAME>   The package reference to add.

Options:
  -h, --help                          Show command line help.
  -v, --version <VERSION>             The version of the package to add.
  -f, --framework <FRAMEWORK>         Add the reference only when targeting a specific framework.
  -n, --no-restore                    Add the reference without performing restore preview and compatibility check.
  -s, --source <SOURCE>               The NuGet package source to use during the restore.
  --package-directory <PACKAGE_DIR>   The directory to restore packages to.
  --interactive                       Allows the command to stop and wait for user input or action (for example to complete authentication).

user@DESKTOP-O8C3BFH MINGW64 /c/dev/mysql/microarch/mysqltest/sqlserverconn (sql-server-connection-string-chnage)
$ dotnet new console
The template "Console Application" was created successfully.

Processing post-creation actions...
Running 'dotnet restore' on c:\dev\mysql\microarch\mysqltest\sqlserverconn\sqlserverconn.csproj...
  Restoring packages for c:\dev\mysql\microarch\mysqltest\sqlserverconn\sqlserverconn.csproj...
  Generating MSBuild file c:\dev\mysql\microarch\mysqltest\sqlserverconn\obj\sqlserverconn.csproj.nuget.g.props.
  Generating MSBuild file c:\dev\mysql\microarch\mysqltest\sqlserverconn\obj\sqlserverconn.csproj.nuget.g.targets.
  Restore completed in 1.33 sec for c:\dev\mysql\microarch\mysqltest\sqlserverconn\sqlserverconn.csproj.

Restore succeeded.


user@DESKTOP-O8C3BFH MINGW64 /c/dev/mysql/microarch/mysqltest/sqlserverconn (sql-server-connection-string-chnage)
$ dotnet add package Microsoft.EntityFrameworkCore.Design
  Writing C:\Users\user\AppData\Local\Temp\tmp45F3.tmp
info : Adding PackageReference for package 'Microsoft.EntityFrameworkCore.Design' into project 'c:\dev\mysql\microarch\mysqltest\sqlserverconn\sqlserverconn.csproj'.
log  : Restoring packages for c:\dev\mysql\microarch\mysqltest\sqlserverconn\sqlserverconn.csproj...
info :   GET https://api.nuget.org/v3-flatcontainer/microsoft.entityframeworkcore.design/index.json
info :   OK https://api.nuget.org/v3-flatcontainer/microsoft.entityframeworkcore.design/index.json 72ms
info : Package 'Microsoft.EntityFrameworkCore.Design' is compatible with all the specified frameworks in project 'c:\dev\mysql\microarch\mysqltest\sqlserverconn\sqlserverconn.csproj'.
info : PackageReference for package 'Microsoft.EntityFrameworkCore.Design' version '2.1.4' added to file 'c:\dev\mysql\microarch\mysqltest\sqlserverconn\sqlserverconn.csproj'.

user@DESKTOP-O8C3BFH MINGW64 /c/dev/mysql/microarch/mysqltest/sqlserverconn (sql-server-connection-string-chnage)
$ dotnet restore
  Restoring packages for c:\dev\mysql\microarch\mysqltest\sqlserverconn\sqlserverconn.csproj...
  Generating MSBuild file c:\dev\mysql\microarch\mysqltest\sqlserverconn\obj\sqlserverconn.csproj.nuget.g.props.
  Restore completed in 2.46 sec for c:\dev\mysql\microarch\mysqltest\sqlserverconn\sqlserverconn.csproj.

user@DESKTOP-O8C3BFH MINGW64 /c/dev/mysql/microarch/mysqltest/sqlserverconn (sql-server-connection-string-chnage)
$ dotnet ef dbcontext scaffold "Server=DESKTOP-O8C3BFH\SQLEXPRESS;Database=Testing;Trus
ted_Connection=True;" Microsoft.EntityFrameworkCore.SqlServer -o Models
Unable to find provider assembly with name Microsoft.EntityFrameworkCore.SqlServer. Ensure the specified name is correct and is referenced by the project.

user@DESKTOP-O8C3BFH MINGW64 /c/dev/mysql/microarch/mysqltest/sqlserverconn (sql-server-connection-string-chnage)
$

user@DESKTOP-O8C3BFH MINGW64 /c/dev/mysql/microarch/mysqltest/sqlserverconn (sql-server-connection-string-chnage)
$ dotnet add package Microsoft.EntityFrameworkCore.SqlServer
  Writing C:\Users\user\AppData\Local\Temp\tmp48DF.tmp
info : Adding PackageReference for package 'Microsoft.EntityFrameworkCore.SqlServer' into project 'c:\dev\mysql\microarch\mysqltest\sqlserverconn\sqlserverconn.csproj'.
log  : Restoring packages for c:\dev\mysql\microarch\mysqltest\sqlserverconn\sqlserverconn.csproj...
info :   GET https://api.nuget.org/v3-flatcontainer/sqlserver.data.entityframeworkcore/index.json
info :   GET https://api.nuget.org/v3-flatcontainer/microsoft.entityframeworkcore.sqlserver/index.json
info :   NotFound https://api.nuget.org/v3-flatcontainer/sqlserver.data.entityframeworkcore/index.json 923ms
info :   OK https://api.nuget.org/v3-flatcontainer/microsoft.entityframeworkcore.sqlserver/index.json 451ms
info :   GET https://api.nuget.org/v3-flatcontainer/microsoft.entityframeworkcore.sqlserver/2.1.4/microsoft.entityframeworkcore.sqlserver.2.1.4.nupkg
info :   OK https://api.nuget.org/v3-flatcontainer/microsoft.entityframeworkcore.sqlserver/2.1.4/microsoft.entityframeworkcore.sqlserver.2.1.4.nupkg 149ms
log  : Installing Microsoft.EntityFrameworkCore.SqlServer 2.1.4.
error: Unable to find package SQLServer.Data.EntityFrameworkCore. No packages exist with this id in source(s): nuget.org
error: Package 'Microsoft.EntityFrameworkCore.SqlServer' is incompatible with 'all' frameworks in project 'c:\dev\mysql\microarch\mysqltest\sqlserverconn\sqlserverconn.csproj'.

user@DESKTOP-O8C3BFH MINGW64 /c/dev/mysql/microarch/mysqltest/sqlserverconn (sql-server-connection-string-chnage)
$ dotnet restore
  Restoring packages for c:\dev\mysql\microarch\mysqltest\sqlserverconn\sqlserverconn.csproj...
  Restore completed in 2.57 sec for c:\dev\mysql\microarch\mysqltest\sqlserverconn\sqlserverconn.csproj.

user@DESKTOP-O8C3BFH MINGW64 /c/dev/mysql/microarch/mysqltest/sqlserverconn (sql-server-connection-string-chnage)
$ dotnet add package Microsoft.EntityFrameworkCore.SqlServer
  Writing C:\Users\user\AppData\Local\Temp\tmpFF8.tmp
info : Adding PackageReference for package 'Microsoft.EntityFrameworkCore.SqlServer' into project 'c:\dev\mysql\microarch\mysqltest\sqlserverconn\sqlserverconn.csproj'.
log  : Restoring packages for c:\dev\mysql\microarch\mysqltest\sqlserverconn\sqlserverconn.csproj...
info :   CACHE https://api.nuget.org/v3-flatcontainer/microsoft.entityframeworkcore.sqlserver/index.json
info : Package 'Microsoft.EntityFrameworkCore.SqlServer' is compatible with all the specified frameworks in project 'c:\dev\mysql\microarch\mysqltest\sqlserverconn\sqlserverconn.csproj'.
info : PackageReference for package 'Microsoft.EntityFrameworkCore.SqlServer' version '2.1.4' added to file 'c:\dev\mysql\microarch\mysqltest\sqlserverconn\sqlserverconn.csproj'.

user@DESKTOP-O8C3BFH MINGW64 /c/dev/mysql/microarch/mysqltest/sqlserverconn (sql-server-connection-string-chnage)
$ dotnet ef dbcontext scaffold "Server=DESKTOP-O8C3BFH\SQLEXPRESS;Database=Testing;Trus
ted_Connection=True;" Microsoft.EntityFrameworkCore.SqlServer -o Models
Unable to identify the primary key for table 'dbo.Users'.
Unable to generate entity type for table 'dbo.Users'.

user@DESKTOP-O8C3BFH MINGW64 /c/dev/mysql/microarch/mysqltest/sqlserverconn (sql-server-connection-string-chnage)
$ dotnet ef dbcontext scaffold "Server=DESKTOP-O8C3BFH\SQLEXPRESS;Database=Testing;Trus
ted_Connection=True;" Microsoft.EntityFrameworkCore.SqlServer -o Models
The following file(s) already exist in directory c:\dev\mysql\microarch\mysqltest\sqlserverconn\Models: TestingContext.cs. Use the Force flag to overwrite these files.

user@DESKTOP-O8C3BFH MINGW64 /c/dev/mysql/microarch/mysqltest/sqlserverconn (sql-server-connection-string-chnage)
$ dotnet ef dbcontext scaffold "Server=DESKTOP-O8C3BFH\SQLEXPRESS;Database=Testing;Trus
ted_Connection=True;" Microsoft.EntityFrameworkCore.SqlServer -o Models

user@DESKTOP-O8C3BFH MINGW64 /c/dev/mysql/microarch/mysqltest/sqlserverconn (sql-server-connection-string-chnage)
$ dotnet build
Microsoft (R) Build Engine version 15.8.169+g1ccb72aefa for .NET Core
Copyright (C) Microsoft Corporation. All rights reserved.

  Restore completed in 224.04 ms for c:\dev\mysql\microarch\mysqltest\sqlserverconn\sqlserverconn.csproj.
Models\TestingContext.cs(24,10): warning CS1030: #warning: 'To protect potentially sensitive information in your connection string, you should move it out of source code. See http://go.microsoft.com/fwlink/?LinkId=723263 for guidance on storing connection strings.' [c:\dev\mysql\microarch\mysqltest\sqlserverconn\sqlserverconn.csproj]
Program.cs(11,33): error CS0246: The type or namespace name 'testingContext' could not be found (are you missing a using directive or an assembly reference?) [c:\dev\mysql\microarch\mysqltest\sqlserverconn\sqlserverconn.csproj]
Program.cs(13,30): error CS1579: foreach statement cannot operate on variables of type '?' because '?' does not contain a public instance definition for 'GetEnumerator' [c:\dev\mysql\microarch\mysqltest\sqlserverconn\sqlserverconn.csproj]

Build FAILED.

Models\TestingContext.cs(24,10): warning CS1030: #warning: 'To protect potentially sensitive information in your connection string, you should move it out of source code. See http://go.microsoft.com/fwlink/?LinkId=723263 for guidance on storing connection strings.' [c:\dev\mysql\microarch\mysqltest\sqlserverconn\sqlserverconn.csproj]
Program.cs(11,33): error CS0246: The type or namespace name 'testingContext' could not be found (are you missing a using directive or an assembly reference?) [c:\dev\mysql\microarch\mysqltest\sqlserverconn\sqlserverconn.csproj]
Program.cs(13,30): error CS1579: foreach statement cannot operate on variables of type '?' because '?' does not contain a public instance definition for 'GetEnumerator' [c:\dev\mysql\microarch\mysqltest\sqlserverconn\sqlserverconn.csproj]
    1 Warning(s)
    2 Error(s)

Time Elapsed 00:00:05.85

user@DESKTOP-O8C3BFH MINGW64 /c/dev/mysql/microarch/mysqltest/sqlserverconn (sql-server-connection-string-chnage)
$ dotnet build
Microsoft (R) Build Engine version 15.8.169+g1ccb72aefa for .NET Core
Copyright (C) Microsoft Corporation. All rights reserved.

  Restore completed in 191.72 ms for c:\dev\mysql\microarch\mysqltest\sqlserverconn\sqlserverconn.csproj.
Models\TestingContext.cs(24,10): warning CS1030: #warning: 'To protect potentially sensitive information in your connection string, you should move it out of source code. See http://go.microsoft.com/fwlink/?LinkId=723263 for guidance on storing connection strings.' [c:\dev\mysql\microarch\mysqltest\sqlserverconn\sqlserverconn.csproj]
  sqlserverconn -> c:\dev\mysql\microarch\mysqltest\sqlserverconn\bin\Debug\netcoreapp2.1\sqlserverconn.dll

Build succeeded.

Models\TestingContext.cs(24,10): warning CS1030: #warning: 'To protect potentially sensitive information in your connection string, you should move it out of source code. See http://go.microsoft.com/fwlink/?LinkId=723263 for guidance on storing connection strings.' [c:\dev\mysql\microarch\mysqltest\sqlserverconn\sqlserverconn.csproj]
    1 Warning(s)
    0 Error(s)

Time Elapsed 00:00:05.47

user@DESKTOP-O8C3BFH MINGW64 /c/dev/mysql/microarch/mysqltest/sqlserverconn (sql-server-connection-string-chnage)
$ dotnet run
SQLServer Users!
id 100, name voidy, email v@abc.com

user@DESKTOP-O8C3BFH MINGW64 /c/dev/mysql/microarch/mysqltest/sqlserverconn (sql-server-connection-string-chnage)
$ git pull -v
From https://github.com/nat2k5us/microarch
 = [up to date]      sql-server-connection-string-chnage -> origin/sql-server-connection-string-chnage
 = [up to date]      master     -> origin/master
Already up to date.

user@DESKTOP-O8C3BFH MINGW64 /c/dev/mysql/microarch/mysqltest/sqlserverconn (sql-server-connection-string-chnage)
$ git config --get-all user.name

user@DESKTOP-O8C3BFH MINGW64 /c/dev/mysql/microarch/mysqltest/sqlserverconn (sql-server-connection-string-chnage)
$ git config --global user.email "nat2k5us@gmail.com"

user@DESKTOP-O8C3BFH MINGW64 /c/dev/mysql/microarch/mysqltest/sqlserverconn (sql-server-connection-string-chnage)
$ git pull -vgit config --global user.email "you@example.com"