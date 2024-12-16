# django-Hello-World
_Getting started with django framework of python._

Printing Hello, World!.

## setting up a django project
_Things that I've did after installing django framework._

Using commands like **django-admin startproject** & **startapp** to set up the project and app folders.

## codes at the editor
_<> codes._

**settings file:** Updating the installed apps, after creating an app. Here, I'm naming the app as 'sayhello'.

![setting.py](https://github.com/santhosh-a11y/django-Hello_World-/blob/e961738802d31f62f451cddfac560eb78f861466/img/Screenshot%202024-12-15%20220846.png)


**views file:** Importing Httprespode from django. Defining a function named hello for a request through which Hello, World! is returned as a response.


![views.py](https://github.com/santhosh-a11y/django-Hello_World-/blob/e961738802d31f62f451cddfac560eb78f861466/img/Screenshot%202024-12-15%20221239.png)


**url file:** Creating an urls file at the app folder. This file imports path and views. Ater this, the urls file at the project folder is updated. This is where I include my sayhello app.


![app's_url](https://github.com/santhosh-a11y/django-Hello_World-/blob/e961738802d31f62f451cddfac560eb78f861466/img/Screenshot%202024-12-15%20221559.png)
![project's_url](https://github.com/santhosh-a11y/django-Hello_World-/blob/e961738802d31f62f451cddfac560eb78f861466/img/Screenshot%202024-12-15%20221613.png)


**runnig the server:** Using the **runserver** command.


![cmd_prompt](https://github.com/santhosh-a11y/django-Hello_World-/blob/e961738802d31f62f451cddfac560eb78f861466/img/Screenshot%202024-12-15%20221709.png)



## Output
_at the web_

**Hello, World!** is displayed.


![at_web](https://github.com/santhosh-a11y/django-Hello_World-/blob/e961738802d31f62f451cddfac560eb78f861466/img/Screenshot%202024-12-15%20221756.png)






