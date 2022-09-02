# Job Seeker Probability Tool

## Clone the project

`git clone https://github.com/spoorthihires/js-probability-app.git`

`cd js-probability-app`

## Pre-Requisites

Before you install the required application dependencies, make sure you have `Node JS` and `Yarn` installed.

- Node JS - Install LTS (long-term support) version of Node JS on your system. Node JS is available from the following site:
  https://nodejs.org
  The Node.js installation also includes npm.

- Yarn - Install the latest stable version of Yarn 1.x on your system. Yarn 1.x is available at:
  https://legacy.yarnpkg.com/docs/install
  <br/>Note: Do not install Yarn 2.x.

## Install application dependencies

Inside the project directory, run the following command. This will install all the required dependencies for the application

`npm install`

Under the `npm-config` folder, there is a `.npmrc` config file. Copy this file to the project root directory and run the install command again. This willinstall the TSF related dependencies

`cp npm-config/.npmrc .`

`npm install`

## Start the application

To start the application in the development mode, run the following command

`yarn start`

Open [http://localhost:3000](http://localhost:3000) to view the application in the browser.
