
# Mariana Trench Explorer

A full stack Javascript educational app about the layers of the ocean and what lies beneath...

Completed as a group project in Week 10 of CodeClan.


## The Project Brief

The BBC are looking to improve their online offering of educational content by developing an interactive browser application to display information in a fun and interesting way.

### MVP
After a thorough planning session, as a group we determined a minimum viable product:
* User should be able to navigate through different sections of content
* App should display multimedia information on things the user might find on their journey
* Interactive background
* Tablet responsive
* Depth gauge in meters
* Use of MongoDB database and Express backend framework

### Extensions
We used a MoSCoW board to help determine what would be the best additional features to tackle:
* Make it mobile responsive
* Ocean sounds effects
* A quiz when the user reaches the bottom
* Pressure and temperature readouts for particular depths
* Form for the user to add their name, height at the beginning of their journey, so that we can create depth gauge based on their height
* Quiz High Score Leaderboard
* Animations
* Quiz between levels to allow user to progress deeper
* Different size buildings to compare the depth
* Give user a prize of a fish/sea creature depending on their score (with mini facts about it)

## Project Parameters
The project was completed as part of a team and used the following technologies:

- ![Javascript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
- ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
- ![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)
- ![Express](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
- ![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
- ![NPM](https://img.shields.io/badge/NPM-%23000000.svg?style=for-the-badge&logo=npm&logoColor=white)
- ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
- ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

## Video Walkthrough
##  Challenges and Solutions

### Time Challenges
At the beginning, we had a team of four for the six day project, however, unfortunately a team member had to leave very early in the project due to unforeseeable circumstances.
We also experienced hardware issues which further reduced available build time.  We responded to these challenges as a team:
-    Remained positive  and focussed on achieving the MVP and extensions we'd defined together. 
- When not in person, worked together keeping in close contact via Slack and Discord.
-  Adopted an agile working model to maximise our efficiency throughout the week. 
-  Used pair and mob programming on several occasions to resolve complex issues quickly.


### Design Challenges

As well as developing the app, our selected topic required a significant amount of subject matter research, content creation and visual asset creation.   As a team we tackled this by segmenting tasks into smaller ones, splitting them evenly between us and sharing knowledge and techniques (eg using Canva) with each other.  We also created a colour palette early for design consistency. 


## Learning Points

- Consolidated learning from JavaScript Module (Weeks 5-9 of Codeclan)
- Experience working in a team with other developers
- Overcoming development challenges collaboratively
- Using Agile working methods
- Using Git/GitHub for a multi person project

## Run Locally

Clone the project and go to the project directory:

```bash
  cd mariana_trench_project
```

Install dependencies in both the client and the server folders:

```
cd client
npm install

cd server
npm install
```

Seed the database.  Within the server folder:

```
npm run seeds
```

Run express (leave running in a terminal window).  Within the server folder:

```
npm run server:dev
```

Run React development environment (leave running in a terminal window).  Within client folder:

```
npm start
```

The application is running on port 3000 so visit http://localhost:3000/ to try out!

