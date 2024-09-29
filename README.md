# API Automation With Newman-Reporter-Htmlextra

## newman-reporter-htmlextra
![NewmanHtmlextraReporterLogo](https://github.com/user-attachments/assets/858d8648-353a-4d16-aa80-4b48a8ab0444) 


## Technology and Tool Used
- Postman
- Node Js
- Newman
- npm
- Visual Studio Code

## Prerequisites

- You must have installed node js to your system
- Postman
- NPM
- Newman

## Scenario of this project

- User Can't Login With Invalid Email
- User Can't Login With Invalid Password
- User Can't Login With Valid Email And Invalid Password
- User Can't Login With  Invalid Email And Valid Password
- User Can Login With Valid Credential
- User able to create a user with valid data
- User unable to create a user with invalid data
- User able to update a user with valid data
- User unable to update a user with invalid data
- User able to delete a user with valid data
- User unable to delete a user with invalid data

## API Documents

      https://documenter.getpostman.com/view/16548351/2sAXqzWJSD 

## How to run this project

- clone this project
- open this project in Visual Studio code

## npm install

             npm install
            
- check the npm version

         npm -v
  
## Newman Install

       npm install -g newman
  
- check the newman version


      newman -v

## Install Newman-Reporter-Htmlextra

The reporter works as a plugin with Newman so ensure that you have already installed that package globally, 
using npm install -g newman.

To globally install the htmlextra package:

      npm install -g newman-reporter-htmlextra

To use htmlextra as a library, install the package as a dependency into a nodejs project's package.json file using:
      
     npm install -S newman-reporter-htmlextra

## Usage

In order to enable this reporter, specify htmlextra in Newman's -r or --reporters option. The following command will create a new report in the ./newman directory, if the directory does not exist, 
it will be created as part of the Newman run.

      newman run collection.json -r htmlextra
