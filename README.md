# eCharger

eCharger Web App lets users search for [Charging Stations](https://frontend.challenges.tblx.io/graphiql) available in Portugal, and save their favorite ones.

---

### Requirements

- Node - version ^10
- NPM is automatically include with Node
- Yarn - can be installed with NPM. Run the command below:

> npm install --global yarn

- Visit [Yarn on Windows](https://classic.yarnpkg.com/lang/en/docs/install/#windows-stable) for more info on installation.

| WARNING: This application was create with yarn package. It's recommended that you use yarn to install and run the application |
| ----------------------------------------------------------------------------------------------------------------------------- |

---

## Getting Started

- Clone the repository to your local machine
- run yarn to install all the dependecies of the project

  > yarn

- run the application with yarn start. The application will open on default browser on localhost:3000

  > yarn start

## Testing the Project

- run the application with yarn start

  > yarn start

- run command 'yarn run cypress open'

  > yarn run cypress open

- It should open a new window for cypress
- Choose the HomePage test file (see image below)

<img alt='home-test' src='/home.PNG'>

- It should run on a new window on selected browser and automatically execute the tests (see image below)

<img alt='tests' src='/tests.PNG'>

- To see the code of the tests just open the file on cypress/integration/homePage.spec.js

## Build the project

- It's quite simple to build a react-app for production. Just run yarn build

  > yarn build
