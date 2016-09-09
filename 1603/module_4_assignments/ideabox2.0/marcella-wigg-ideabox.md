# Ideabox 2.0 Submission Form - Marcella Wigg

[Project Spec](https://github.com/turingschool/curriculum/blob/master/source/projects/revenge_of_idea_box.markdown)

* Fork this repo, if you haven't already and check out a branch
* Use this README as a template to create a file in this folder with your name as the title.
* Submit a pull request
* Pro Tip: You can use [recordit.co](http://recordit.co/) to record interaction gifs.
* Secondary Pro Tip: [Here's how to link to specific line number(s) in Github](http://stackoverflow.com/questions/23821235/how-to-link-to-specific-line-number-on-github)
* Tertiary Pro Tip: You can re-use some of these things in your portfolio/resume

------

# Basics

### Link to the Github Repository for the Project
[GitHub Repo](https://github.com/marcellawigg/bright-ones)

### Link to the Deployed Application
[Deployed Application](http://bright-ideas.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[Commits](https://github.com/marcellawigg/bright-ones/commits/master)

### Provide a Screenshot of your Application

## Completion

### Were you able to complete the base functionality?
* Yes - with bug

### Which extensions, if any, did you complete?
* None

### Attach a .gif, or images of any extensions work being used on the site.
* N/A

# Code Quality

### Link to a specific block of your code on Github that you are proud of
* Why were you proud of this piece of code?

[Link to Code](https://github.com/marcellawigg/bright-ones/blob/master/test/requests/api/v1/ideas_controller_test.rb)
* Sounds dumb, but I am really proud to be testing my controllers more thoroughly.

### Link to a specific block of your code on Github that you feel not great about
* Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?

[Link To Code](https://github.com/AnnaCW/ideabox/blob/d4bd9aa93ac951c9d06a85dffc4a425a242d07c8/app/assets/javascripts/edit_ideas.js#L1-L47)

* This is a link to part of my code for the edit ideas (title and body) functionality. I had a lot of challenges in trying to get this to work, so I'm proud of it in the sense that I got it working. I don't feel great about it in that I'm sure this is not the best way to do it, and the code just looks messy. I was not able to test it so I am hesitant to refactor.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.

![Screenshot](http://i.imgur.com/boW4LXx.png)

#### MINITEST

# Running:

............

Finished in 0.572686s, 20.9539 runs/s, 33.1770 assertions/s.

12 runs, 19 assertions, 0 failures, 0 errors, 0 skips


#### TEASPOON

Failed to do this.


### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'

[Unhappy Path Example](https://github.com/marcellawigg/bright-ones/blob/master/test/requests/api/v1/ideas_controller_test.rb)

* This test makes sure that an item will not be able to be created without the required fields.

-----

### Please feel free to ask any other questions or make any other statements below!

# Instructor Feedback

131/150

*** Very minor amending needs to be done and score will rise significantly when done :D See note below ***

### Data Model

(5 points total.)

### User Flows

#### Viewing ideas

(5 points total.)

Buggy truncation

#### Adding a new idea

(15 points total.)

#### Deleting an existing idea

(15 points total.)

#### Changing the quality of an idea

15 points total.

Needs to be fixed for new idea

#### Editing an existing idea

20 points total.

Needs to be fixed for new idea

#### Idea Filtering and Searching

(15 points total.)

## Instructor Evaluation Points

### Specification Adherence

* **10 points**

### User Interface

* **3 points** - The application has many strong pages/interactions, but a few holes in lesser-used functionality.

### Testing

* **5 points** - Project has sporadic use of tests and multiple levels. Not all controller actions are tested. There are little or no attempts at integration testing.

### Ruby and Rails Quality

* **8 points** - Developer solves problems with a balance between conciseness and clarity and often extracts logical components. Developer can speak to choices made in the code and knows what every line of code is doing.

### JavaScript Style

* **5 points** - Your application has some duplication and minor bugs. Developer can speak to most choices made in the code and knows what every line is doing.

### Workflow

* **10 points** - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.
