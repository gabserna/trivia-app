Trivia App

General Requirements:

You must use a good structure for your app. Separate code in different files as you see fit.
App should have zero critical bugs and up to three small bugs (a critical bug is
defined as one that blocks a user from using or completing a major feature in your
app and for which there is no workaround).
Commit and push your work to GitHub daily.
Publish a web app on a public website.
App Specific Requirements:
The goal of the Trivia App is to allow the user to challenge themselves to a trivia game and
display/save their results. Your app must have a minimum of three different pages, but you can add more pages/details than are listed here if you would like. It is up to you how you route between pages 2-3. This API has limited documentation, but many options. In order to find all of the difficulty types and question types, you will need to test the API for each one in order to build all of the options for your own application.

The first page (only page that order matters) that the user sees should be a welcome and set up page. The setup consists of a list of  categories to choose from which you can get from the API, a way to select difficulty (easy, medium, hard), and a way to select the type of trivia question (true/false or multiple choice). Once all the setup is complete the tap of a button should start the trivia.
The second page is the trivia game. Each question will pop up on the screen at a time. There should be a timer going and displayed. There should also be displayed the question number and out of how many questions. Once the user clicks on an answer, let them know if they got it right or not and move to the next question. Once all questions are done, display their result and the option to save the result or not. This last view should have a way to see the stats page.
The third page should be the stats page. This page should contain a list of the trivia games the user has played and a bit of information about each trivia (time taken, score, category, difficulty) and a general stats section where the user can see how many trivias they have done, what is their overall score and whatever else you think would be interesting to know. This page should be accessible from the first page and the user should be able to go back to the first page. 
Setup (No API Key required):
1. Go to https://opentdb.com/api_config.php
2. Click “API Documentation” to open endpoints/documentation
3. Use “API Helper” for example of what a correct API endpoint should look like
Endpoints:
The endpoints listed below are examples only and can be altered to the way you need them.
1. To get all categories - “https://opentdb.com/api_category.php”
To get a set of questions matching # of questions/category type/difficulty/type (T/F or
Multi) - “https://opentdb.com/api.php?amount=10&category=9&difficulty=medium&type=multiple”

