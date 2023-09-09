[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# Logo-Maker

## Description

This app empowers freelance web developers to create custom logos without hiring a graphic designer. It uses inquirer to prompt users for logo preferences, such as up to three characters of text, text color, and shape (triangle, square, or circle) with a corresponding color. After answering the prompts, the app generates an SVG file with the user's selections. I also implemented unit testing for the first time, with a test suite consisting of three tests to ensure accurate shapes and colors. This app showcases the potential of back-end developers and the importance of unit testing, even for small projects. I added minor error handling for the first prompt, limiting text input to three characters. Future improvements could include additional error handling for SVG colors, more unit tests, and expanded font and polygon options. All in all, creating this app was a valuable learning experience that further developed my developer mindset.

## Table of Contents

- [Description](#Description)
  <a name="Screenshots"></a>

- [Screenshots](#Screenshots)
  <a name="Screenshots"></a>
- [Technologies-Used](#Technologies-Used)
  <a name="Technologies Used"></a>
- [Installation](#Installation)
  <a name="Installation"></a>
- [Usage-Information](#Usage-Information)
  <a name="Usage Information"></a>

- [Test-Instructions](#Test-Instructions)
  <a name="Test Instructions"></a>
- [License](#License)
  <a name="License"></a>
- [Questions](#Questions)
  <a name="Questions"></a>

## Live Screen Recording of Application Functionality

https://drive.google.com/file/d/1PjWCbuDGHb8yw71_b3QOi8BvOVbQemmZ/view

## Screenshots

logo generation

<img width="1470" alt="screen capture 1" src="./images/ScreenCap1.png">
<img width="1026" alt="screen capture 2" src="./images/ScreenCap2.png">
<img width="817" alt="screen capture 3" src="./images/ScreenCap3.png">

## Examples of Generated Logos

<img width="323" alt="sample circle logo" src="./images/Cir.png">
<img width="323" alt="sample square logo" src="./images/Sqr.png">
<img width="323" alt="sample triangle logo" src="./images/Tri.png">

## Technologies Used

This project utilizes Node.js v18, inquirer v8.2.4 (node package manager), and file system module (node package manager), as well as jest v29.5.0 (node package manager) for conducting unit testing.

## Installation

1. Clone the repo: git clone https://github.com/epalermobootcamp/Logo_Maker.git
2. To access, utilize VS Code. Installation is necessary if not currently installed.
3. To install node.js v16 using the terminal, refer to the documentation for the appropriate command. For instance, if you have homebrew, you can use the command 'brew install node@16'.
4. After installing node.js v18, use the command "npm init -y" in the terminal to create a package.json file for storing project files.
5. Using the terminal, run "npm i" to install the application's dependencies. For inquirer and jest, developers can install them directly from the command line using "npm i inquirer@8.2.4" for version 8.2.4 of inquirer and "npm i jest" for the latest version of jest.
6. Type "node index.js" in the terminal to run the application.

## Usage Information

To run the application, navigate to its directory using the command line, install dependencies (npm i), and run the command "node index.js". Answer the questions that follow and once done, a message will appear confirming the logo generation. Check the newly generated SVG file for your new logo.

For unit testing, refer to the Test Instructions section.

## Test Instructions

To perform unit testing, execute the command "npm run test" in the terminal. Currently, there is a single test suite containing three tests. This suite verifies that the render() method generates the correct string for the specified shape color in the associated SVG file.

<img width="797" alt="Test Result" src="./images/testResult.png">

## License

NOTICE: This application is covered under the MIT License

## Questions

If you have any questions about the repo, open an issue or contact me directly at [enrico.palermo@ymail.com](mailto:enrico.palermo@ymail.com).

![Avatar](https://avatars.githubusercontent.com/u/141057897?v=4&s=100)

Check out my other projects at [epalermobootcamp](https://github.com/epalermobootcamp)
