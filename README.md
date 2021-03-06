# Day Care Portal App (backend)

This app is built to facilitate parent teacher interaction in a day care setup, where parents will be able to view what children activities are and teachers will be able to post new activity and also interact with the parents as needed. This is the back end for this app.

# How it works

The app can be used from two point of view

1)	Parent – From a parent POV, you can use the app to view the activities for your children for the current week. Parents also have the options to post special notes related to their children for the teacher’s attention. Please login using number from 1-10 as both username and password. 
2)	Teacher – From a teacher’s POV, the app can be used to enter children activity like breakfast, play, nap time etc. Teachers also have the ability to view special notes from parents. Please login using number 1 as both username and password.

# Tech behind this

The backed for the app is built on Ruby on Rails & PostgreSQL. All the CURD operations are exposed to the UI as RESTful calls. RESTful API is build using the Ruby on Rails framework. The PostgreSQL has a simplistic data model for storing all the information about children, parents, teachers, activities, notes etc.

# Future enhancements / Known issues

Enhancements

High Priority 

1 - Login using proper authentication and maintaining session

2 - Add Home button when you are in the login page for parents and teachers

Parents 

1 - Add a calendar view so that a parent can look at the activity for any given day

2 - Add offline chat like interaction between teachers and parents 

3 – Along with the weekdays, show the actual dates

Teachers

1 - Add capability to look at what’s been entered

2 – in addition, give ability for teacher to correct/update an activity

3 - List of values (dropdowns) for various items

4 – Use Date object / calendar for Date

Note from Parents

1 – Ability to select a note and edit/delete it

# About the author

Prathyusha
