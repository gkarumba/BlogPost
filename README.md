# BLOGPOST

## Description
#### This is a web application that allows users to express themselves using a blog posts. They they first create an account then log in to start creating blogs..
#### By **gkarumba**
##[Live Site](https://gkarumba-blogpost.herokuapp.com/)
The user can:
* See various blog posts
* View blogposts they like
* See the latests posts
* Subscribe to latest post service
## Setup/Installation Requirements
### Prerequisites
* python3.6
* pip
* Virtual environment(virtualenv)

### Cloning and running
* Clone the application using git clone(this copies the app onto your device). In terminal:

          $ git clone https://github.com/gkarumba/blogpost.git
          $ cd blogpost

* Creating the virtual environment

          $ python3.6 -m venv --without-pip virtual
          $ source virtual/bin/env
          $ curl https://bootstrap.pypa.io/get-pip.py | python

* Installing Flask and other Modules

          $ python3.6 -m pip install Flask
          $ python3.6 -m pip install Flask-Bootstrap
          $ python3.6 -m pip install Flask-Script
          $ python3.6 -m pip install -r requirements.txt

* Run the application:

          $ chmod a+x start.sh
          $ ./start.sh
### Testing the Application
* To run the tests for the class files:

          $ python3.6 manage.py test

## Technologies Used
* Python 3.6
* Flask
## Behaviour driven development/ Specifications

| Behaviour |  Sample Input | Sample Output |
| :---------------- | :---------------: | :------------------ |
| Display latest blogs | On page load | List of various blogs I have written |
| Registration | Submit regitration form | User creates an account and receives welcome email |
| Subscription | Submit subscription form| User receives email eb=very time there is a new post|
| Edit posts(writer) | Submit edit post | The post is updated with new data from user |
| Delete posts(writer) | Click delete post | Post is deleted |
| Delete comments(writer) | Click delete comment | Comment is deleted |

## Support and contact details
For any questions, troubleshooting or contributions,  find me on:
* Email: gachegua@gmail.com
### License
MIT License
Copyright (c) {2019} [gkarumba](https://github.com/gkarumba/BlogPost/blob/master/LICENSE)
