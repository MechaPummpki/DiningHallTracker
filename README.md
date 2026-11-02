## DiningHallTracker
## Problem:  
I've used the Purdue BoilerBites app for a while now, and it feels very clunky to use and a bit annoying to navigate. I want to make it easier for people to navigate the menus and see what food is available.  
## Solution:  
I want to solve the problem I have with the BoilerBites app by making a program that can scrape the dining hall sites and display the entire menu for the week, while allowing you to cycle through breakfast, lunch, and dinner easily and displaying your selected list of favorites at the top.  
## Tech Stack:  
Language: Python   

Imports: import json; from urllib.request import Request, urlopen; import requests   

UI Library: Reflex   

Data Storage: JSON files   

API: http://api.hfs.purdue.edu/menus/v2/locations/<Dining Court>/<MM-DD-YYYY>/   
## Build Plan:  
- Set up the Git Repo and environment
- Use a program to scrape the Purdue dining hall API
- Use a JSON parser to convert the data into Python format
- Save the data into tables
- Repeat 7 times for the whole week
- Display the week's menu
- Select between breakfast, lunch, and dinner
- Format with a UI library
## Eisenhower Matrix:   

[Eisenhower Matrix.pdf](https://github.com/user-attachments/files/34255943/Eisenhower.Matrix.pdf)

