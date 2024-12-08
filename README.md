# Continuous Integration N  Deployment

## Description
```md
This project is take the starter code and to create a CI/CD pipeline using GitHub Actions to run the component tests via Cypress when a Pull Request is made to the develop branch, and the application is deployed when code is merged from develop to the main branch. 
```

## User Story
```md
- AS A software engineer looking to integrate a CI/CD pipeline in a codebase
- I WANT a full-stack application that runs test cases when a Pull Request is made to the develop branch and automatically deploys to Render when the code is merged to main
- SO THAT I can ensure that all code integrations are clean and pass the proper requirements and that the application is constantly updated when major releases are made to the main branch
```


## Table of Contents

- [Introduction](#introduction)
- [Technology](#technology)
- [Usage](#usage)
- [Contact](#credits)
- [License](#license)

## Introduction
GIVEN a full-stack application
WHEN I upload new features to the application
THEN I should be making Pull Requests to a develop branch first
WHEN I create a Pull Request to a develop branch
![alt text](/client/assets/Main.yml-Checking_Tests-fr_features_to_develop.png)
THEN I should be executing a GitHub Action that checks the Cypress component tests
WHEN I see that the tests pass on GitHub Action
THEN I should see those test results on GitHub Action and merge the code
WHEN I push the code from the develop branch to the main branch
![alt text](/client/assets/DeployToRender-fr_Develop_to_Main.png)
THEN I should see that another GitHub Action triggers and should automatically deploy to Render
![alt text](/client/assets/DeployToRender-fr_Develop_to_Main-Render_status.png)


## Technology
[![React](https://img.shields.io/badge/Framework-React-00ff00?style=plastic&logo=React&logoWidth=10)](https://reactjs.org/)
[![Render Status](https://img.shields.io/badge/Deployed%20on-Render-blue?style=plastic&logo=render&logoWidth=10)](https://render.com/)
[![TypeScript](https://img.shields.io/badge/Language-TypeScript-00ff00?style=plastic&logo=TypeScript&logoWidth=10)](https://www.typescriptlang.org/)
[![npm](https://img.shields.io/badge/Tools-npm-ff0000?style=plastic&logo=npm&logoWidth=10)](https://www.npmjs.com/)
[![VS Code](https://img.shields.io/badge/IDE-VSCode-ff0000?style=plastic&logo=VisualStudioCode&logoWidth=10)](https://code.visualstudio.com/docs)

## Usage
- [Github Repo](https://github.com/dcruzel/ContinuousIntegrationNDeployment)
- [Website](https://continuousintegrationndeployment.onrender.com/)

## Resources

- Activity from bootcamp used 
    - Module 20: Activity 28 - Project

## Contact

Elizabeth D'Cruz
- [Github Profile](https://github.com/dcruzel)
- [Email](Liz.c.dcruz@gmail.com)

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

