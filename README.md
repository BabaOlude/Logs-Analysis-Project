# Logs-Analysis-Project

## Technologies That I Used

Python

PostgreSQL

Git Bash

## This tool produces answers to the following three questions based on the data in the database:

What are the most popular three articles of all time?

Who are the most popular articles authors of all time?

On which days did more than 1% of requests lead to errors?

## Getting Started

Open Terminal (Windows users - open Git Bash terminal that comes with the GIT software).

In the Terminal enter "psql -d news -f newsdata.sql" to connect to the database "news" and run sql commands.

Run the command " psql news" to open PostgreSQL command line program

After you created the view, exit PostgreSQL command line by running "\q" command.

To load the data, use the command psql -d news -f newsdata.sql to connect a database and run the necessary SQL statements.

## What I Learned About Not Using VirtualBox and Vagrant

I actually did not use Virtualbox and Vangrant. I discussed it with my Udacity mentor and I ended up just getting Postgres on my machine and using it with GitBash. I also used Visual Studio Code for my Python script development. What I learned was that Virtualbox and Vagrant are good things to know, but not 100% necessary and that in web development there tend to be a few different ways create a work environment. I already had GitBash on my computer. I liked using these tools and I would recommend them to anyone doing this project.
