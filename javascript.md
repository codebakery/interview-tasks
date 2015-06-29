# FoobarTimesheets

## Techinal requirements

1. MVC-like client (React + Flux, Angular or Backbone)
2. Node.JS server (Express)
3. Unit tests (Jest or Jasmine)

## Optional stuff

1. ES6 with Babel
2. Build system with webpack or Browserify

## Project Spec

1. It should allow user to sign in using GitHub OAuth
2. It should display a list of sent timesheets
3. It should allow user to create a new timesheet (see App page #3)
4. On new timesheet page, it should allow user to set date for a timesheet using a datepicker
5. On new timesheet page, it should autocomplete typing in 'Project' input using GitHub API (https://developer.github.com/v3/repos/#list-your-repositories)
6. On new timesheet page, it should append new timesheet row when user starts filling out the first row

## App pages

1. Landing page - generic landing page with sign in link on top
2. Timesheet list page - list of user timesheets, create a new timesheet link
3. New timesheet page - choose timesheet date with datepicker on top, table with four columns (project, issue, hours spent, comment) and one empty row with text inputs, autocomplete for project names, e.g. `octocat/Spoon-Knife`. When you start typing in the first row, next empty row appears.