# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

This is a simple Tic Tac Toe game using ReactJS
Documentation:
1. Set up folder structure
2. Build components logic
- Square 
- Board
3. Styling components:
- Square 
- Board
4. Build helper.js:
- Purpose: use to determining the winner
- Logic: create a 2D array of possible win patter, loop the board and if match return the winner
5. Create State
6. Create handleClick function
7. Create renderMoves function
8. Implement functions allow user to go back to particular move (implement jumpTo function)

What is used:
useState()
import { useState } from "react";
function foo (){
    const [initial value, function update state] =    useState(stateChanges);
}
   
import/export: 
    import: use to get build-in functions from other library
    export: export the functions so that those can be import in other files
JSX


