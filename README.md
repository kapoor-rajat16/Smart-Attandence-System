<div align="center">
 
<h1 align="center">Smart Attendence System</h1>

[![](https://img.shields.io/badge/Made_with-Nodejs-red?style=for-the-badge&logo=node.js)](https://nodejs.org/en/)
[![](https://img.shields.io/badge/IDE-Visual_Studio_Code-purple?style=for-the-badge&logo=visual-studio-code)](https://code.visualstudio.com/  "Visual Studio Code")
[![](https://img.shields.io/badge/Database-MongoDB-green?style=for-the-badge&logo=mongodb)](mongodb.com "MongoDB")
[![](https://img.shields.io/badge/Made_with-Python-blue?style=for-the-badge&logo=python)](https://www.python.org/)

</div>

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

Smart Attendence System is a cutting-edge attendance recorder which records attendance of the students using our face recognition model which has an accuracy of about 97%.  Using face recognition, you can easily record attendance and have access to in-depth analysis and a wide range of functionalities. Because of the covid-19 pandemic, stringent guidelines have been established, and precautions must be made to minimise unnecessary physical encounters. As a result, our method has shown to be effective in eliminating the requirement for any type of physical interaction while collecting and analysing attendance.


### Built With

* [NodeJS](https://nodejs.org/en/)
* [ExpressJS](https://expressjs.com/en/starter/generator.html)
* [Python](https://www.python.org/)
* [OpenCV](https://opencv.org/)

<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

Update to the latest version of npm
* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/staticshreyas/Attendance-Portal.git
   ```
2. Install NPM packages
   ```sh
   npm install
   ```
3. Install Python packages
   
   ```sh
   cd ./Py-Scrpits 
   pip install requirements.txt
   ```

### Running the project
1. Start the express server from the root directory
   ```sh
   npm start
   ```
2. Start the flask server
    ```sh
    cd ./Py-Scripts
      python app.py
   ```
3. Start the mongo server
    ```sh
    mongod --dbpath YOUR_PATH
   ```

## Contact
Rajat Kapoor - rajatkapoor214@gmail.com