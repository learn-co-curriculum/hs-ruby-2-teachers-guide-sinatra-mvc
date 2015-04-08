---
  tags: kids, mvc, sinatra
  languages: ruby
  level: 1
  type: teacher guide
---

### SWBATs
*Build a basic Sinatra application using the principles of MVC architecture*

  + MODEL - Understand what a model is
  + MODELS - Build a model with attributes and actions
  + MODELS - Understand what attr_accessors are and how to use them
  + SINATRA - Understand why we use the MVC file structure and how models fit into it
  + CONTROLLERS - Understand why we need controllers (to set up routes and connect data from models to views)
  + CONTROLLLERS - Build GET request routes
  + CONTROLLERS - Connect specific routes to erb templates
  + CONTROLLERS - Connect information from models to views via controller and instance variables
  + VIEW - Understand how to create an erb template file (and how it is similar to an HTML file)
  + VIEWS - Understand what the `yield` statement in layout.erb does and why we use it
  + VIEWS - Understand why we  use instance variables in our views
  + VIEW - Understand how to use erb tags and instance variables to display dynamic information in views
  + SINATRA - Boot up server via rackup and run their app
  + SINATRA - Understand why we need a config.ru file
  + SINATRA - Understand what goes into the public folder, gemfile and config folder (environment configurations)
  + NB - Must use rackup (as opposed to shotgun) for this demo (shotgun restarts server every time page is refreshed and tweets disappear)

### Motivation / Why Should You Care?
You all built projects in Ruby 1 that you should be proud of, but you probably wanted to make them even bigger and better and add features that you didn’t know how to implement. We’re going to spend the next few weeks taking your skills to the next level. To that end we need to make sure that our foundation is solid before we get fancy. Today we are going to go over MVC frameworks and lay the groundwork for a basic Twitter like project.

### Lesson Plan
**HOW WEB APPLICATIONS WORK**
+ MVC stands for Model View Controller
+ Models
  * The logic or code that goes into storing and maintaining the data in an application - like adding a tweet to your list of tweets - is the M in an MVC framework - the models.
  * The models are responsible for pulling data from database.
+ Views
  * The V in MVC stands for views and this directory is where we will store all of the HTML (and embedded Ruby) that gets displayed in the browser.
+ Controller
  * The C stands for Controller and the application controller file in our project will hold all the code that is in charge of making the back end - the Ruby logic - talk to the front end - the HTML in the browser that users interact with.
+ This MVC - model view controller - framework is the way that most modern web applications are organized.
  * Keeping the functionality of our application in these separate directories helps us stay organized as our apps become more and more complex.
+ We will be using a gem called Sinatra to set up our MVC framework and create our applications.
  * We’ll be going into depth about how each component of the Sinatra MVC performs each of these actions, but first we need to create a new blank Sinatra project and put in all the empty directories and files that will keep us organized as we build our project.
+ **First Challenge for Students:**
  * Use terminal and your `mkdir`, `touch` and `cd` commands to build out this [file structure](https://github.com/flatiron-school-curriculum/hs-advanced-ruby-project-setup)

**CREATING A GITHUB REPO**
+ We'll be saving student progress on GitHub so they'll all need to set up GitHub repos
+ Here are instructions: https://github.com/flatiron-school-curriculum/hs-git-commit-catchup

**SINATRA WALKTHROUGH**
***Code snippets can be found [here](https://github.com/flatiron-school-curriculum/hs-week-1-code-snippets)
+ Gemfile: This is where we bring in Gems (open source code) that we can use in our project. 
  * Create a development group - for working locally on our computer.
  * Look at the code snippet for Gemfile
  * In terminal in the directory of the project, run `bundle install` once you save the changes to your gemfile
+ Config.ru: This file controls the instructions that actually run our app
  * To run our application we’ll need to start up a server with a tool like the `rackup` gem. 
  * This file tells the server where to find an run the application
  * See code snippet 2
+



### Conclusion / So What?


### Hints and Hurdles

