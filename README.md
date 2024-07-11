# CIS2701 Fundamentals of Web Coding

**[ Module Ready for 2024/25 ]** 
A Visual Studio-based Development Container for CIS2701.

## Requirements

- [Docker Desktop](https://www.docker.com/products/docker-desktop/)
- [Visual Studio Code](https://code.visualstudio.com/) (with [Dev Containers]() extension installed)

## About: Dev Environment

The development environment contains everything you need for **CIS2701**. This includes all the neccessary directories for tutorials,tasks as well as the following configurations for:

- **Javascript**

  - [Node.js](https://nodejs.org/en) (A Javascript Framework)
  - [Mocha](https://github.com/mochajs/mocha) (A Javascript testing framework)

- **PHP**

  - [composer](https://getcomposer.org/) (A php package manager)
  - [phpunit](https://phpunit.de/) (a PHP unit testing framework)

### Extensions and Settings
- No VS Code extensions have been installed 
- The debugging for both JavaScript and PHP has already been configured for you. 

### FAQ

You will be required to test your coding using unit tests. The two framework you will use for this module are `Mocha` and `Phpunit`. To use these command line interface (CLI) tools with in the development container open up a new terminal (remembering to choose bash as the terminal shell) pane and enter the following:

- For JavaScript (`.js`) files: `mocha <path-to-unit-test-code>`

- For PHP (`.php`) files: `phphunit <path-to-unit-test-code>`

Replacing `<path-to-unit-test-code>` with the path to the file containing the unit test code. Please refer to the Web Teaching Environment for more information on how to use these tools.
