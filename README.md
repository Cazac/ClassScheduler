# Projects - KPU Class Scheduler (2017)

The KPU Class Scheduler project receives and auto-sorts input from a database to schedule classes for students based off a defined rule set.

CURRENT DATABASE IS OFFLINE 
(SQL Code is provided if you which to re-create the database though!)


- BASICS
-------------------------------------------------------------------------------------------
- Run the "Builds/MLSG - Chess Demo" to start the application
- Hit the "esc" key to close application
- C# Source code files can be found under "MLSG-Chess-Demo\MLSG - Chess Demo\Assets\Scripts"
-------------------------------------------------------------------------------------------

- INFORMATIONAL STRUCTURE
-------------------------------------------------------------------------------------------
●	Stores the following data:
  ○	Classroom Information
■	Campus
■	Building
■	Room Number
■	Classrooms with Desktop PCs
  ○	Semester -- year and season
  ○	Course info
■	Course Name
■	Course ID
■	Program
■	Course year (ie. 1st, 2nd, 3rd, 4th)
■	PC Required in Classroom (Required/Not Required)
  ○	Instructor
■	First, Last Name
■	KPU Staff ID
  ○	Section
■	CRN
■	Section ID
  ○	Schedule
■	Day of Week
■	Course Time Slots


- SORTING RULES
-------------------------------------------------------------------------------------------
○	Each faculty member will have a list of courses they can teach
○	Each faculty member is constrained to a maximum of 4 sections per semester
○	Each faculty is limited to teaching a maximum of 2 class per day
○	3rd and 4th year classes can only be offered after 4pm
○	Different sections of the same course cannot be offered in the same time block

-------------------------------------------------------------------------------------------

Project by: 	Zachary Blouin

Source Code: 	https://github.com/Cazac/ClassScheduler
