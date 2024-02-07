# Spring MVC Security<br>![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

## Description

A simple demo web application built with SpringBoot, Spring Security (passwords encrypted with bcrypt),
mySQL, JDBC, and Thymeleaf.  The application demonstrates how Spring Security can be used to protect routes and content
based on the role of the user (i.e. Employee, Manager, or Admin).  Employees with Roles of Manager and Admin have access
to routes/content that "regular" Employees can't access.

### App Screenshots

#### Login Page
![login page](/Screenshot1.png)

#### All Employees Page
![employees page](/Screenshot2.png)

#### Managers Only Page
![leaders page](/Screenshot3.png)

#### Admin Only Page
![systems page](/Screenshot4.png)

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)
- [Tests](#tests)
- [Questions](#questions)

## Installation

run from your code editor on localhost server.

## Usage
Routes and Content

To Login as a User with the Employee Role:
Login as user: john, password: fun123
Employee roles can log in to application and can see the login page which shows
username and role.  There are no links to any other pages.  User can log off with logout button.

To Login as a User with the Manager Role:
Login as user: mary, password: fun123
Manager Roles can log in to application and can see a link to a Leadership Meeting page, which can
be accessed.  Users with Employer roles cannot see this link.  If a user with an Employee role attempts
to access this route manually via the browser, they will see an access denied page.

To Login as a User with both Admin & Manager Role:
Login as user: susan, password: fun123
This user has been assigned both an Admin and a Manager role and can log in to application and can see links to both a
Manager Meeting and an IT Systems Meeting page, which can both be accessed.  Users with Employer roles cannot see this 
link.  If a user without the appropriate Role attempts to access these routes manually via the browser, they will see 
an access denied page.

## License
This application is covered under the MIT License.
<br>For more information: https://opensource.org/licenses/MIT

## Contributing
N/A

## Tests
N/A

## Questions
Contact Info<br>
GitHub user name: BillStephens2022<br>
Link to GitHub profile: https://github.com/BillStephens2022<br>
Email: stephensbill17@gmail.com