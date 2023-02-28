# Incubeta take home assignment - Frontend developer

## Business case

We work a lot with forms and input data (yeah, all the boring sh*t). To keep everything DRY we favor to use component libraries like [Material UI](https://mui.com/material-ui) and [React hook form](https://react-hook-form.com/). In this assignment we ask you to come for a solution for a simple form use-case that you would encounter IRL at Incubeta.


## Before you start - preparation

- Make sure you book enough time for yourself to complete this assignment. Based on our experience maximum 2-3 hours should be enough to deliver a solution.
- Your solution should be in a private repository. Once you created one please don't forget to invite us, so we can track your progress. Our accounts: https://github.com/S4n3L, https://github.com/miguelosana, https://github.com/baspenny
- Use commits and commit messages as you would work in our team already. We intend to check your timestamps to know how much time you needed to spend with certain tasks.
- Please make sure that your application is production-ready and runs in a docker environment. We are happy to see a good enough test coverage and a readme file that describes how we can deploy and use the application.

## Your assignment

We work agile and we describe everything with user stories so we created one for this specific assignment as well:

Story: Create a simple wizard to collect user input and save it to the react state
Description: As a user, I want to see wizard with two pages, where I can give some input values on the first page and see the result on the second page

AC:

* should use react with typescript in the implementation
* should use a Material UI stepper component with two input fields and a next button on the first screen
* the first inputs should use the textInput MUI component where I can type in my name
* the second input should be a select MUI component and should contain country names
* should validate the fields when the user clicks on next to go to the next wizard page, based on the following criteria:
* first input should accept alphanums only
* second input - must be at least on country selected
* should show the entered data on the wizard step2 screen after the user clicks on next button
* should show a back button on the wizard step2 screen and make sure the data is still populated when the user goes back
* should use react-hook-form to manage the inputs

MUI component references:

https://mui.com/material-ui/react-text-field/
https://mui.com/material-ui/react-stepper/
https://mui.com/material-ui/react-select/

React hook form reference:

https://react-hook-form.com/

Please estimate this story. If it more complex that you can deliver in two/three hours, please let us know and we can negotiate about the scope!

***We wish you a great time with this assignment. Trust us: you have nothing to fear and we hope we can welcome you in our team soon! See you on the other side! :)***
