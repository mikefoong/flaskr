# flask Tutorial Project
# Project: flaskr

starting flackr
source activate flaskr
. env.set (this sets the environment)
flask run --host=0.0.0.0

default username and password: admin/default

## 201721Ap+65
Added Views for 
1. /
- Show all database entries
2. /add
- add title and text to the database
3. /login
- to authenticate a single user
- hardcoded password
4. /logout
- use pop() to remove session from a dict (pros? cons?)


## 201721Apr+651747
- Tested the app. Receiving a syntax error for request.form

## 201721Apr+652107
- error in else if - should be elif and not elseif
- corrected some typo

### Moving on to templates
- Templates uses jinja2 syntax
- template inheritance are what makes reusing of a layout possible

### Created the layout.html
- This template contains HTML skeleton
- It also creates the log in and log out functions

### Created the show_entries.html
- extends the layout.html 

### Created the login.html to authenticate the user
