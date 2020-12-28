488 Project

This project was built in Visual Studio and should be opened/run through Visual Studio.

To open and prep for running:
	-Make sure Visual Studio is installed
	-Extract All .zip folder contents to your Desktop
	-Inside the folder, follow this path and open the solution -- "488Project-master > 488Project > HospitalWebApp.sln"
	-Once Visual Studio loads everything, find in Default.aspx in Solution Explorer, right click and select "Set as Start Page"
	-Right click the project name "HospitalWebApp" at the top of Solution Explorer, select Rebuild

To run:
	-Go to the Toolbar at the top of Visual Studio and find the green Play button (it might say "IIS Express <web browser>")
	-Left click this tool and it should load in the specified web browser
	-Once on the Login webpage use these for logins:
		-Patient (Username: bob.ross   	Password: bobross123)
		-Doctor  (Username: jane.doe	Password: janedoe123)

Troubleshooting:
	-If you get a server error that says it can't find /Default.aspx right after running the project, there are a couple things you can try:
		-Find in Default.aspx in Solution Explorer, right click and select "Set as Start Page"
		-Right click the project name "HospitalWebApp" at the top of Solution Explorer, select Rebuild
		-Right click the Solution Name at the top of Solution Explorer, select Rebuild
		-Close Visual Studio and reopen the Solution

	-If you can't login using either provided user information, the Database is not correctly connected and refer to the demonstration video if video is
	provided to see the application.
