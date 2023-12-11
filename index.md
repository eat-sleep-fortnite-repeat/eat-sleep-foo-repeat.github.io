![](doc/yummyfoologo.png)
# Overview
Our goal for this project is to create an information hub where students of UH Manoa can find, share, and learn new and creative recipes that will fit within the budget of a college student. For convenience and money’s sake, the majority of students will buy fast food or take out for their meals. However, this can lead to unhealthy eating habits as well as a selection of food that might not fit the constraints of every student, whether that be food allergies or intolerances. 

To remedy this, our website will prompt UH students to begin or expand on their culinary education, learning how to cook up meals that will fit their specific needs. Users can browse through the current selection of recipes, as well as add their own, and favorite ones they want to try out! We hope that with the large selection of recipes, pricing information, ingredient and appliances, as well as acknowledgement of dietary constrictions, this will be able to help all students of UH Manoa.

# Table of Contents
* [Community Feedback](#community-feedback-)
* [User Guide](#user-guide)
* [Developer Guide](#developer-guide)
* [Deployment](#deployment)
* [Development History](#development-history)
* [Meet the Team](#team)
* [Team Resource Links](#link-to)

# Community Feedback 
To test the application, we took our website to the community to see what they had to say:

Aiden's feedback:
"I liked the searching and adding your own recipe functionality. I think the site could use a visual overhaul and some of the menus are confusing."

Mairi's feedback:
"I thought the website was very easy to use and well designed to help me get what i was looking for. This has great potential for college students!"

Kye's feedback:
"The picture on the individual recipe page is way too small or thin. Some formats on the recipes page are not the same and some images do not show up. However, the overall application looks good."

Catelyn's feedback:
"I would use this application because I live on my own and I want to eat and cook yummy food on a budget. Overall, the functionality of the application works great like adding & submitting recipes to the form, searching for recipes, and bookmarking my favorite recipes. However, some areas need a bit of touch-up such as the images of the individual recipe pages and the [landing] page feels a bit naked. Considering that this is the basic form of the app, I definitely see this app improving and having more potential!"

David's feedback:
"I like the concept of a database that prioritizes the needs of college students. Your color choices lend to a very cute vibe. The links at the top make navigation simple. When I added a recipe, you have a field called "Filters" that did not immediately make sense to me, and may not make sense to the average user. I am guessing this should be renamed to something like "tags" or "keywords" so the user realizes this is to help others locate this recipe."

# User Guide

## Logging in 

To log in, either type in your credentials or register here:

![Step 1](https://github.com/eat-sleep-fortnite-repeat/YUMMY-FOO/blob/main/img/Login.jpg?raw=true)

## How to Add a Recipe

To add a new recipe to the website, follow these steps:

### Step 1

Click the Add Recipe button

![Step 1](https://github.com/eat-sleep-fortnite-repeat/YUMMY-FOO/blob/issue-46/img/addrecipe_step1.jpg?raw=true)

### Step 2

Fill out the form and press the submit button to submit your recipe.

![Step 2](https://github.com/eat-sleep-fortnite-repeat/YUMMY-FOO/blob/issue-46/img/addrecipe_step2.jpg?raw=true)

## How to Search for a Recipe

To search for a recipe, follow these steps:

### Step 1

Click the Search button

![Step 1](https://github.com/eat-sleep-fortnite-repeat/YUMMY-FOO/blob/issue-46/img/search_step1.jpg?raw=true)

### Step 2

Type in the search box anything you would like to search - ingredients, name, appliances, etc

![Step 2](https://github.com/eat-sleep-fortnite-repeat/YUMMY-FOO/blob/issue-46/img/search_step2.jpg?raw=true)

### Step 3

Reset your filters by pressing the reset search button

![Step 3](https://github.com/eat-sleep-fortnite-repeat/YUMMY-FOO/blob/issue-46/img/search_step3.jpg?raw=true)

### Step 4

To view the recipe in full, click on the recipe link.

![Step 4](https://github.com/eat-sleep-fortnite-repeat/YUMMY-FOO/blob/issue-46/img/search_step4.jpg?raw=true)

## How to Favorite and View Favorite Recipes

To favorite and view your favorite recipes, follow these steps:

### Step 1

After searching for a recipe, click the star icon on a recipe you like.

![Step 1](https://github.com/eat-sleep-fortnite-repeat/YUMMY-FOO/blob/issue-46/img/fav_step1.jpg?raw=true)

### Step 2

Favorited recipes will have a gold star

![Step 2](https://github.com/eat-sleep-fortnite-repeat/YUMMY-FOO/blob/issue-46/img/fav_star.jpg?raw=true)

To view your favorite recipes, click the favorites tab

![Step 2](https://github.com/eat-sleep-fortnite-repeat/YUMMY-FOO/blob/issue-46/img/fav_page.jpg?raw=true)


# Developer Guide
## Download
Download our source code from this project [here](https://github.com/eat-sleep-fortnite-repeat/YUMMY-FOO).

## Installation
First, [install Meteor](https://www.meteor.com/install).

Second, once you have access to the YummyFoo repo you can clone the repo for yourself and open with a program like Github Desktop.

Third, once you have the project set up in a program like IntelliJ IDEA, you can open up the terminal inside the application, cd into the app/ directory and run:
```
$ meteor npm install
```
Fourth, to actually run the website use:
```
$ meteor npm run start
```
* This segment might take a while to finish but you will know its done when something like this pops up: <img src="doc/meteorInstallM2.jpeg">
* This created the users that you can log into to access certain pages along with the default recipes built into the website
* It also contains the link you can click on to open the website

Fifth, as a precautionary check you can run:
```
$ meteor npm run lint
```
to see if there are any errors, hopefully there won't be any and you can run the website without any issue

## Modifying the Application
To modify our work, create a clone of the [application](https://github.com/eat-sleep-fortnite-repeat/YUMMY-FOO) and open the project with an IDE (our team used [IntelliJ](https://www.jetbrains.com/idea/)). Cd into the directory of the app locally:
```
$ cd yummy-foo/app
```
Before modifying the application, below is the background and functionality of each page:

### Landing Page
Upon loading the website users are directed towards our landing page. Along with a carousel, this page gives a description to users about our purpose behind creating this website and how they can use it.

![](doc/landingM2.png)

### Login
Next users should login or create an account in order to gain access to the websites main features.
![](doc/loginM2.png)

### User Homepage / Favorites
Once logged in users are then taken to a Favorites page which includes all of their favorites recipes. A new user would have a blank page and can add to their favorites by navigating to Search.
![](doc/favoritesM2.png)

### Search
The search page allows users to search by any part of the recipe whether that be name, time, ingredients, or cost. From the results they end up with users can then click on either click on the name or picture to take them to that specific recipe page.
![](doc/searchM2.png)

### Specific Recipe Pages
This is the recipe page that includes all details about the specific recipe.
![](doc/specific-recipeM2.png)

### Add Recipe
From Favorites and also the navbar users can also navigate to the Add Recipe page where they can upload their own recipe by filling in all the form text fields and then uploading an image from their local device.
![](doc/add-recipeM2.png)

### List Recipe Admin
For admins only, they are able to see all recipes and have the power to remove and edit any recipe.
![](doc/list-recipe-adminM2.png)

### Edit Recipe Admin
If admin clicks on edit they are given a pop up where they can change any details about the recipe and update it for all users.
![](doc/edit-recipeM2.png)

### About Us Page
![](doc/about-us-updated.jpg)

### Testing
In the test directory there are tests to ensure site pages display and function as they should.
![](doc/GreenTests.png)
![ci-badge](https://github.com/eat-sleep-fortnite-repeat/yummy-foo/workflows/yummy-foo/badge.svg)

# Deployment
Find our project website [here](http://146.190.161.129/)!

# Development History
The development process for Yummy Foo conformed to [Issue Driven Project Management](https://courses.ics.hawaii.edu/ics314f19/modules/project-management/)! practices. In a nutshell:

* Development consists of a sequence of Milestones.
* Each Milestone is specified as a set of tasks.
* Each task is described using a GitHub Issue, and is assigned to a single developer to complete. 
* Tasks should typically consist of work that can be completed in 2-4 days. 
* The work for each task is accomplished with a git branch named “issue-XX”, where XX is replaced by the issue number. 
* When a task is complete, its corresponding issue is closed and its corresponding git branch is merged into master. 
* The state (todo, in progress, complete) of each task for a milestone is managed using a GitHub Project Board.

The following section documents the development history of Yummy Foo.

## Milestone 1: Mockup development
The goal of Milestone 1 was to create a set of HTML pages providing a mockup of the pages in the system.

Milestone 1 was managed using [Eat-Sleep-Foo-Repeat GitHub Project Board M1](https://github.com/orgs/eat-sleep-fortnite-repeat/projects/2/views/1):
![](doc/M1ProjectBoard.png)

## Milestone 2: Implementing Admin and list pages
The goal of Milestone 2 was to add more pages and tidy up the project as a whole.

Milestone 2 was managed using [Eat-Sleep-Foo-Repeat GitHub Project Board M2](https://github.com/orgs/eat-sleep-fortnite-repeat/projects/3/views/1):
![](doc/project-m2.jpg)

## Milestone 3: Work in Progress
The goal of Milestone 3 was to finish implementing real data, the rest of the site, and get outside trial and feedback.

Milestone 3 will be managed using [Eat-Sleep-Foo-Repeat GitHub Project Board M3](https://github.com/orgs/eat-sleep-fortnite-repeat/projects/5):
![](doc/M3projectboard.png)

# Link To...
* [Team Contract](https://docs.google.com/document/d/10fjiUGCcoZn1zsEntLvA_btXFST54v0s46QtEraBu4E/edit?usp=sharing)
* [GitHub Organization](https://github.com/eat-sleep-fortnite-repeat/eat-sleep-fortnite-repeat.github.io)
* [Milestone 1 Project Page](https://github.com/orgs/eat-sleep-fortnite-repeat/projects/2)
* [Milestone 2 Project Page](https://github.com/orgs/eat-sleep-fortnite-repeat/projects/3)
* [Milestone 3 Project Page](https://github.com/orgs/eat-sleep-fortnite-repeat/projects/5/views/1)

# Team

Yummy Foo is designed, implemented, and maintained by [Aiden Woodard](https://github.com/aidenlkw), [Catelyn Jochim](https://github.com/cjochim), [David Rickards](https://github.com/DavidRickards), [Kye Steele](https://github.com/kyesteele), and [Mairi Yoshioka](https://github.com/mair1). 
