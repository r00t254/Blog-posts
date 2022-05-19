# Blog-posts
# Author
Mary Auma
# Description
This is a flask application that allows writers to post blogs, edit and delete blogs.It also allows a person to subscribed to recieve email everytime a new blog is posted by a writer.
# Live Link

# User Story
.A user sees random quotes on the site

.A writer can create a blog from the application and update or delete blogs I have created.

.A user should an email alert when a new post is made by joining a subscription.

.Register to be allowed to log in to the application

.A user can view the most recent posts.

.View and comment the blog posts on the site.

# Developments
Running the application

python3.8 manage.py server

start.sh
# Technology  Used
Python3.8
Flask 
Heroku
# BDD
Behaviour'''''	Input'''''''	Output
Load the page	  On page load	Get all blogs,---- Select between signup and login

Select SignUp   	Email,Username,-----Password	Redirect to login

Select Login	Username and password	Redirect to page with blogs that have been posted by writes and be able to subscribe to the blog

Select comment button	    Comment	--------Form that you input your comment

Click on submit	  	-----Redirect to all comments tamplate with your comment and other comments

Subscription	   Email Address	Flash message -----"Succesfully subsbribed to D-Blog"

# Known Bugs
There are no known bugs
# Contact Information
You can send your comments here :email  root243@mary.gmail.com

# License
MIT License:

Copyright (c) 2022 Mary Auma

