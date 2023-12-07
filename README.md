## CLI Contact Manager
<img align="right" src="https://media.giphy.com/media/du3J3cXyzhj75IOgvA/giphy.gif" width="100"/>

[![GitHub last commit](https://img.shields.io/github/last-commit/Alexandrbig1/goit-NodeJS-hw-01)](https://github.com/Alexandrbig1/goit-NodeJS-hw-01/commits/main)
[![GitHub license](https://img.shields.io/github/license/Alexandrbig1/goit-NodeJS-hw-01)](https://github.com/Alexandrbig1/goit-NodeJS-hw-01/blob/main/LICENSE)

This is a simple command-line interface (CLI) program built with ![Alt text](https://img.shields.io/badge/Node.js-339933.svg?style=for-the-badge&logo=nodedotjs&logoColor=white) for managing contacts. It allows you to perform basic operations on a ![Alt text](https://img.shields.io/badge/JSON-000000.svg?style=for-the-badge&logo=JSON&logoColor=white) file containing contact information such as ID, name, phone number, and email.

## Table of Contents

- [Features](#features)
- [Technologies](#technologies)
- [How to Use](#HowtoUse)
- [Examples](#Examples)
- [Screenshots](#Screenshots)
- [Issues](#Issues)
- [License](#License)
- [Feedback](#Feedback)
- [Connect with me](#Connectwithme)

## Features
- **View All Contacts:** Retrieve a list of all contacts stored in the ![Alt text](https://img.shields.io/badge/JSON-000000.svg?style=for-the-badge&logo=JSON&logoColor=white) file.
- **Get Contact by ID:** Find a specific contact using their unique identifier.
- **Delete Contact by ID:** Remove a contact from the list based on their ID.
- **Add New Contact:** Append a new contact to the ![Alt text](https://img.shields.io/badge/JSON-000000.svg?style=for-the-badge&logo=JSON&logoColor=white) file with a generated ID.

## Technologies Used
- ![Alt text](https://img.shields.io/badge/Node.js-339933.svg?style=for-the-badge&logo=nodedotjs&logoColor=white) The runtime environment for executing the CLI program.
- **Commander:** A framework for building command-line applications, providing a clean and structured way to define commands and options.
- **uuid:** Used for generating unique IDs for each contact.
- **fs/promises:** File system module for handling file operations asynchronously.

## How to Use

1. **Install Dependencies:**
    ``` bash
    npm install
1. **Run the CLI:**
    ``` bash
    node src/index.js --<command> [options]

## Available Commands

- **list:** Display all contacts.
    ``` bash
    node src/index.js --action list
- **get:** Get contact by ID.
    ``` bash
    node src/index.js --action get --id <contactId>
- **remove:** Delete contact by ID.
    ``` bash
    node src/index.js --action remove --id <contactId>
- **add:** Add a new contact.
    ``` bash
    node src/index.js --action add --name <name> --email <email> --phone <phone_number>

## Examples

- **List all contacts:**
    ``` bash
    node src/index.js --action list
- **Get contact by ID:**
    ``` bash
    node src/index.js --action get --id 05olLMgyVQdWRwgKfg5J6
- **Remove contact by ID:**
    ``` bash
    node src/index.js --action remove --id qdggE76Jtbfd9eWJHrssH
- **Add a new contact:**
    ``` bash
    node src/index.js --action add --name "John Doe" --email "john.doe@example.com" --phone "+1234567890"

## Project Preview

### Screenshots:

![goit-NodeJS-hw-01](./src/images/hw-1.jpg)
_Caption for Screenshot 1 (listContacts)_

![goit-NodeJS-hw-01](./src/images/hw-2.jpg)
_Caption for Screenshot 2 (getContactById)_

![goit-NodeJS-hw-01](./src/images/hw-3.jpg)
_Caption for Screenshot 3 (addContact)_

![goit-NodeJS-hw-01](./src/images/hw-4.jpg)
_Caption for Screenshot 4 (removeContact)_

## Issues

If you encounter any issues or have suggestions, please [open an issue](https://github.com/Alexandrbig1/goit-NodeJS-hw-01/issues).

## License

This project is licensed under the [MIT License](LICENSE).

## Feedback

I welcome feedback and suggestions from users to improve the application's functionality and user experience.

## Languages and Tools:

<div align="center">  
<a href="https://www.javascript.com/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/javascript-original.svg" alt="JavaScript" height="50" /></a>
<a href="https://nodejs.org" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/></a>
<a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/></a>
</div>

## Connect with me:

<div align="center">
<a href="https://linkedin.com/in/alex-smagin29" target="_blank">
<img src=https://img.shields.io/badge/linkedin-%231E77B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white alt=linkedin style="margin-bottom: 5px;" />
</a>
<a href="https://github.com/alexandrbig1" target="_blank">
<img src=https://img.shields.io/badge/github-%2324292e.svg?&style=for-the-badge&logo=github&logoColor=white alt=github style="margin-bottom: 5px;" />
</a>
<a href="https://stackoverflow.com/users/22484161/alex-smagin" target="_blank">
<img src=https://img.shields.io/badge/stackoverflow-%23F28032.svg?&style=for-the-badge&logo=stackoverflow&logoColor=white alt=stackoverflow style="margin-bottom: 5px;" />
</a>
<a href="https://dribbble.com/Alexandrbig1" target="_blank">
<img src=https://img.shields.io/badge/dribbble-%23E45285.svg?&style=for-the-badge&logo=dribbble&logoColor=white alt=dribbble style="margin-bottom: 5px;" />
</a>
<a href="https://www.behance.net/a1126" target="_blank">
<img src=https://img.shields.io/badge/behance-%23191919.svg?&style=for-the-badge&logo=behance&logoColor=white alt=behance style="margin-bottom: 5px;" />
</a>  
</div>
