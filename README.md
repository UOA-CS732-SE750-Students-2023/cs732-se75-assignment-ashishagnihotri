# Building Quick Interactive Graphs with Plotly.js

Get started with building graphs with React using the react-plotly.js library. Requisite information is mentioned in the Documentations section

## Documentations
1. Get started with the basics of [plotly.js](https://plotly.com/javascript/)
2. Checkout the documentation for [react-plotly.js](https://plotly.com/javascript/react/) which is a react friendly plotly.js library very similar to plotly.js (this is the library that is used in the project)
3. Checkout the code for the open source [React Plotly.js Library](https://github.com/plotly/react-plotly.js/)
4. Get started with basics of React, checkout the [React documentation](https://reactjs.org/).

## Project Structure 
* Components (`src/components`) contains 4 JS files, 3 are used for making the components responsible for making the graphs (types of graphs used and their documentation can be found in the section below). 1 JS file contains data used in the other 3 components

* Pages (`src/pages`) contains 3 JS files that help routing the user through all the 3 types of graphs used in the project. These 3 files further go to their respective graph component types

* index.html (`public`) contains sample, untouched html code that project came with time of initialization

Documentation for the Coinbase API (https://docs.cloud.coinbase.com/exchange/reference/exchangerestapi_getproductcandles) used to make the time Series Chart

#### The Link to the 3 types of graphs that were used in this project
1. Line Chart (https://plotly.com/javascript/line-charts/)
2. Topographical Chart (https://plotly.com/javascript/3d-surface-plots/)
3. Time Series Chart (https://plotly.com/javascript/time-series/)


This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## How to run
### Prerequisites
Install [Node.js](https://nodejs.org/en) which includes [Node Package Manager] (https://docs.npmjs.com/getting-started)

#### Setting up the Project
Just install the dependencies already available in the packag.json file by running the command
`npm install`

In the project directory, you can run:
`npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\

## Further Reading Material (Tutorials/Articles)
1. Using Plotly.js with Angular and Firebase - https://www.youtube.com/watch?v=Ga0vrqed6Ho
2. Introduction to Plotly.js - https://www.youtube.com/watch?v=GVrjv9ajsJ0&t=47s
3. Reasons why you may avoid using D3.js library directly (and instead use plotly.js that uses d3.js) - https://medium.com/@PepsRyuu/why-i-no-longer-use-d3-js-b8288f306c9a#:~:text=As%20you%20can%20see%2C%20there's,them%20using%20your%20existing%20framework.