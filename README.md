# automation-code-challenge-test
This is the automation technical challenge for Pear Deck. Read this README.md for instructions on guidelines and the task to solve.

## Clone the repo 
```bash
git clone  https://github.com/peardeck/automation-code-challenge-test.git
```
## Installing
```bash
yarn install
```
## Automation take home assignment 
 
Please use these credentials to login and to automate login flow 
1. username - e2eautomation@dev-edu-peardeck.com
2. password - pddemo1234

**Note**: Incase the credentials above doesnt work, please either create a gmail account for testing purposes or feel free to use your personal gmail account.

Read the steps below in full before planning and beginning your work
You are welcome to reach out to ask any questions, gain clarification, or gather requirements at any time.

## Setup
Please follow the steps and create one test to check login functionality and ensure at the end,
you verify a valid element on homepage https://app.peardeck.com/home/?action=signin&idProvider=google#

**Important** - The Login test should be completed in cypress but feel free to use other frameworks to help you formulate the solution and complete this assignment.

## Sample video covering login flow manually done

https://user-images.githubusercontent.com/87498845/141855222-914c287a-7d49-44af-bada-15a23100f527.mov


## Steps

1. Visit peardeck url - https://www.peardeck.com/
2. Click on Teacher login button on the top right 
3. Click on Login with Google button
4. Enter your gmail username 
5. Click on Next Button 
6. Enter your gmail password
7. Click on Next Button again
8. You should land on the homepage - https://app.peardeck.com/home/?action=signin&idProvider=google#
9. Verify any element on the homepage to complete the test

## Timing

You will have one week from the time you receive the challenge to complete and return your work.

## Delivery

Please return your solution as a zipfile of your git repo according to the instructions of the recruiter


## Review

After you deliver your work, one of our engineers will review your work
Should you pass and move onto team interviews with our engineering team, there will likely be questions or discussions relating to this work, so please be prepared to help explain/teach your work!

## Setup

1. Ensure you have git installed on your computer
2. Please make sure that your solution of adding login flow is submitted/done under cypress/integration/login.specs.js file path
