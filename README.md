Turing Mod2 Intermission Work : Task Manager Rails Introduction

Checks for Understanding
Define CRUD.
  Create Read Update Delete. Operation process for interracting with stored data
Define MVC.
  Model View Controller - Pattern in SoftwareDev used to implement user interfaces, data and logic
  Model - Manages data and business logic
  View - Handles layout and display
  Controller - Routes commands to the model and view parts
What three files would you need to create/modify for a Rails application to respond to a GET request to /tasks, assuming you have a Task model.
  We would need to modify the tasks_controller.rb and routes.rb files, and create a get.html.erb file in our      views/tasks directory, 
What are params? Where do they come from?
  Params are parameter objects. They are a method built into ActionController which is a class we inherit from.
Check out your routes. Why do we need two routes each for creating a new Task and editing an existing Task?
  We need one for the task erb file, one for the params
