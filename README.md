# README

Banking Buzz Blog

Banking Buzz is a simple CRUD system that enables users to create and share news and information about the big 4 Australian Banks: Commonwealth Bank, Westpac, ANZ Bank, and National Australia Bank. The blog is designed to provide a platform for discussions on the latest news, events, and trends in the banking industry.


Installation

To install this application on your local machine, please follow these steps:

Clone this repository to your local machine.
Make sure you have Ruby version 2.7.8 installed.
Run bundle install to install all the necessary dependencies.
Run rails db:migrate to migrate the database.
Start the server by running rails server.

Features

Create, read, update and delete blog posts
Leave comments on posts

Usage

Once the server is up and running, you can access the application by visiting localhost:3000 in your web browser. Here's a breakdown of what you can do with the application:

Creating a new post
To create a new post, click on the "New Post" button on the homepage. You'll be taken to a form where you can enter the details of your post, including the title and the body. Once you're done, click the "Create Post" button to save your post.

Updating a post
To update an existing post, click on the post's title on the homepage to view its details. On the post's details page, click the "Edit" button to make changes to the post's title and body. Once you're done, click the "Update Post" button to save your changes.

Deleting a post
To delete an existing post, click on the post's title on the homepage to view its details. On the post's details page, click the "Delete" button to remove the post from the application.

Commenting on a post
To add a comment to an existing post, click on the post's title on the homepage to view its details. Scroll down to the "Comments" section and enter your comment in the form provided. Once you're done, click the "Create Comment" button to save your comment.


Technologies and Gems Used

Ruby on Rails framework
SQLite database
Puma app server
Bulma CSS library - a modern CSS framework based on Flexbox
The following gems are used in the project:

sass-rails - to use Sass for stylesheets
coffee-rails - to use CoffeeScript for .coffee assets and views
jbuilder - to build JSON APIs
uglifier - to compress JavaScript assets
turbolinks - to make navigating the web app faster
simple_form - to simplify forms
better_errors - to make error pages more user-friendly
bootsnap - to reduce boot times through caching
byebug - to debug code
capybara - to write system tests
selenium-webdriver - to use the Selenium driver for system testing
chromedriver-helper - to easily install and use chromedriver for system testing