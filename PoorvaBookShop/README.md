﻿Name: Poorva Virmani
Student ID: w0816105

2023-10-30
1408
Initiate the project with the name PoorvaBookShop and ASP.NET Core(Model-view-controller) version being 5.0 and enabled the razor runtime compilation
1412
Got an error when trying to run the project for the first time but it says couldn't find the page.
1415
Realised that i needed to comment the SSL port in launchsetting.json and re-run it worked successfully.
1442
In the startup.cs on line 35 removed the (options => options.SignIn.RequireConfirmedAccount = true) as parameter as it pointed in the ppt.
1450
Added the Breakpoints in Controllers > HomeController.cs on line 22 and line 27 as per the ppt and run the project.
1451
Realised that i have a PHP lecture so just close the screen of the laptop and kept the project run in the background. 
2225
Started again with the debugging part from where i left.
2231
Went on Bootstrap.com to select the theme for my project and selected Vapor Theme and downloaded the bootstrap.css
2234
Changed the name on the old bootstrap file in wwwroot > lib > bootstrap > dist > css > bootstrap.css and renamed it to bootstrap_old.css and created new file called bootstrap.css.
2242
Downloaded the site.css from the blackboard which was provided by Professor.
2246
Replaced the site.css in wwwroot > css > site.css.
2250
In Views > Shared > _Layout.cshtml changed the bootstrap.min.css to bootstrap.css.
2256
Changed the nav class navbar-light to navbar-dark and bg-white to bg-primary and on line 23 removed text-dark
2302
In _loginPartial.cshtml removed all text-dark class and run the project to check the output.
2305
From the CSS_JS.txt added the css and js links.
2310
Added the code for the dropdown navbar from the slides but there was no closing div. So, i added on my own. And i commit for the first time and had a small break.
2323
Back from the break and started agian.
2325
Created all three new projects namely - PoorvaBooks.DataAccess, PoorvaBooks.Models and PoorvaBooks.Utility
2332
Copied the original data folder from the main project and pasted it in PoorvaBooks.DataAccess and deleted the original folder.
2337
Installed the following packages:
Mircosoft.EntityFrameworkCore.Relational and Mircosoft.EntityFrameworkCore.SqlServer
2342
Deleted the Migration folder from the data folder in DataAccess project and also installed the Microsoft.AspNetCore.Identity.EntityFrameworkCore and all of these versions were 5.0.11.
2345
Modified the namespace - "PoorvaBookShop.DataAccess.Data".
2350
Deleted all the Class1.cs files and Build the project successfully.
2355
Moved the Models in PoorvaBooks.Models and deleted the main one and also added the Refernces to .DataAccess and .Models main project.
2357
Renamed the Models folder to ViewModels and modified the namespace - PoorvaBookShop.Models.ViewModels.
2023-10-31
0000
Happy Halloween
0001
Tried to build project but got 3 errors in Startup.cs and 1 Error.cshtml
0006
Referred the slides and modified Startup.cs service and 'AddContext' with the using statement and 3 errors in Startup.cs got solved.
0015
Replaced the line 1 on Error.cshtml to this "PoorvaBookShop.Models.ViewModels.ErrorViewModel" and ran the project successfully.
0018
Created new SD.cs class and modified the class property and added reference to main project
0020
Also gave reference to Models and Utility project from DataAccess.
0022
Created the new Area Customer and changed route in startup.cs file outlined in ScaffoldingReadMe.txt
0024
Moved the HomeControllers.cs file to Area > Customer and deleted the Data and Model
0025
Added [Area("Customer")] on line 12 in HomeController.cs as per slides
0027
Moved Views > Home and modify the HomeController namespace and run the project but gave me different output as expected.
0028
Found the caused and copied _ViewImport and _ViewStart to Customer Area and modified the _ViewStart.cshtml to reflect the new path.
0030
Added a new Admin area in Areas and added the proper view files and delete the Data and Models folder, also deleted the Controllers folder from main project
0035
Done the last commit 

