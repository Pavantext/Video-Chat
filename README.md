# A Simple Video Chat Room
 A learning based Django video conference web app. Learn a basic implementation of Django concepts

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

- register Page
- login Page
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
Third-Party : `ZEGOCLOUD UIkit`
<br/><br/>
Database: `Sqlite3`
<br/><br/>

<br>

### Installation

  ## Prerequisites
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
   source env/Scripts/activate
   ```

   If you are giving a different name than `env`, mention it in `.gitignore` first
   
3. Make migrations/ Create db.sqlite3

   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

4. Create a super user.
   This is to access Admin panel and admin specific pages.

   ```djangotemplate
   python manage.py createsuperuser
   ```
   
   Enter your username, email and password.
   
5. Run server
   ```bash
   python manage.py runserver

  
###Snapshots


  

  
