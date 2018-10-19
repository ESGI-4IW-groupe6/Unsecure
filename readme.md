# Unsecure project  

[![Build Status](https://travis-ci.com/ESGI-4IW-groupe4/Unsecure.svg?branch=Develop)](https://travis-ci.com/ESGI-4IW-groupe4/Unsecure)


## Description

Unsecure is a website in Symfony 2.3 containing security breach :blush:

---

## Installation


### Step1

#### Make a git clone of the project:
`` 
    git clone <URL de git> 
``     
### Step2

#### Go to the clone folder:
`` 
    docker-compose build 
`` 
### Step3

#### Install Vendor:
`` 
    docker run --rm -v $PWD:/app composer install
`` 
### Step4

#### Launch the containers:
`` 
    docker-compose up -d
`` 
### Useful tools:

#### To turn off the containers:
`` 
   docker-compose down 
`` 
#### To display the containers:
`` 
    docker ps 
`` 
#### To view the images:
`` 
    docker images
`` 
        

---

## Licence

This project is under MIT license. You can found them [here](LICENSE)

---

## Deployment

> Add additional notes about how to deploy this on a live system

---

## Contributing

Please read [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) for details on our code of conduct, and the process for submitting pull requests to us.
See also [CONTRIBUTING.md](CONTRIBUTING.md) to see how to contribute on our project, 
[PULL_REQUEST_TEMPLATE.md](PULL_REQUEST_TEMPLATE.md) to see how to create a PR as we ask for and finally 
[ISSUE_TEMPLATE.md](ISSUE_TEMPLATE.md) to see how to create great issues on our project.
---

## Authors

- SETTBON Dylan :white_check_mark:
- BUENO Jerome :white_check_mark:
- DELENCLOS Wladimir :white_check_mark:
- DUMONT Antoine :white_check_mark:
