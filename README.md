# NatureBlog 1.0 - Django Blog Application

This is a Blog Web Application, written in <strong>Django 3</strong>. 

<strong>This application allows the creation and publication of posts</strong>. The posts are listed in the main layout, and it's possible to see the Title, the Published Date, and a small part of their Text Content. By clicking on the Post's Link you are interested in, you can see all of its content.

![Image-Intro-Webapp](images/image_intro.png)

 ## Table Of Contents

 * General Info
 * Technologies
 * Setup
 * Status
 
 ## General Info
 


![Image-Intro-Webapp](images/image_blog_layout1.png)

 ## Technologies Used

  ### Languages Used

  * [Python3](https://en.wikipedia.org/wiki/Python_(programming_language))
  * [HTML5](https://en.wikipedia.org/wiki/HTML5)
  * [CSS3](https://en.wikipedia.org/wiki/CSS#CSS_3)
  * [SQLite](https://en.wikipedia.org/wiki/SQLite)

  ### Frameworks, Libraries & Programs Used

  1. [Django3](https://en.wikipedia.org/wiki/Django_(web_framework))
  2. [SASS](https://en.wikipedia.org/wiki/Sass_(stylesheet_language))
  3. [Google Fonts](https://en.wikipedia.org/wiki/Google_Fonts)
  4. [Git](https://en.wikipedia.org/wiki/Git)
  5. [GitHub](https://en.wikipedia.org/wiki/GitHub)


 ## Setup

  To run this project on your machine you should use a <strong>Virtual Enviroment</strong> with <strong>Django3</strong> installed. It's necessary to have also <strong>Python3</strong> installed.

  It's recommended to follow the instructions below:
  
  ### Check Python Version/Install Python3

  1. Check if you have <strong>Python3</strong> installed. Open the Terminal and type:
  ```bash
  python3
  ```

  You should get an output that shows you the Python version installed on yous OS. In case you don't get nothing check this guide to install the last version of Python3 [Python.org/downloads](https://www.python.org/downloads/)

  ### Install the Virtual Enviroment

  1. After that you installed Python3. Create and empty folder in your machine:
  ```bash
  mkdir django_projects
  ```

  2. Go inside the folder and install the <strong>Virtual Enviroment</strong>:
  ```bash
  python3 -m venv my_env
  ```  

  3. Activate the <strong>Vitual Enviroment</strong>:
  ```bash
  source my_env/bin/activate
  ``` 
  Whenever you would like to <strog>deactivate</strog> the <strong>Virtual Enviroment</strong>, type:
  ```bash
  source my_env/bin/deactivate
  ``` 

  ### Install Django3 Framework in the Virtual Enviroment with pip

  (With Python3 <strong>pip</strong> package manager comes installed. It's recommended to use <strong>pip3</strong>)

  1. Install <strong>Django3</strong>:
  ```bash
  pip3 install "Django==3.0.*"
  ```  

  2. <strong>Check that Django3 it's been successfully installed</strong>:
  ```bash
  python3
  >>> import django
  >>> django.get_version()
  '3.0.14'
  ``` 
  
  ### Run the Application on the Server

  1. Download the NatureBlog Project's Folder from this GitHub Account;
  2. Put this folder inside you Remote Django Projects folder in you machine (where you installed the Virtual Enviroment);
  3. Be sure that the Virtual Enviroment is active (you should see <strong>(my_env)</strong> next to your bash username on the Terminal);
  4. <strong>Follow these steps to run the project on the Server</strong>:

   1. Go inside <strong>the nature_project folder</strong>:
   ```bash
   cd nature project
   README.md blog db.sqlite3 images manage.py nature 
   ```

   2. Run the Server with Django <strong>runserver</strong> command
   ```bash
   python3 manage.py runserver
   Watching for file changes with StatReloader
   ``` 

   ```bash
   System check identified no issues (0 silenced).
   February 19, 2022 - 12:20:00
   Django version 3.0.14, using settings 'nature.settings'
   Starting development server at http://127.0.0.1:8000/
   Quit the server with CONTROL-C.
   ```

   3. Copy the <strong>URL address</strong> you'll obtain on your Browser's navbar, adding the <strong>blog/</strong> path:

   ![url_image](images/url_path.png)



