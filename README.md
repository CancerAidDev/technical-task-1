# CancerAid Technical Task 1

## Introduction

The goal of this task is to get familiar with the Elm ecosystem used at CancerAid.

Your task is to set up the repository in your local environment and make a few small changes to the logic.

You will be assessed based on your reasoning and how you approach the problem, not necessarily on success.

## The Task 

### Step 1 - Installation

We use `yarn` for our package management in CancerAid.

Your first task is to install yarn on your system and install the dependencies for this repository. Yarn's documentation can be found here: https://yarnpkg.com/

You may need to first install node 16 (if you don't already have it on your system) - we recommend using nvm (https://github.com/nvm-sh/nvm) to install and manage node versions, or you can use `brew install node@16` if you're on a mac.

Once you have installed yarn, you can run:

`yarn install`

Now you should be able to run the example:

`yarn local`

Go to http://localhost:1234 to check it out.

### Step 2 - Adding a field

Your next task is to add an `email` field to the form.

At this stage, no validation is required, but make sure you are storing the value.

### Step 3 - Add validation to the email field

The example already has validation around the password field.

In this step, add validation for the email field to check it is a valid email address.

The validation should say "invalid email" when an invalid value is entered into the email field.

### Step 4 - Your choice

You now should be a bit more comfortable with the setup in this repo, so this task is to add something of your choice.



