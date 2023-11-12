---
layout: page
title: Banana Central
permalink: /projects/bananacentral
parent: Projects
nav_order: 2
---

# Welcome to Banana Central | <a href="https://github.com/loganditterline/bananacentral" target="_blank"><img src="../assets/images/github-mark-white.png" alt="GitHub Logo" width="25" height="25"></a>

Banana Central SAT Prep is a web app designed to streamline SAT preparation by condensing official College Board questions into short daily sessions. Inspired by the efficiency of language learning apps like Duolingo, our goal is to make SAT prep more accessible and engaging. This was made within a 24-hour period as part of MakeUC 2023 and won the competition.

## Technologies Used

* React - Frontend framework
* HTML - Webpage formatting
* CSS - Formatting and styling
* Javascript - Functions and calls
* Auth0 - Authentication
* NodeJS - Backend framework
* Python - Backend arithmetic and question generation
* MongoDB - Database management
* Github - Version control

## Project Walkthrough

This journey began by scraping 2000 questions from the official College Board SAT practice website. Since there was no database readily available, manual scraping had to be done to gather training data. Additionally, we queried 100 reading and writing questions, along with 100 math questions from OpenAI's ChatGPT3.5 turbo. All questions were stored in a MongoDB Atlas database. Once we were able to store these questions, we developed an application that would present user's with questions based upon their strengths an weaknesses in the form of lessons. Each lesson had a set of questions that were presented to the user in a random order. The user would then select the correct answer and the next question would be displayed. Once the user finished, it would display how the user had improved. On a leaderboard site, one could view the top 10 scorers using the platform by lessons completed.

## Demo / Example Images

### Home Page of Application
<img src="../assets/images/bc-home.PNG" alt="Home Page of Application" style="border: 1px solid #ddd; border-radius: 4px; padding: 5px;">

### Example of an AI Generated Question
<img src="../assets/images/bc-example-question.PNG" alt="Example AI Generated Question" style="border: 1px solid #ddd; border-radius: 4px; padding: 5px;">

### Final Stats Page of a Lesson
<img src="../assets/images/bc-stats.PNG" alt="Final Stats Page of a Lesson" style="border: 1px solid #ddd; border-radius: 4px; padding: 5px;">

### Leaderboard of Top Monkeys
<img src="../assets/images/bc-leaderboard.PNG" alt="Leaderboard of Top Monkeys" style="border: 1px solid #ddd; border-radius: 4px; padding: 5px;">
