# Face_attendence_engage_yash-main

(Overview to how to run the project files and do the attendence using face recognition)

In this project we are going to perform attendence using face recognition

First we gonna install pycharm and download the files from github

Now we will head on to our Pycharm project. Here we will install the required packages from the requirement.txt file.
(to know how to install the package from requirement.txt file refer video ' https://youtu.be/empqyr7vZ8o?t=173 ' from time 2:53)(we need to move the requirement.txt file into 'venv\Scripts\' folder)

after package installation delete the file in 'clicked_photo' and 'face_encoding' folder which we get after downloading the files from github.

Now run the python file(ctrl + shift + f10)

(After opening of the python file #new page)

Click option 'Generate' which will ask for the password "yash123".
  (first we need to create a database for creating table one for storing student information like name, batch, collegeid, department and second one for storing date and time with respect of collegeid and name.)
  (I store the password option so that only the authority has the access to create the database. For changing the password Visit line 378)

Now we gonna click 'Start Student Enrollment' option for storing student data and face
(after clicking the option you can see the options like 'Enter name of person', 'Enter college id', 'Enter batch', 'Enter department', Now click save.  After you can click the 'Enroll the image' option for storing the image.) 

After enrolling all the face we can start the 'Start Attendence' option to start the attendence (press q to close the video). We can see the person Name written on the screen only one time so that multiple data of same person can be avoided. Now we can check all the student timing in the database in the 'present_student_table.

if we want to reset we can click the reset all the things button

In the end we can send the database to anyone by entering its email in the right corner box.
