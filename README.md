# Udagram

This application is provided to you as an alternative starter project if you do not wish to host your own code done in the previous courses of this nanodegree. The udagram application is a fairly simple application that includes all the major components of a Full-Stack web application.

## Getting Started

1. Clone this repo locally into the location of your choice.
1. Move the content of the udagram folder at the root of the repository as this will become the main content of the project.
1. Open a terminal and navigate to the root of the repo
1. follow the instructions in the installation step

The project can run but is missing some information to connect to the database and storage service. These will be setup during the course of the project

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

1. In AWS, provision a publicly available RDS database running Postgres. <Place holder for link to classroom article>
1. In AWS, provision a s3 bucket for hosting the uploaded files. <Place holder for tlink to classroom article>
1. Export the ENV variables needed or use a package like [dotnev](https://www.npmjs.com/package/dotenv)/.
1. From the root of the repo, navigate udagram-api folder `cd starter/udagram-api` to install the node_modules `npm install`. After installation is done start the api in dev mode with `npm run dev`.
1. Without closing the terminal in step 1, navigate to the udagram-frontend `cd starter/udagram-frontend` to intall the node_modules `npm install`. After installation is done start the api in dev mode with `npm run start`.

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

-------------------

## PROJECT LINKS

[GITHUB REPO](https://github.com/Abdul-Rahman1321/Udagram)

[SERVER](http://udagram-api-dev.eba-ypgxhz5x.us-east-1.elasticbeanstalk.com/api/v0)


[UDAGRAM HOME PAGE](http://deployudagrambucket.s3-website-us-east-1.amazonaws.com)


----------------------------

## INFRASTRUCTURE 

> IN this project we used aws services to deploy our web app

- ***RDS DATABASE*** to host the database with the endpoint :*database-1.cc5yionnyy5m.us-east-1.rds.amazonaws.com* 


- ***ELASTIC BEANSTALK*** service that run the application on web server : http://udagram-api-dev.eba-ypgxhz5x.us-east-1.elasticbeanstalk.com/api/v0



- ***S3 BUCKET*** to host the ***udagram*** web app on :
http://deployudagrambucket.s3-website-us-east-1.amazonaws.co


----------------

## INFRASTRUCTURE DIAGRAM

<a href="https://seupload.com/uzH/diag.PNG" target="_blank" title="Download from SeUpload, share and manage your files for free"><img src="https://cloudse1.seupload.com/cache/plugins/filepreviewer/17533/9fbccdb47ba7964de3d940a1cde9bcb86cd064926be6483cb294e63a908c0b76/900x900_cropped.jpg"/></a>

-------------

## CIRCLECI 

### steps :
- #### installing orbs :
```
orbs:
  node: circleci/node@5.0.0
  aws-cli: circleci/aws-cli@2.0.6
  eb: circleci/aws-elastic-beanstalk@2.0.1
```
- ### installing the frontend 

- ### installing the backend 

- ### building the frontend 

- ### building the backend 

- ### deploying the frontend 

- ### deploying the backend 


> The circleci pipline starts automatically when any change is done by the developer and pushed to the git repo ... 

## DIAGRAM

<a href="https://seupload.com/uzL/circ_uda.png" target="_blank" title="Download from SeUpload, share and manage your files for free"><img src="https://cloudse1.seupload.com/cache/plugins/filepreviewer/17537/84d5b7a0291f126778b22cc490054916b847cf4bbc8c6cce3cfa391dfbb684ff/900x900_cropped.jpg"/></a>
