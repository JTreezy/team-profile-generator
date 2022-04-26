# Team Profile Generator
## Description 
This is a Node.js command-line application that takes in information about employees on a software engineering team, then generates an HTML webpage that displays summaries for each person. 
## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Contributions](#contributions)
- [License](#license)
- [Github](#github)
- [E-Mail](#email)
- [Tests](#tests)
- [Questions](#questions)

## Installation <a name="installation"></a>
For this application, you will need to have node.js, jest, and inquirer installed in order for this application to work. 
## Usage Information <a name="usage"></a>
To use this application, you must go to the terminal and run the command "node index.js". However, this is after running "npm install" to make sure that you have all of the dependencies (jest/inquirer). Then you will be prompted to create your team. The prompt will ask for the manager's credentials before continuing on to create a team that can consist of any amount of engineers and/or interns. When finished, there is an option to finish building the team.  Afterwards, an HTML page will be created that will display a nicely formatted team roster. The email addresses on the HTML will open up your default email program and auto-populate the email address in the "to:" field. When you click on the Github username, that Github profile will open up in a new tab. 
## License <a name="license"></a>
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
## Contributions <a name="contributions"></a>
For any significant changes to the application, please open up an issue within Github in order to address and discuss what is needed to be changed or adjusted. For any minor adjustments or improvements, pull requests are welcomed and thoroughly encouraged.
## Tests <a name="tests"></a>
Please update tests when appropriate and necessary. The current tests that are being run are made and used through Jest.
The application must include Employee, Manager, Engineer, and Intern classes. The tests for these classes (in the _tests_ directory) must ALL pass.

The first class is an Employee parent class with the following properties and methods:

name

id

email

getName()

getId()

getEmail()

getRole()—returns 'Employee'

The other three classes will extend Employee.

In addition to Employee's properties and methods, Manager will also have the following:

officeNumber

getRole()—overridden to return 'Manager'

In addition to Employee's properties and methods, Engineer will also have the following:

github—GitHub username

getGithub()

getRole()—overridden to return 'Engineer'

In addition to Employee's properties and methods, Intern will also have the following:

school

getSchool()

getRole()—overridden to return 'Intern'
## Questions <a name="questions"></a>
If there are any questions or concerns about the application, here is a link to my GitHub profile:

-jtreezy([github.com/jtreezy](github.com/jtreezy))

If there are any additional questions, here is my e-mail address to reach me.

-digitalsigna@gmail.com


Grading Requirements
Note: If a homework assignment submission is marked as “0”, it is considered incomplete and will not count towards your graduation requirements. Examples of incomplete submissions include the following:

A repository that has no code

A repository that includes a unique name but nothing else

A repository that includes only a README file but nothing else

A repository that only includes starter code

This homework is graded based on the following criteria:

Deliverables: 15%
A sample HTML file generated using the application must be submitted.

Your GitHub repository containing your application code.

Walkthrough Video: 32%
A walkthrough video that demonstrates the functionality of the Team Profile Generator and passing tests must be submitted, and a link to the video should be included in your README file.

The walkthrough video must show all four tests passing from the command line.

The walkthrough video must demonstrate how a user would invoke the application from the command line.

The walkthrough video must demonstrate how a user would enter responses to all of the prompts in the application.

The walkthrough video must demonstrate a generated HTML file that matches the user input.

Technical Acceptance Criteria: 40%
Satisfies all of the preceding acceptance criteria plus the following:

Uses the Inquirer package.

Uses the Jest package for a suite of unit tests.

The application must have Employee, Manager, Engineer, and Intern classes.

Repository Quality: 13%
Repository has a unique name.

Repository follows best practices for file structure and naming conventions.

Repository follows best practices for class/id naming conventions, indentation, quality comments, etc.

Repository contains multiple descriptive commit messages.

Repository contains a high-quality readme with description and a link to a walkthrough video.

Review
You are required to submit the following for review:

A walkthrough video that demonstrates the functionality of the application and passing tests.

A sample HTML file generated using your application.

The URL of the GitHub repository, with a unique name and a readme describing the project.
