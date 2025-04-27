![alt text](image.png)

First nmap scan on IP given

![alt text](image-1.png)

Found two ports open ssh and upnp 

On port 5000 Python Code Editor is running 
![alt text](image-2.png)


After trying many commands most of the commands are restricted but then successfully printed the global variables and globals that has sensitive data.
![alt text](image-3.png)

Finally revealed some information 

Flask Application (app = <Flask 'app'>)
Confirms this is a Python Flask web app .

Database:
SQLAlchemy with SQLite (sqlite:////home/app-production/app/instance/database.db).

After this look for users and password in the database


