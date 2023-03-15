# Hosting a Full-Stack Application



this project  will  developed Full-Stack application built for a retailer and deploy it to a cloud service provider so that it is available to customers.we use the aws console to start and configure the services the application needs such as a database to store product information and a web server allowing the site to be discovered by potential customers.

# Udagram

The udagram application is a fairly simple application that includes all the major components of a Full-Stack web application.


## Table of Contents

- [Project Title](#Hosting-a-Full-Stack-Application)

- [Instructions](#instructions)

- [Table of contents](#table-of-contents)

- [Usage](#Usage)

- [Dependencies](#Dependencies)

- [Installation](#Installation)

- [Testing](#Testing)

- [Built With](#Built-With)

- [Applications Links](#Links)

- [License](#License-&-Copyright)


------


## Instructions

[(Back to top)](#table-of-contents)

- The documentation folder attached in the project folder includes separate pages on different topics:
     1. Infrastructure description.
     2. App dependencies.
     3. Pipeline process.
   
---

## Usage

[(Back to top)](#table-of-contents)

You can Install this project to your PC using clone the repo to your github account then Download It as a ZIP File to your PC.

or Clone it using GIT `git clone` if you access it from GITHUB.
`git clone https://github.com/amroabdelslam/project3-udagram.git`

---

## Dependencies

```
- Node v14.15.0 (LTS) version .

- AWS CLI .

- A RDS database running Postgres.

- A S3 bucket for hosting uploaded pictures.

```
---
## Installation

Provision the necessary AWS services needed for running the application:

1. In AWS, provision a publicly available RDS database running Postgres. 
1. In AWS, provision a s3 bucket for hosting the uploaded files.
1. install nvm package from here `https://github.com/coreybutler/nvm-windows#installation--upgrades`
1. install nodejs version 14.15.0 `nvm install 14.15.0` then use it `nvm use 14.15.0`
1. Export the ENV variables needed or use a package like [dotnev](https://www.npmjs.com/package/dotenv)/.
or use "set_env.sh" file and run command `source set_env.sh` in udagram console .
1. From the root of the repo, navigate udagram-api folder `cd  udagram-api` to install the node_modules `npm install`.
 After installation is done start the api in dev mode with `npm run dev`.
1. Without closing the terminal in step 1, navigate to the udagram-frontend `cd udagram-frontend` to intall the node_modules `npm install`. After installation is done start the api in dev mode with `npm run start`.
  
### Ports:
    • Server port 3000.
    • Database port 5432.
---
## Testing

This project contains two different test suite: unit tests and End-To-End tests(e2e). Follow these steps to run the tests.

1. `udagram-frontend`
1. `npm run test`
1. `npm run e2e`

There are no Unit test on the back-end


### Unit Tests:

Unit tests are using the Jasmine Framework.


### End to End Tests:

The e2e tests are using Protractor and Jasmine.

---

## Built With

- [Angular](https://angular.io/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework
---
## Applications Links

* Front-end : `http://udagram-project3.s3-website-us-east-1.amazonaws.com/`
* Back-end : `http://udagram-api-dev.eba-bjcqmjbm.us-east-1.elasticbeanstalk.com/`
* Github : `https://github.com/amroabdelslam/project3-udagram`

[(Back to top)](#table-of-contents)

**- Udacity**

**- EgFwd**

---

## License & Copyright

[(Back to top)](#table-of-contents)

**© Udacity - Amro Abdelslam .**
