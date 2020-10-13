# Web Dev Basics

## Intro

The following exercises will test your knowledge in basic Javascript concepts.

Please start off by *forking* this repo, and then *clone* it to your local machine.

The different exercises are split into different js files and the `index.html` file includes a link to each of them.

To test your code, open the `index.html` file in your browser and either use the debugger or `console.log`s.

**Good Luck! :)**

***

## Exercise 1

In the `ex1.js` file you will find two things:
1. An object called `users`:
    - Each key is the name of the user
    - Each value is an object which contains the `age` of the user and the `city` he lives
2. A function named `getUserInfo`.
    - This function `prompt`s the user to input a name of a user and stores the user's input in a variable called `userName`

You should add two `console.log`s to this function. One should print the `age` for the `userName` that was entered, and the other should print the `city` for the `userName` that was entered.

*Uncomment the invokation of the function to test your work.

*Add and commit your code*.

***

## Exercise 2

In the `ex2.js` file you will find an array of objects named `citiesWeather`. Each object represents a single citiesWeather. Each cityWeather object has the following properties:
  - `name` - a string representing the name of the city
  - `temp` - a number representing the temperature
  - `humidity` - a number representing the humidity
  - `weather` - representing the weather forecast 

Create a function called `getAverageTempByWeather` that receives one paramter named `weather` (a string with a weather type). The function should loop over all of the cities and calculate the sum of all the temperatures for the cities in the weather received. Then, it should divide it by the number of cities that have this weather. The function should return the average sum. For example, if we invoke the function with `'Clear'` like so: `getAverageTempByWeather('Clear')`, the return value should be: `29.75`.

*Add and commit your code*.

***


## Extension

If you want to show us some of your skills in HTML and CSS, feel free to create something interesting with HTML and CSS. You'll need to create a `styles.css` file, and don't forget to link it in your `index.html` ;)

***

### *Add, commit, and push your code*.