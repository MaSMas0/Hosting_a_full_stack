# Udagram
# CircleCI
[![MaSMas0](https://circleci.com/gh/MaSMas0/Hosting_a_full_stack.svg?style=svg)](https://app.circleci.com/pipelines/github/MaSMas0)

## Powered By 

![](https://d20vrrgs8k4bvw.cloudfront.net/images/open-graph/udacity.png)

This application is provided to you as an alternative starter project if you do not wish to host your own code done in the previous courses of this nanodegree. The udagram application is a fairly simple application that includes all the major components of a Full-Stack web application.

## Getting Started

### Dependencies

```
- Node v14.15.1 (LTS) or more recent. While older versions can work it is advisable to keep node to latest LTS version

- npm 6.14.8 (LTS) or more recent, Yarn can work but was not tested for this project

- AWS CLI v2, v1 can work but was not tested for this project

- A RDS database running Postgres.

- A S3 bucket for hosting uploaded pictures.

```

### Installation

Provision the necessary AWS services needed for running the application:

1. In AWS, provision a publicly available RDS database running Postgres. [udagram RDS Link](database-1.cwfocpfbwoyq.us-east-1.rds.amazonaws.com)
2. In AWS, provision a s3 bucket for hosting the uploaded files. [udagram S3 Link](http://udagram123bucket.s3-website.eu-central-1.amazonaws.com)
3. In AWS, provision an Elastic Beanstalk for hosting the server. [udagram EB Link](http://udagram-app-env.eba-uwjndmxh.us-east-1.elasticbeanstalk.com)
4. Export the ENV variables needed or use a package like [dotenv](https://www.npmjs.com/package/dotenv)/.
5. From the root of the repo, navigate udagram-api folder `cd starter/udagram-api` to install the node_modules `npm install`. After installation is done start the api in dev mode with `npm run dev`.
6. Without closing the terminal in step 1, navigate to the udagram-frontend `cd starter/udagram-frontend` to install the node_modules `npm install`. After installation is done start the api in dev mode with `npm run start`.

## Testing

This project contains two different test suite: unit tests and End-To-End tests(e2e). Follow these steps to run the tests.

1. `cd starter/udagram-frontend`
1. `npm run test`
1. `npm run e2e`

There are no Unit test on the back-end

### Unit Tests:

Unit tests are using the Jasmine Framework.

### End to End Tests:

The e2e tests are using Protractor and Jasmine.

## Built With

- [Angular](https://angular.io/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework

**Please note that the version of dependencies is mentioned in package.json**

### Contact Info for Programmer
* Name: _Mohamed Abd El-Samie Ahmad Mansour_
* Email: mmansour92@icloud.com  
