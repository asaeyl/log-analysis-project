# log-analysis-project


Asaeyl talal

## About

This is the first project for the Udacity Full Stack Nanodegree. The name of project is logr analysis project . In this project, a big database is given. And I discover the database and write some queries to answers the questions. The database contains newspaper articles, as well as the web server log for the site.

## To Run the project

### You will need:
- Python3
- Vagrant
- VirtualBox


### Setup
1. Install Vagrant And VirtualBox
2. download the data and put newsdata.sql in vagrant directory

### To Run
Launch Vagrant Virtual Machine by running `vagrant up` inside the vagrant directory
then you can log in with `vagrant ssh`

To load the data, use the command `psql -d news -f newsdata.sql` to connect a database and run the necessary SQL statements.

The database includes three tables:
- Articles table
- Authors table
- Log table

To execute the program, run `python3 newsdata.py` from the command line.
