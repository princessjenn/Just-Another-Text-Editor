# Progressive Web Application: Text Editor

## Description

Deployed Heroku Application [here](https://serene-sierra-16900.herokuapp.com/) 

Repository Link [here]
(https://github.com/princessjenn/readme-generator2.git)

This application helps a user to generate their own professional, quality README file in the command line interface based upon prompts given for each section of the README. The user will be prompted with questions to input in the command-line and once the program ends, they will have a README built based upon their input answers!


## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Tests](#tests)
- [Questions](#questions)



## Installation

In order to generate your own README.md file through the command-line, you will need to follow these steps to get your program running in the correct environment:

- Navigate to your local command line/terminal window, and change directories into the directory where you want to create a new repository.

```cd repos```

- Next, create a new directory called readmeGenerator using the command 

```mkdir readmeGenerator```

- Once directory is created, you’ll want to change directories into it

```cd readmeGenerator```

- Open directory into Visual Studio code by entering into the command line:

```code .```

- Once VS code has opened with the 'readmeGenerator' directory, open the integrated terminal associated with it, and in the command line type ```npm init -y``` ,which is used to initialize a new Node.js project with default settings.
 
- When you run ```npm init -y```, NPM creates a new package.json file in your current directory with default settings, including the project name, version number, description, entry point file, test command, and other metadata.

- Next, create a '.gitignore' file in the directory in order to store the ‘node_modules’ directory into. The purpose of ‘ignoring’ the node_modules is to reduce the repository size, because if you include it in your Git repository it can increase the repository's size significantly. This can make it slow to clone, push, or pull the repository.

- Once we’ve initialized the Node.js, we will install Inquirer with the command ```npm install inquirer@8.2.4```. Inquirer is a powerful and easy-to-use Node.js library for creating interactive command-line interfaces (CLIs)

- When the installation process is complete, we can implement Inquirer into our README generator project by ‘importing’ it at the top of our Javascript file (which reads the code TOP to BOTTOM), ‘import inquirer from 'inquirer’;’

- Lastly, we will create a 'index.mjs' file into the integrated terminal with the command ```touch index.mjs```. In Node.js, when you import a directory that doesn't have an 'index.js' file, Node.js looks for an 'index.mjs' file by default. The 'index.mjs' file imports two modules from other files in the same directory, and then exports them as an object with named properties. This allows other modules to import all the modules in the directory at once by importing the 'index.mjs' file.

- Once the index.mjs file is created, you will complete the process by running ```node index.mjs``` into the command line. 
This starts the Node.js runtime, and executes the JavaScript code in the 'index.mjs' file as a module.

Now we're ready to start coding!

## Usage

Assuming logic is added to the `index.js` to register a service worker, and the `webpack.config.js` file is updated to use the HTML webpack plugin and the Inject Manifest class of the workbox webpack plugin. To run and use the application through your viewport, my case being `localhost:8081`, you would follow these steps:

1. In VS Code, open the integrated terminal associated with the root of the directory
2. Assuming you have the programs and dependencies described above from the 'Installation' section, simply type `npm run start:dev` into CLI to start running the generator.
3. You will be presented with a console message in the terminal that the app is listening, and directs you to go to the viewport in your browser, `localhost:8081`
4. Once the program ends and the user has entered all of their inputs on the command line based upon the given prompts, the README.md file will be generated in your explorer on VS Code!


## License [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This project is licensed under the terms of the MIT license.


## Contributing

To contribute to the project: 

1. start by forking the repository and creating a new branch specifically for your new feature or bug fix.
2. It's important to adhere to the project's coding standards and properly format your code.
3. When committing changes, be sure to write clear and concise messages that describe the changes made.
4. If your contribution affects the user interface or experience, include screenshots or animated GIFs in your pull request to help reviewers understand the changes. 
5. Additionally, make sure your code is thoroughly tested and all existing tests pass before submitting the pull request.
6. Finally, provide a detailed description of your changes and explain why they're necessary.

Thanks for contributing! 



## Tests

To ensure that my Text Editor Appliation was functioning properly, I used the command `npm run start:dev` in the root of the the app's directory to start running my application, ensuring the it was listening on the correct port and rendering properly in the browser port. This allowed me to ensure that my imports and exports were applied to the client side vs. server side properly. What is great about PWAs is the offline usage, so that I can see when the app is working before deploying by correctly caching and storing data, enabling me to access content and perform tasks even without an internet connection. That way I am able to catch any potential bugs or errors early on configuration, ensuring that my final product was functional.
 
![Application Test](cache-test.png)

## Questions

> Have any Questions? You can contact me on Github [here](https://https://github.com/princessjenn)

> Or, email me for more questions: j.eckenrode@me.com