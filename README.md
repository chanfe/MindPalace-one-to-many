# MindPalace-one-to-many

## Objectives

1. Construct a directional one to many.
2. Query for associations via the belongs_to and has_many associations.
3. Iterate over associations in a view and display associated data for a primary instance.

## Overview

Oh no! One people person have truoble of remebering his <object here> and he need something to keep track of his <object here>.  Let's help this people person out (and practive our associations) by building some associations and displaying the data.

![greys-anatomy](https://media.giphy.com/media/6SaVutI40pCKc/giphy.gif)

## Instructions

First, fork and clone this lab.

You'll need to create all of the migrations, models, routes, controllers, and views for this lab.

***NOTE***: As with much of our Rails curriculum, remember to always use the `--no-test-framework` flag when you generate models, controllers, etc. That way, the Rails generators will not create additional tests on top of the test suite that already comes with the lesson. E.g., `rails g model User username:string email:string --no-test-framework`.

Every 'Person' should be created with a 'name', 'age' and 'weight' and every 'Memory' should be created with a 'object' and a 'description'. And since Flatiron is all about love, when a Memory is created, it needs to be created with a Person. After all, a memory should never be without an owner!

With this website, a user should be:

* Able to see a list of all the person

* Able to see a single person and all the memory owned by that person

* Able to log a new person (and make sure that their name, age is not blank)

* Able to edit a person's name (and make sure that their name and age is not blank)

* Able to see a list of all the Memory

* Able to see a single memory and see all its details

* Able to edit a memory and its details

* Able to create a new memory with an association to a person (and make sure that their name and type are not blank)

Make the necessary edits and alterations to make the website function as expected.
