# Overview

A web portal which facilitates online booking of doctors it has features like 
showing availability of doctors, number of free slots and booked slots, patients
can view their profile edit their profile etc. All schedules and data can be modified 
by the Admin and doctors can manage their details and appointments..

## Description

The portal is hepful for any hospital who has a large number of clients, It has 
been mainly divided into two modules one is admin and another is user, Admin
can see the patient details can modify them, similarly admin can edit doctor details 
and make changes to them also admin can manage appointments, through this portal 
clients can register themselves in the hospital, they can see the availability of the 
doctors along with date and time, they can book their slot etc, it saves their time and 
travelling expenses.

## Possible Approaches

One way to design this portal is by using PHP, Mysql at backend and HTML,CSS,
Bootsrap at frontend.
We can also use Djando python framework (which is mainly based on HTML and python)
to design this portal.
There are many more technologies that can be used for this purpose.

##My Approach

To design this portal I used:
#At server side:
PHP
Mysql database
#At Cliend side:
HTML,CSS,Javascript
Bootstrap 4
jQuery

##Key Learnings

Usage of HTML,CSS and Bootstrap framework in frontend development.
Usage of PHP and Mysql at backend.
Establishing a connection between frontend and backend. 

#Folders and Files:
                   
                   Admin folder:Contains all source code files related to admin module.
                                     appointment: It is a php source code file, helps admin to view all
                                                              scheduled appointments.
                                     appointment_action: It contains source code for the search button which 
                                                                        retrieves all records within two given dates.
                                     dashboard: dashboard displays total number of appointments in recent days.
                                     doctor: This file contains source code of the module through which admin can
                                                   add, modify and remove doctors from the database.
                                     doctor_action: This file contains source code through which admin adds new
                                                                   add a doctor.
                                     doctor_profile: A source code file helps in editing doctor details.
                                     doctor_schedule: A source code file helps in editing doctor schedules.
                                     login: source code file contains source code of login page.
                                     login_action: Source code file of login button to authenticate admin from 
                                                             the database.
                         CSS folder:  Contains all stylesheets used in project.
                        Class Folder:  Contains php classes used in project.
                        SCSS folder : contains all scss files used in the project.
                        Bootstrap folder: Contains Bootstrap tools used in project. 
                        appointment.php file :This file helps to dispaly the total appointments taken by a a patient.
                        login.php file: A source code file, It redirects a patient to the dashboard afetr successful 
                                           authentication.
                        logout.php file: A source code file, It redirects a patient to the login page.
                        register.php file : A source code file It helps new users to get registered.
                        Index.php: A source code file, It open the dashboard for the patients where they can
                                   see the availability of doctors.
                        navbar.php : A source code file, It displays the navigation bar on the appointment page.
                        profile.php : A source code file displays user profile, user can edit his profile as well.
                        verify.php : A source code file helps user to verify their email and once verified reflect it
                                     to the database.
                        download.php : A source code file helps to download report in pdf form.
                        footer.php : A source code file contains code for the footer.
                        header.php : A source code file contains code for the header.
                        

#Further Work

To be added some attractive features like online payment spported with various payment methods, making it
more attractive by adding more styles to make it look more user friendly.
An android app is to be developed for the same web portal so that It can be made more convenient for the patients
to connect where they do not need to login again and again like in web browser.
                  
                     


                         
              

