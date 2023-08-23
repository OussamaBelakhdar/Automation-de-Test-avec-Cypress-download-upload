# Automation-de-Test-avec-Cypress-download-upload
This project involves automated testing of file upload and download functionality using the Cypress testing framework.  
The tests are designed to run on the website "https://filebin.net/".  

## Table of Contents
- Setup  
- Tests  
- Running the Tests  
- Contributing  
- License  
- Contact  

## Setup
Before you proceed with running the tests, make sure you have the following prerequisites installed:

1. Node.js: Cypress is a Node.js module, so you need Node.js to install and run it. If you don't have Node.js installed, you can download it from Node.js website. You can verify your Node.js installation by running the following commands in your terminal:  
`node -v`  
`npm -v`
   
1. Cypress : Cypress is an end-to-end testing framework for web applications. Below is a step-by-step guide on how to install Cypress.
-**Create a new project folder**: If you don't already have a project where you want to add Cypress, create a new folder for your project and navigate into it:  
`mkdir my-new-project`  
`cd my-new-project`    
-**Initialize a new Node.js project**: Run the following command to create a new package.json file. This file will keep track of your project's dependencies, including Cypress.  
`npm init -y`    
-**Install Cypress**: Run the following command to install Cypress as a development dependency:  
`npm install cypress --save-dev`      
This command will add Cypress to your project's node_modules folder and package.json file.
-**Installez les plugins cypress-file-upload et cypress-downloadfile**:  
`npm install --save-dev cypress-file-upload`
`npm install --save-dev cypress-downloadfile`          
-**Run Cypress for the first time**: After installing Cypress, you can open it by running:  
`npx cypress open`  
This will launch the Cypress Test Runner. The first time you open it, Cypress will create a cypress folder in your project directory. This folder will contain example tests and configurations you can use as a starting point for your tests.  
   
#### After you have Node.js and Cypress installed 
- clone the repository:
`git clone <repository_url>`
- Change to the project directory:
`cd <repository_directory>`

## Tests
The project comprises the following test scenarios:

**Upload and Download in Zip Format:**: : This test uploads a file and downloads it in Zip format.The steps include:  
- Attaching the file "fileToUpload.jpg" to the input field with the ID fileField.
- Verifying the successful upload message.
- Clicking the "Download files" link.
- Extracting the Zip download link and constructing the absolute link.
- Downloading the file and verifying its content.
**Upload and Download in Tar Formatt**:  Similar to the previous test, this one focuses on downloading the uploaded file in Tar format. The steps are parallel to the Zip format test.   

## Running the Tests
To execute the tests, navigate to the project directory and run the following command:
`npx cypress run`  
Cypress will initiate the tests and present the results in the terminal.

## Contributing
You're welcome to contribute to this project! If you have suggestions, bug fixes, or new features, please submit a pull request or create an issue to discuss further.  
## License
This project is open source and released under the MIT License. You're free to use, modify, and distribute it according to the terms of the MIT License.  
## Contact
If you have any questions or comments, please contact the repository owner at oussamabelakhdar@gmail.com.    

This README provides a structured guide to the purpose, setup, execution, contribution, licensing, and contact details of the file upload and download tests conducted using Cypress.  
