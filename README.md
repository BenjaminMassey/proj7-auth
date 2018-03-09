# Project 7: Authenticated brevet time calculator service

Ben Massey March 2018 for CIS 322

## What is this?

This is a continuation of the brevet calculator. It is essentially everything from last time,
(see proj6-rest), but with a user profile for storing your data. There are also now buttons
for the functions in project 6.

## How to use

1. Create a MongoDB database (I used m-lab)

2. Create a collection titled "users" in that database

3. Create a collection titled "times" in that database

4. Create your credentials.ini file based on credentials-skel.ini

5. Run the program!

You can either use basic python (python flask-brevets.py), basic docker (have fun),
or docker-compose (docker-compose up)