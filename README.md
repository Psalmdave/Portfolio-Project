# <p align='center'>Animation Library </p>

<p align ='center'>
  <img src="https://res.cloudinary.com/dc29czhf9/image/upload/v1660175087/image/logo_tohji9.png" width="200" height="100">
</p>
This project provides an easy to use guide to developers, precisely beginners, on how to add animations to the several elements on their webpage(s). In essence, we try to avoid the hassle of a developer trying to think critically on how they can create or add animations to their webpage.

[live preview]([https://group100animo.herokuapp.com/](https://drive.google.com/file/d/1ng2urGV5zLYb9ucTU7pN1bzclbIDxnd5/view?usp=sharing))

## Acknowledgements

- [proj-anima-lib Team 100](#)

## Tech Stack

**Design:** Figma <img src="https://res.cloudinary.com/dc29czhf9/image/upload/v1659109673/Figma-logo_pw2gqg.svg" width="20" height="20">

**Client:** HTML, CSS, JavaScript and Bootstrap.

**Server:** Python, Django (web framework).

**Database:** MySQL.

**Project Management and Version Control:** Github

## Optimization

We converted both files (css and js) of the library to a zip file. The essence of this is to compress both files to a small size, before they are being saved to the client's local computer.

## Installation

To install the project to your local computer or server.
Clone into a directory in your computer using:

```bash
git clone https://github.com/zuri-training/anima_lib_team-100.git
```

change directory to the project folder created after cloning.
For window users use the command provided below.

For other Operating System Users, Kindly follow online documentation or guide on how to change directory.

```bash
cd <directoryname>
```

Creating a virtual environment (this is optional but advisable).

For window users use the command below. If created successfully, activate the virtual environment.
For other Operating System Users, kindly follow online documentation or guide on how to install and activate your virtual environment.

```bash
virtualenv <virtualenvironmentname>
```

Install the required packages, using:

```bash
pip install -r requirements.txt

or

pip3 install -r requirements.txt
```

Run migrations to prepare the models or table to be added to the database, using:

```bash
python manage.py makemigrations
```

Migrate your tables to the database, using:

```bash
python manage.py migrate
```

Finally, you can run your server using:

```bash
python manage.py runserver
```

## Features

NOTE: A majority of our features are provided for only authenticated users. Hence, you need to have registered and logged in to the web application to enjoy these features.

- Interactive documentation showing various animation samples.
- View User(s) comment about our product (every user can enjoy this)
- User interaction via posting comments (for only logged in users)
- Animation library downloadable as zip file. (for only logged in users)

## Usage/Examples - How to use library to add nice animation to your web page.

When you are referencing the code on our server. That is,when you want to embed a link that points to the css and js on our server.

```html
<html>
  <head>
    <meta charset="utf-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <title>page title</title>
    <meta name="description" content="" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />

    <link rel="stylesheet" href="code_link_to_server" />
  </head>
  <body>
    <tagname class="animation"></tagname>

    <script src="code_link_to_server"></script>
  </body>
</html>
```

When you have downloaded the animation library on your computer

```html
<html>
  <head>
    <meta charset="utf-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <title>page title</title>
    <meta name="description" content="" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <link rel="stylesheet" href="path_to_style.css" />
  </head>
  <body>
    <tagname class="animation"></tagname>

    <script src="path_to_script.js"></script>
  </body>
</html>
```

## Contributors

```bash
Miracle Achumba (miracleachumba@gmail.com)
Raphael Sajimi (raphaelemerald2002@gmail.com)
