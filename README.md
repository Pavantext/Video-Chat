# A Simple Video Chat Room
 A learning based Django video conference web app. Learn a basic implementation of Django concepts
 I have Deployed the project.

 you can visit the  [site here](https://pavanonline.pythonanywhere.com/) to test project

<br>

<p align="center">
<a href="https://codeclimate.com/github/pkini2002/Social-media-web-app/maintainability">
<img src="https://api.codeclimate.com/v1/badges/b79b9943a5cb4340c05f/maintainability" /></a>
<a href="https://codeclimate.com/github/pkini2002/Social-media-web-app/test_coverage">
<img src="https://api.codeclimate.com/v1/badges/b79b9943a5cb4340c05f/test_coverage" /></a>
</p>

<p align="center">
<a href="https://www.python.org/"><img src="https://forthebadge.com/images/badges/made-with-python.svg" border="0" title="Made with Python" />
</p>

<p align="center">
<a href="http://www.djangoproject.com/"><img src="https://www.djangoproject.com/m/img/badges/djangopowered126x54.gif" border="0" alt="Powered by Django." title="Powered by Django." /></a>
</p>


<br>

### Pages

- Register Page
- Login Page
- Dashboard Page
- Meeting Page
- Index Page
- Join Room Page
- Video Room Page

  
<br>

### Features
- video chat functionality using ZEGOCLOUD
- Customizing user video and audia on/off buttons
- Personal Chat room
- Joining via link
- Max upto 50 users

<br>

### Tools and Techs

Backend Framework: `Django`
<br/><br/>
Front-end : `Bootstrap, HTML, CSS`
<br/><br/>
Third-Party : `ZEGOCLOUD UIkit/SDK`
<br/><br/>
Database: `Sqlite3`
<br/><br/>

<br>

## Installation

  ### Prerequisites
  - Python == 3.12.x
  - Django == 5.x
  - ZEGOCLOUD UIkit
    
<br>

### Setup
1. - Fork the [repo](https://github.com/Pavantext/Video-Chat)
   - Clone the repo to your local system
     
   ```git
   git clone https://github.com/Pavantext/Video-Chat.git
   cd VideoConference
   ```
   Make sure you have python installed on your system.
   <br>
2. Create a Virtual Environment for the Project

   If u don't have a virtualenv installed

   ```bash
   pip install virtualenv
   ```
   **For Windows Users**
   ```bash
   virtualenv env
   env/Scripts/activate
   ```

   **For Linux Users**
   ```bash
   virtualenv env
   source env/bin/activate
   ```

   If you are giving a different name than `env`, mention it in `.gitignore` first
      <br>
3. Make migrations/ Create db.sqlite3

   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```
   <br>
4. Create a super user.
   This is to access Admin panel and admin specific pages.

   ```djangotemplate
   python manage.py createsuperuser
   ```
   
   Enter your username, email and password.
      <br>
5. Run server
   ```bash
   python manage.py runserver
   ```
<br>


### Snapshots

1. Register Page

![Screenshot (16)](https://github.com/user-attachments/assets/0d88fc5a-3fe9-40da-9485-dbdba76dcc1f)

   <br>
   
2. Login Page

![Screenshot (15)](https://github.com/user-attachments/assets/1984a8ce-efd7-422c-b3f1-fe810814373c)

   <br>
   
3. Dashboard Page

![Screenshot (17)](https://github.com/user-attachments/assets/896bf382-10ae-4c1d-9783-e5e68c41763b)

   <br>
   
4. Meeting Page

![Screenshot (18)](https://github.com/user-attachments/assets/93133d9d-51af-41e4-b569-aa4454bdba29)

![Screenshot (19)](https://github.com/user-attachments/assets/90e68bf6-0647-43ae-822f-941acce090ca)

   <br>
   
5. Index Page

![Screenshot (14)](https://github.com/user-attachments/assets/051b3fc2-facf-4483-b95a-6c7b0b5e7304)

   <br>
   
6. Join Page

![Screenshot (20)](https://github.com/user-attachments/assets/b6c84956-2e94-458d-a626-78eed18139e1)

 

