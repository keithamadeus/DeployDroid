# DeployDroid the Pipeline Project

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

[GitHub Repository](https://github.com/keithamadeus/DeployDroid/tree/main)

[Deployed Link](https://deploydroid.onrender.com/)

## Description

I've embarked on a project to integrate a Continuous Integration/Continuous Deployment (CI/CD) pipeline into a full-stack application. My aim is to automate testing and deployment processes using GitHub Actions. Here's the breakdown:

- **CI:** When I make a Pull Request to the `develop` branch, GitHub Actions run Cypress component tests to ensure code quality.

- **CD:** Once the code from `develop` merges into `main`, another GitHub Action deploys the application automatically to Render.

## Table of Contents

- [Installation](#installation)

- [Usage](#usage)

- [Learning Points](#learning-points)

- [Author Information](#author-information)

- [Contributing](#contributing)

- [Tests](#tests)

- [License](#license)

## Installation

To set up this project: 
```
npm i
npm run build 
npm run seed 
npm run develop 
npm run cypress (if you want to check test in cypress app)
```
Make a change to the Feature branch, switch to Develop, and merge changes from Feature branch to Develop, got to GitHub, and merge Develop into the Main branch. Tests will automatically run, then render will deploy the updated code. 

## Usage

Here's how I'll use this setup:
- **Adding New Features:** I'll push new features to the `develop` branch via Pull Requests.
- **Testing:** Each Pull Request triggers GitHub Actions to execute Cypress tests. If tests pass, I can merge the code.
- **Deployment:** Merging to `main` from `develop` automatically deploys the application to Render, ensuring my app is always updated with major releases.

## Learning Points

Through this project, I've learned:
- The importance of CI/CD for maintaining code quality and deployment efficiency.
- How to configure GitHub Actions for both testing and deployment workflows.
- The significance of having a staging (`develop`) branch for testing before production (`main`) deployment.
- Practical experience with Cypress for component testing in a CI environment. This project is a step towards mastering automated software development practices, ensuring I can deliver clean, well-tested code with minimal manual intervention.

## Author Information

Keith Williams

## Contributing

N/A

## Tests

Automated Cypress testing and deployment processes using GitHub Actions.

## License

This project is licensed under the MIT license.

https://opensource.org/licenses/MIT

## Questions

If you have any questions, you can reach me at keith.amadeus.williams@gmail.com.

You can also visit my GitHub profile at [keithamadeus](https://github.com/keithamadeus).