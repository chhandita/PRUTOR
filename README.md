# PRUTOR
Source code for instructor's interface for PRUTOR (Online programming tutor)

### What is this repository for? ###
This repository is for fetching marks from the database "prutornew" and displaying the marks in question-wise and in a consolidated form.

* Quick summary
* Version
The whole database is imported to phpMyAdmin which is set up on the localhost with port 8080
* [Learn Markdown](https://bitbucket.org/tutorials/markdowndemo)

### How do I get set up? ###

* Summary of set up
softwares needed to be installed:
1) Wamp Server
2) phpMyAdmin - to be installed on the localhost(port number 8080 if phpMyAdmin doesn't work on the default ports)
* Configuration
$servername = "localhost:8080";
$dbname = "prutornew";
$user: "root";
$password: "";
* Dependencies
For importing large sql files on phpMyAdmin, go to "I cannot upload big dump files" 
on this link :https://docs.phpmyadmin.net/en/latest/faq.html

* Database configuration
* How to run tests
* Deployment instructions

### Contribution guidelines ###

* Writing tests
* Code review
For consolidated marks :
Fetch marks for each event from the datbw
* Other guidelines

### Who do I talk to? ###

* Repo owner or admin
* Other community or team contact
