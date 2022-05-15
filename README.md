![MIT](https://img.shields.io/badge/License-MIT-blue)
# Employee-Profile

## Description

Welcome to the Employee-Profile project!

A Node.js command-line application that takes information about employees on a software engineering team and generates an HTML webpage that displays summarys for each person

You may visit the deployed [website](https://VMLujanJr.github.io/employee-profile/) to try it out for yourself!

## Table of Contents

- [Employee-Profile](#employee-profile)
  - [Description](#description)
  - [Table of Contents](#table-of-contents)
  - [User Story](#user-story)
  - [Acceptance Criteria](#acceptance-criteria)
  - [Mock-up](#mock-up)
  - [Technologies](#technologies)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Contributing](#contributing)
  - [Tests](#tests)
  - [Questions](#questions)
  - [License](#license)
  - [Extra Information](#extra-information)
  - [Getting Started](#getting-started)
  - [Bonus](#bonus)

## User Story

~~~
AS A small business owner
I WANT to be able to write and save notes
SO THAT I can organize my thoughts and keep track of tasks I need to complete
~~~

## Acceptance Criteria

~~~
GIVEN a note-taking application
~~~

- [x] WHEN I open the Note Taker
~~~
THEN I am presented with a landing page with a link to a notes page
~~~

- [ ] WHEN I click on the link to the notes page
~~~
THEN I am presented with a page with existing notes listed in the left-hand column, plus empty fields to enter a new note title and the note’s text in the right-hand column
~~~

- [ ] WHEN I enter a new note title and the note’s text
~~~
THEN a Save icon appears in the navigation at the top of the page
~~~

- [ ] WHEN I click on the Save icon
~~~
THEN the new note I have entered is saved and appears in the left-hand column with the other existing notes
~~~

- [ ] WHEN I click on an existing note in the list in the left-hand column
~~~
THEN I am presented with a menu with the option to add an engineer or an intern or to finish building my team
~~~

- [ ] WHEN I click on the Write icon in the navigation at the top of the page
~~~
THEN I am presented with empty fields to enter a new note title and the note’s text in the right-hand column
~~~

## Mock-up

![mockup](./lib/assets/images/mock-up.png)

## Technologies
HTML, CSS, Markdown, JavaScript, Node.js, Jest, Inquirer

## Installation

VSCode

## Usage

Please use this [video](https://drive.google.com/file/d/1y-zzffdqEfttWwcFoLaSlIKfW6oH_2b-/view) to learn how to start the application.

## Contributing

Contribute

## Tests

Test

## Questions

If you have any questions, you may direct them to VMLujanJr using the following links:

| Contact | Description |
| --- | --- |
| Name | Victor |
| Occupation | Developer |
| E-mail | <vmlujanjr@outlook.com> |
| GitHub | <https://github.com/VMLujanJr/> |

## License

MIT License

Copyright (c) 2022 Victor

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Extra Information

~~~
.
├── __tests__/             //jest tests
│   ├── Employee.test.js
│   ├── Engineer.test.js
│   ├── Intern.test.js
│   └── Manager.test.js
├── dist/                  // rendered output (HTML) and CSS style sheet      
├── lib/                   // classes
├── src/                   // template helper code 
├── .gitignore             // indicates which folders and files Git should ignore
├── index.js               // runs the application
└── package.json           
~~~

## Getting Started

~~~
The application should have a db.json file on the back end that will be used to store and retrieve notes using the fs module.

The following HTML routes should be created:

GET /notes should return the notes.html file.

GET * should return the index.html file.

The following API routes should be created:

GET /api/notes should read the db.json file and return all saved notes as JSON.

POST /api/notes should receive a new note to save on the request body, add it to the db.json file, and then return the new note to the client. You'll need to find a way to give each note a unique id when it's saved (look into npm packages that could do this for you).
~~~

## Bonus

~~~
You haven’t learned how to handle DELETE requests, but this application has that functionality in the front end. As a bonus, see if you can add the DELETE route to the application using the following guideline:

DELETE /api/notes/:id should receive a query parameter containing the id of a note to delete. In order to delete a note, you'll need to read all notes from the db.json file, remove the note with the given id property, and then rewrite the notes to the db.json file.
~~~