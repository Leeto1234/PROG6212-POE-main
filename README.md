How to run the project 

. Install Visual Studio
   If you haven’t installed Visual Studio, download it from [here](https://visualstudio.microsoft.com/). Make sure to select the workload for ASP.NET and web development during installation.

 2. Create a New MVC Projec
   - Open Visual Studio.
   - Select File > New > Prog MVC Part 2
   - In the "Create a new project" window, search for ASP.NET Core Web App (Model-View-Controller) or ASP.NET Web Application (.NET Framework) (depending on whether you're using .NET Core or .NET Framework).
   - Choose the appropriate template and click Next.
   - Name your project and specify a location, then click Create.

   If you're opening an existing MVC project:
   - Go to File > Open > Project/Solution and browse to the project's location.

 3. Configure Startup Project
   - In Solution Explorer, right-click your project and select Set as Startup Project if it isn’t already.

 4. Select Debug or Release Mode
   - At the top of Visual Studio, choose Debug or Release mode from the dropdown. Debug is useful for development and troubleshooting.

 5. Check Dependencies
   Ensure that all necessary NuGet packages and dependencies are installed. For example, ensure you have Microsoft.AspNetCore.Mvc or System.Web.Mvc packages, depending on the type of MVC project you are using.
   - Right-click on the Dependencies folder or References in the Solution Explorer.
   - Select Manage NuGet Packages and install any missing packages if necessary.

 6. Run the Project
   - At the top of Visual Studio, click the Start button (green triangle) or press F5.
   - Select a browser from the dropdown next to the Start button if you prefer a specific browser for testing.

 7. View in Browser
   - Once the application is built, it will open in your default browser.
   - The application will run on a local development server (usually on localhost), and you can interact with the MVC components (views, controllers, models).

 8. Troubleshooting
   If the project doesn't run:
   - Check the Output Window or Error List in Visual Studio for build errors.
   - Ensure that you have the correct SDK and Runtime installed for the version of .NET or .NET Core you're using.

