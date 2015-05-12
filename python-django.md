# FoobarToDo

## Techinal requirements

1. Django 1.8
2. Python 2.7 or Python 3.4
3. Project pip requirements in requirements.txt. Any number of Python requirements
   can be used
4. Test Suite
5. Project hosted as public GitHub repo
6. OPTIONAL: Client MVC (React, Angular or Backbone). jQuery/jQuery UI is fine too

## Project Spec

1. It should allow user to create a new account or sign in using Facebook or Google
2. User's social auth and registered accounts should be integrated into one if email is the same
3. User model should have email as "username" field
4. User should get email confirmation after registration. No confirmation is needed after social sign in
5. Main application screen should display all to-do lists as clickable blocks with list of first 5 items. (like Google Keep stickers). 'Create new to-do' link should be also present
6. Clicking on to-do list or clicking 'create new to-do' link should redirect user to todo edit/entry list
7. New entry input should be displayed below entry list
8. After typing into new entry input and pressing "Enter" key a new entry is created and appended to the entry list. Input is cleared
9. Entries should be sortable with drag-n-drop

## App pages

1. Landing page - placeholder text and sign in/sign up links on top
2. Sign in page - form with email and password fields, submit button and social login links below
3. Sign up page - form with email, password, password confirmation, first name and last name
4. Email confirmed page - displayed after clicking a link in the confirmation email
5. To-do list page - list of to-do blocks, create a new to-do link
6. To-do edit page - list of to-do entries, new entry text input