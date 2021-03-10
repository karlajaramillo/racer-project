# Welcome to the Hedgehog Simulation Game

## Project Introduction
Let's choose a track and your hedgehog to start the race! You will need to accelerate your racer by clicking an acceleration button. A live updated leaderboard will show player positions and their progress on the track. You still have time to win, just accelerate to be the winner! 
Finally, when the hedgehogs finish the race, the results will be displayed and you will know who is the winner!

## Aim of the Project
This is the final project of the Intermediate JavaScript Nanodegree Program from Udacity. The main purpose of this is to use Asynchronous Programming with JavaScript. Promises are the primary method for dealing with API responses in this game. And Async/Await syntax are used with API calls and internal logic to handle game processes.

### Start race
--------------------------------
<img width="350" alt="92FA7665-AF50-4D03-A8B3-393E351D46A7" src="https://user-images.githubusercontent.com/8181053/110620156-fa57c400-8198-11eb-82eb-09363b68cfae.png">

### Select racer and track
--------------------------------
<img width="350" alt="183BD7B7-28EA-499C-9DB3-78718C9788A3" src="https://user-images.githubusercontent.com/8181053/110620225-0fccee00-8199-11eb-8e5d-bfcf60b7f192.png">

### Get ready for the race 
--------------------------------
<img width="350" alt="Screenshot 2021-03-10 at 10 07 21" src="https://user-images.githubusercontent.com/8181053/110620285-22dfbe00-8199-11eb-8d77-0ddd1f055c72.png">

### Leaderboard and progress
--------------------------------
<img width="350" alt="Screenshot 2021-03-10 at 10 07 54" src="https://user-images.githubusercontent.com/8181053/110620354-35f28e00-8199-11eb-885d-b5354292c8ec.png">

### Results and start a new race
--------------------------------
<img width="350" alt="Screenshot 2021-03-10 at 10 09 39" src="https://user-images.githubusercontent.com/8181053/110620391-3f7bf600-8199-11eb-85ed-70a2cae76573.png">


## API provided by Udacity
--------------------------------
A pre-built API provided by Udacity will create the race selected by the players and return a stream of information lasting the duration of the race, resulting in a final ranking of racers. The API is provided in the form of a binary so that you can run it on any system. Because of this, you cannot edit the API in any way, it is just a black box that we interact with via the API endpoints.


## Getting started
1. The first step you need to do is clone this repository. 

2. To run the server, locate your operating system and run the associated command in your terminal at the root of the project.

| Your OS               | Command to start the API                                  |
| --------------------- | --------------------------------------------------------- |
| Mac                   | `ORIGIN_ALLOWED=http://localhost:3000 ./bin/server-osx`   |
| Windows               | `ORIGIN_ALLOWED=http://localhost:3000 ./bin/server.exe`   |
| Linux (Ubuntu, etc..) | `ORIGIN_ALLOWED=http://localhost:3000 ./bin/server-linux` |


#### WINDOWS USERS -- Setting Environment Variables
If you are using a windows machine:
1. `cd` into the root of the project containing data.json 
2. Run the following command to add the environment variable:
```set DATA_FILE=./data.json```

Note that this process will use your terminal tab, so you will have to open a new tab and navigate back to the project root to start the front end.

2. Top start the frontend, open another terminal tab and being at the root of this project, install the dependencies by running `npm install && npm start`. So, you should be able to access http://localhost:3000.






