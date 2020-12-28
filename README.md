Upload Using Visual Studio
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

	-If you can't login using either provided user information, the Database is not correctly connected and refer a demonstration video that might be
	provided to see the application.


# CSCI488_doctor_appointment
For this project we were Working with a project design emphasis, a doctor and patient appointment website was created. For this project we used visual studio as our IDE. The doctor and patient appointment had slightly different functions/roles. Each patient and each doctor had their own account. This site helped doctor and patient communication enabling them to send messages, create appointment and keep notes. The patient was able to send a message to their doctor and keep that message saved similar to an inbox, additionally the patient could make an appointment and that date would be saved and the patient could make make changes like deleting the appointment and so on with some other functions and doctors having a lightly more functional account.
