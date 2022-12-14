# Front End Capstone

Group Hack Reactor FEC project. When given only a wireframe and business requirements create a mock e-commerce product page.
Personally I was responsible for building out the Questions and Answers component and sub. components along with all testing related to the component. Other responsibilities being setting up Webpack for production and setting up testing environment for Jest and RTL. 

> ### Group members<br>
> Nick Amenda(Product Overview)<br>
> Cameron Montgomery(Q&A Component)<br>
> Jonathan Liang (Reviews). <br>

## Table of Contents

1. [Description](#description)
2. [Technical Overview](#technical-overview)
3. [Usage](#usage)
4. [Requirements](#requirements)
5. [Development](#development)
6. [Production](#production)
7. [Testing](#testing)

## Description

After completing the junior phase at Hack Reactor groups are assigned to complete a collaborative group project building out a product page of an e-commerce site. Students are given just a wireframe and business requirements to use and are tasked to plan and build the site. We used React, Express, Webpack, CSS, and Node.js to build the site with Jest and React Testing Library for testing. Along with meeting the business requirements we also were tasked with building out 70% test coverage of our component. Since our team consisted of 3, not 4, we were instructed to not include "Related Products" component.

[Provided Wireframe](https://xd.adobe.com/view/e600dc0f-454c-44e3-5075-7872d04189ff-9031/)

<div align="center">

![GIF demo - overview of site](https://github.com/CameronMontgomery/FEC/blob/master/demos/overview-640.gif)

</div>
<br>

### I was personally responsible for the Q&A section of the project.

<br>

<div align="center">

![GIF demo of Q&A component](https://github.com/CameronMontgomery/FEC/blob/master/demos/Q%26A-full.gif)

</div>

View my code contributions at <br> [/client/src/components/questionsComponent](https://github.com/Tribalash/FEC/tree/master/client/src/components/questionsComponent) <br>

Tests for component are accessible at <br>
[/client/src/\_\_tests\_\_/questions.test.js](https://github.com/Tribalash/FEC/blob/master/client/src/__tests__/questions.test.js)<br>

## Technical Overview

First Hack Reactor collaborative project. Project is the culmination of all the front-end skills students have been learning. Students learn to use proper Git workflows, reviewing commits and pull requests. Technical skills involve React (functional components and hooks), Node.js/Express.js is used to forward requests to the API adding authentication to ensure keys are not included in client bundles. Jest and RTL was used for testing and Webpack for bundling.

## Usage
In order to run the project locally please read [Requirements](#requirements) section for instructions setting up a local .env and for installing dependencies. Find further instructions for setting up the project for development or production in the [Development](#development) and [Production](#production) sections.

## Requirements

Node.js - version 16.0+

### Configuring .env
To run locally the project needs a github PAT key added to a .env. In the projects root you will find a file titled config.env. Add your GitHub PAT key to this file and rename it .env leaving it in the projects root.

### Installing Dependencies
From within the root directory:
> 1. Run ```npm install``` to install all required dependencies

## Development

Setting up the development environment:
> 1. Ensure dependencies are installed.
> 2. To run both server-dev and build-dev with watch flags, run ```npm run start-dev```
> 3. Navigate to localhost port 3000, http://localhost:3000

## Production

Creating production build:
>  1. Ensure dependencies are installed
>  2. To create production build files, run ```npm run build```
>  3. To start server, ```npm run start```

## Testing

To get a coverage report from Jest use script ```npm run test-coverage```, along with the console coverage report an HTML file will be created in the coverage directory located in the projects root.

To just run the jest tests in the console with no coverage report use script ```npm run test```.
