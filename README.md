# <div align="center">**You Won't Find A Better City!**</div> 
<br>
First and foremost my partner and I would like to thank you for your time and consideration, as you allow us to take you on a journey through America's only city worth talking about. Enjoy!

The journey begins with an introduction and a list of the five boroughs that make New York City. Once you've selected the borough of your desire, you're then taken to a list of activites of that particular borough. From there you'll make a decsion, but there's no harm in looking at them all, you wont regret it. Then you open the door and the first thing you see is a wonderfull image representing that venue you've choosen along with a brief description. Its only brief so you can then add and make it your own. If you have time live a little return home utilizing the *Return Home* link and see all that the five boroughs have to offer. After all it doesnt get any better than NYC!
<!-- The README.md must contain the following information

    Name of project
    Names of group members and their Github usernames
    Instruction on how to create and run a virtual environment using venv
    Instruction on how to install project dependencies with pip
    Instruction on how to run the Django application -->

<!-- group names -->
[Brandon Grant GitHub](https://github.com/Grantb2134) 
 
[Jason Rolle GitHub](https://github.com/JasonRolle1990) 
<br>
<br>
<br>



## <div align="center">***How To Create And Run A Virtual Environment***</div>
---
<br>

* In your terminal enter **mkdir** to make a new directory. This makes a new folder for the environment your going to create.
* Then enter **python3 -m venv (name of environment)** to create a new virtual environment.
* After that you want to enter **source (name of environment)/bin/activate** on Unix/MacOS or **(name of environment)\Scripts\activate.bat** on Windows to activate the virtual environment. 

>##### *please note where you see (name of environment) its litteraly the name of your environment minus the parenthesis*

<br>
<br>
<br>

## <div align="center">***How To Install Dependencies With Pip***</div>
---
<br>
Once you have compleated the steps above your now able to continue with the steps below.

* Enter **pip install django** to install Django
* Then enter **pip install -r requirements.txt**
* It would be good to do a *sanity* check after by entering **pip freeze** This prompt shows all project dependencies installed.  Just to make sure everthing is in order to move forward.

<br>
<br>
<br>

## <div align="center">***How To Run The Django App***</div>
---
<br>
Now that your virtual environment is created and up and running and Django is installed. Your now ready to create a Django project and application.

First you want to create the project
* Enter **django-admin startproject (the name of your project)**

Then you want to enter the folder of the project you just created.
* **cd (the name of your project)**

Then you want to run the server
* Enter **python manage.py runserver** when you go to the local host in your browser *localhost:8000* you should see the pic below.
>>![](https://i.imgur.com/5jaC2y7.png)

Once you have the server running you can now create an app.
* Enter **python manage.py startapp (the name of your app)**

Its best for you then to register your new app with your project. From your explorer in VS Code you want to navigate to the name of your project. In that folder you'd see **settings.py** enter the python script. In your editor you want to add it to the installed apps portion.
*       INSTALLED_APPS= [
        '(app name).app.(AppnameConfig)'],
        *It's important that the first letter is uppercase as well as the 'C' in config.
    
At this point you should be in sync with the project you created. Now you can migrate the database.
* Enter **python manage.py migrate**

Then you need to create a *superuser* this would allow you to utilize the admin page. Which allows you to review the data in your database. 
* Enter **python manage.py createsuperuser**
Follow the prompt, create a username and password
















