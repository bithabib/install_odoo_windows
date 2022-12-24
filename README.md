# Install Odoo Windows
Download all the necessary software:
PyCharm -  https://www.jetbrains.com/pycharm/download/#section=windows
Visual Studio - https://visualstudio.microsoft.com/
Anaconda - https://www.anaconda.com/products/distribution#windowsa
PostgreSQL - https://www.enterprisedb.com/downloads/postgres-postgresql-downloads
Also need to download Odoo15 sourch code from github - https://github.com/odoo/odoo.git

Note: 
# When installing visual studio you have to tick c ++ & node Js. 
# Extract odoo15 Zip file in Desktop.
# PostgreSQL Passwords and database name must be kept in mind when installing.
           (E.g. - Name: odoo15 , Password: odoo15)



Now go to PyCharm and open the odoo15 folder. 
We need to add interpreter. So click on add interpreter.
Now must go to conda environment. Need to setup location in new environment.                                                                                     ( E.g. - user/user/anaconda3/envs/odoo15 )
Select python version 3.7
Click on OK
Now open anaconda prompt and enter the commands -

>activate odoo15

>cd Desktop

>cd odoo-15.0

>pip install -r requirements.txt
Note: 
# If you see any error during pip installation, you will find the error in the requirements.txt file and delete it. Then you have to install the pip again.
# Else follow next steps.


Now let's go to pg admin4
Enter the password
Click on server. and again enter the password  
Right click on Login/Group and create Login/Group 
Enter name (e.g. odoo15) & save, Click Defination and define password(e.g. odoo15). Now turn on everything in privilege.


Now go to PyCharm 
Copy the odoo.conf file from the debian folder of odoo15 and paste it into odoo15 folder. 
Go to odoo.conf and change db_user (e.g. odoo15) and db_password (e.g. odoo15)
Now you need to add configaretion -

Name - E.g. odoo15
Scriptpath - Select odoo-bin file location (E.g. User/user/Desktop/odoo-15.0/odoo-bin)
Parameter - -c odoo.conf


After finish all setup process ,run odoo15 source code 

Allow access 
Copy this local host and paste it in your browser.
Now fill the form with the required information.


Follow our YouTube video to understand better - 

Download all the necessary software:
PyCharm -  https://www.jetbrains.com/pycharm/download/#section=windows
Visual Studio - https://visualstudio.microsoft.com/
Anaconda - https://www.anaconda.com/products/distribution#windowsa
PostgreSQL - https://www.enterprisedb.com/downloads/postgres-postgresql-downloads
Also need to download Odoo15 sourch code from github - https://github.com/odoo/odoo.git

Note: 
# When installing visual studio you have to tick c ++ & node Js. 
# Extract odoo15 Zip file in Desktop.
# PostgreSQL Passwords and database name must be kept in mind when installing.
           (E.g. - Name: odoo15 , Password: odoo15)



Now go to PyCharm and open the odoo15 folder. 
We need to add interpreter. So click on add interpreter.
Now must go to conda environment. Need to setup location in new environment.                                                                                     ( E.g. - user/user/anaconda3/envs/odoo15 )
Select python version 3.7
Click on OK
Now open anaconda prompt and enter the commands -

>activate odoo15

>cd Desktop

>cd odoo-15.0

>pip install -r requirements.txt
Note: 
# If you see any error during pip installation, you will find the error in the requirements.txt file and delete it. Then you have to install the pip again.
# Else follow next steps.


Now let's go to pg admin4
Enter the password
Click on server. and again enter the password  
Right click on Login/Group and create Login/Group 
Enter name (e.g. odoo15) & save, Click Defination and define password(e.g. odoo15). Now turn on everything in privilege.


Now go to PyCharm 
Copy the odoo.conf file from the debian folder of odoo15 and paste it into odoo15 folder. 
Go to odoo.conf and change db_user (e.g. odoo15) and db_password (e.g. odoo15)
Now you need to add configaretion -

Name - E.g. odoo15
Scriptpath - Select odoo-bin file location (E.g. User/user/Desktop/odoo-15.0/odoo-bin)
Parameter - -c odoo.conf


After finish all setup process ,run odoo15 source code 

Allow access 
Copy this local host and paste it in your browser.
Now fill the form with the required information.


Follow our YouTube video to understand better - 

Download all the necessary software:
PyCharm -  https://www.jetbrains.com/pycharm/download/#section=windows
Visual Studio - https://visualstudio.microsoft.com/
Anaconda - https://www.anaconda.com/products/distribution#windowsa
PostgreSQL - https://www.enterprisedb.com/downloads/postgres-postgresql-downloads
Also need to download Odoo15 sourch code from github - https://github.com/odoo/odoo.git

Note: 
# When installing visual studio you have to tick c ++ & node Js. 
# Extract odoo15 Zip file in Desktop.
# PostgreSQL Passwords and database name must be kept in mind when installing.
           (E.g. - Name: odoo15 , Password: odoo15)



Now go to PyCharm and open the odoo15 folder. 
We need to add interpreter. So click on add interpreter.
Now must go to conda environment. Need to setup location in new environment.                                                                                     ( E.g. - user/user/anaconda3/envs/odoo15 )
Select python version 3.7
Click on OK
Now open anaconda prompt and enter the commands -

>activate odoo15

>cd Desktop

>cd odoo-15.0

>pip install -r requirements.txt
Note: 
# If you see any error during pip installation, you will find the error in the requirements.txt file and delete it. Then you have to install the pip again.
# Else follow next steps.


Now let's go to pg admin4
Enter the password
Click on server. and again enter the password  
Right click on Login/Group and create Login/Group 
Enter name (e.g. odoo15) & save, Click Defination and define password(e.g. odoo15). Now turn on everything in privilege.


Now go to PyCharm 
Copy the odoo.conf file from the debian folder of odoo15 and paste it into odoo15 folder. 
Go to odoo.conf and change db_user (e.g. odoo15) and db_password (e.g. odoo15)
Now you need to add configaretion -

Name - E.g. odoo15
Scriptpath - Select odoo-bin file location (E.g. User/user/Desktop/odoo-15.0/odoo-bin)
Parameter - -c odoo.conf


After finish all setup process ,run odoo15 source code 

Allow access 
Copy this local host and paste it in your browser.
Now fill the form with the required information.


Follow our YouTube video to understand better - 
http://3.239.37.196:8069/blog/odoo-4/odoo-installation-process-in-windows-50
