# README Inquirer Generator
    
![License](https://img.shields.io/static/v1?label=license&message=MIT&color=yellowgreen) 
    
A README generator that uses the Inquirer.js package to get user input from which the application will generate a formatted README for a new project in a specified target directory.
    
## Table of Contents
    
* [Installation](#Installation)
    
* [Usage](#Usage)
    
* [Contributing](#Contributing)
    
* [Tests](#Tests)
    
* [License](#License)
    
* [Author](#Author)
    
## Installation
    
To generate your own README, first enter Git Bash. Then clone the repository with the following link: [README Inquirer Generator Repository](https://github.com/raulds-fmtx/README-Inquirer-Generator.git).\n\nNext run `npm install inquirer` in order to install the required npm package dependencies in your cloned directory.\n\nThen run the application with the command `node index.js`.
    
## Usage
    
When you run `node index.js`, you will be prompted by the `inquirer` package to answer a series of questions in the command line about your GitHub and project.\n\nFrom there, the application will generate a markdown file and a table of contents for the README based on your response to the Inquirer prompts. The README will also include a badge for your repo's license.\n\nLastly, `fs.writeFile` is used to generate your project's README.md file. Check out the [`ExampleREADME.md`](https://github.com/raulds-fmtx/README-Inquirer-Generator/blob/main/output/ExampleREADME.md) in this repo as an example.
    
[Click Here to View a Demo.](https://drive.google.com/file/d/1e9Jf5jJXXUQQ7CGS1Bz-peptH6UfDYJX/view?usp=sharing)
    
## License
    
This project is license under the MIT License - see the [License](https://choosealicense.com/licenses/mit/)
    
## Author
    
Raul Santos
    
Github: [raulds-fmtx](https://github.com/raulds-fmtx)
Repo: [README-Inquirer-Generator](https://github.com/raulds-fmtx/README-Inquirer-Generator)