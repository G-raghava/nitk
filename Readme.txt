A replication of https://www.nitk.ac.in/

Software Requirements : Browser : Google Chrome,Mozilla Firefox
 Code Editor:Pycharm
 Version Control : Github for Desktop.
 Technology Stack : Frontend : HTML, CSS, Jinja 2 Templates 
Backend : Python Flask Framework.
 Database : SQLAlchemy - A Python SQL toolkit

Directory Structure - The Main Folder named Nitk_website Contains 2 subfolder : nitk_cse,venv and 2 files : readme.md and run.py
Within nitk_cse we have 3 folders : 
1)static - containing images, scripts and stylesheets
2) templates - containing HTML pages
3) pycache : containing python logs. 
Nitk_cse also contains 5 files : 
1)init.py : Python file contains various flask library imports. 
2)forms.py : Python file contains all forms displayed in HTML.
3) models.py : Python file contains all database models(i.e. tables) 
4)routes.py : Python file contains all routing information from forms to database. 
5)site.db : The SQL Database binary file.
Within venv:We have all the imported packages infromation.

Here,we run the 'run.py' in the pycharm with the installed packages like flask,wtfoems,sqlalchemy,etc.
Then we get the link as http://127.0.0.1:5000/,where we can access all the pages.
For login---There are two type of login:
               a)student login---can view and update their profile.
               b)faculty login----can view and update their profile over the site.
              
Login page for Student are with credentials:raghav@nitk.edu.in,Password:78910.
Login page for Faculty are with credentials:alwyn@nitk.edu.in,Password:123456.
