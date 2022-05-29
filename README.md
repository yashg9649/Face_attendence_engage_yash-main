# Face_attendence_engage_yash-main
note1 - install python and pip for running this project.
note2 - To open the database online database opener can be used. Link - ( https://inloop.github.io/sqlite-viewer/ )

(Overview to how to run the project files and do the attendence using face recognition)

In this project we are going to perform attendence using face recognition

1) First we gonna clone the files from github
Please remember to install the git files in the same folder which contain python and pip

2) after then make ensure to delete the file in 'clicked_photo' and 'face_encoding' folder which we get after downloading the files from github.

3) now open command prompt for installing the required packages from requirement.txt
(first go in the requirement.txt folder usind cd command then run the 'pip install -r requirement.txt' , it will install all the required packages) 

4) Now run the python file using command 'python smart_attendance.py'

(After opening of the python file #new page)

5) Click option 'Generate' which will ask for the password "yash123".
  (first we need to create a database for creating table one for storing student information like name, batch, collegeid, department and second one for storing date and time with respect of collegeid and name.)
  (I store the password option so that only the authority has the access to create the database. For changing the password Visit line 378)

6) Now we gonna click 'Start Student Enrollment' option for storing student data and face
(after clicking the option you can see the options like 'Enter name of person', 'Enter college id', 'Enter batch', 'Enter department', Now click save.  After you can click the 'Enroll the image' option for storing the image.) 

7) After enrolling all the face we can start the 'Start Attendence' option to start the attendence (press q to close the video). We can see the person Name written on the screen only one time so that multiple data of same person can be avoided. Now we can check all the student timing in the database in the 'present_student_table.

if we want to reset we can click the reset all the things button

8) In the end we can send the database to anyone by entering its email in the right corner box.
(for now you will get the mail from email - 'ygarg042005@gmail.com')
