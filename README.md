# team-profile-generator
This application creates a team.html file with the command line based on the users input.
The tests that are in the _tests_ folder all pass.
I made a parent class called Employee and added 3 sub classes which extend the employee class: engineer, intern and manager.
When a user starts the application, they're prompted to enter the team manager's: name, id, email and office number.
When a user enters those requirements, the user is presented with a menu with the option to: add an engineer, add an intern, finish building the team.
When a user selects the engineer option, the user is prompted to enter the following and then taken back to the menu:
name, id, email and github username.
When a user selects the intern option, the user is prompted to enter the following and then taken back to the menu:
name, id, email and school.

When a user decides to finish building their team, they exit the application and the HTML is generated.

Tools used: javascript, npm, cli, inquirer, jest
