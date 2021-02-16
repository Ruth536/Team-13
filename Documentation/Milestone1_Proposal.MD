# CEN 4010 Principles of Software Engineering Spring 2021
# Milestone 1 Project Proposal: An online multiplayer 2-D game where players navigate through obstacles
# Team name and project name: Team 13
# Team 13
# Rosalba Monterrosas: rmonterrosas2015@fau.edu
# Brandon Basdeo: bbasdeo@fau.edu
# Ruth Betancourt: rbetancourt2003@fau.edu
# Michael Hollinger: mhollinger2020@fau.edu
# Lionel Munoz: lionelmunoz2018@fau.edu
# Luiz Zullino Junior: lzullinojuni2020@fau.edu
# 02/12/2020
# History Table
Version 0.00 - 2/12/21 - Added template
Version 0.01 - 2/15/21 - Added executive summary
Version 0.02 - 2/15/21 - Added competitive analysis
Version 0.03 - 2/16/21 - Added High-Level System Architecture and Team

## Executive Summary
Team 13 will be making a project aimed at connecting during social distancing through the use of a multiplayer game. The game will be playable in a browser and users will be able to choose who they connect to. The system for allowing users to find each other will be a short randomized code, which can be shared using outside means like text or video communications. Players can maintain privacy by only sharing their code with people they choose. Only the usernames of players will be shared with other players, and all other information will be kept private. 

The main function of the game will be players competing against each other in a two dimensional obstacle course. Using user friendly interface, simple movement, and easy to understand controls, players will move from start to finish and compete to see who can finish first. The games will be short, a few minutes long, so people will not need to allocate a large amount of time to play. During times of social distancing, our game aims to provide a means of connecting with other people for a short moment of fun, before continuing with the rest of their day. 

## Competitive Analysis
Key Features: Competitor vs Team 13
|Competitor (Fall Guys)|	Team 13|
|---|---|
|Online Multiplayer	|Code Based Lobby|
|3D-Graphics|	2D-Graphics|
|Third Person|	Side-View|
|Winner Take all|	Point System|
|Customizable Avatars|	Customizable Avatars|

One of the major competitors that came to mind when coming up with our idea was the fame Fall Guys. When people think of online obstacle game, the think of Fall Guys. The first key difference will be how the multiplayer works. Fall Guys requires around a 50-person lobby which means there is no way to play solely with your friends. Our idea is to use a code invite system and have the games on a smaller scale so that games can take place between friends. Fall Guys takes place in a 3D environment, while our game will be in 2D. In this day and age, a games success has little to do with the dimensions of the game and more to do with how it makes use of the space. Only being in 2D will allow us to spend more time making the physics work well and give the user more control over their avatar. Our game will be using a side-view perspective which will allow the user to have precise control over the two dimensions they can move in. Fall Guys’ movement is much less focused on precision and more on situational awareness which allows are game to fill a difference niche. The point system between the two games will also be different. Fall Guys utilizes a winner take all when it comes to receiving rewards from playing. Our game will have a point system that will allow even those who come in second or third to earn rewards and have a sense of progression. Finally, you need a way to spend these points and this is where the two games will behave the same. The points players earn through their accomplishments will be used to buy customizable items to personalizer their avatars.

## Data Definition

**LAMP Server**: Linux Apache MySQL PHP [LAMP] server, provided by FAU, provides access to Linux (via SSH access) ), Apache (for web based development via PHP or CGI-BIN), MySQL (for database development), PHP (for web based development, and Tomcat (for java based web development).

**Unity**: American video game software development company


## Overview, scenarios and use cases

## High-level Functional Requirements

## Non-functional Requirements

## High-Level System Architecture

### Database

Use MySQL database service on the Lamp server. The database will store the players’ login information (unique username and hashed password), game data, and their highest score.

### Server
Use our group’s LAMP server provided by the university.

### Client-Server Relationship

* Client-side: JavaScript
* Server-side: PHP

### API’s
* Vulkan API: Graphics API developed by Khronos
https://www.khronos.org/vulkan/

* Last.fm API: Allows the exploring of the entire collection of the website’s music data resources, such as artists and playlists.
https://english.api.rakuten.net/dimashirokov/api/LastFm


### Supported Browsers
* Google Chrome
* Firefox


### GUI

Unity  for developing a 2-D game 
https://docs.unity3d.com/Manual/Unity2D.html


## Team

* Scrum Master: Rosalba Monterrosas
* Product Owner: Luiz Zullino Junior
* Development Team: Brandon Basdeo, Lionel Munoz, Michael Hollinger, Ruth Betancourt


## Checklist

a)  Team decided on basic means of communications: DONE

b)  Team found a time slot to meet outside of the class: DONE

c)  Front and back end team leads chosen: DONE

d)  Github master chosen: DONE

e)  Team ready and able to use the chosen back and front-end frameworks: DONE

f)  Skills of each team member defined and known to all: DONE

g)  Team lead ensured that all team members read the final M1 and agree/understand it before submission: DONE