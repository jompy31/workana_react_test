# Challenge React.js for Workana

This repository contains my submission for the React.js challenge as part of the evaluation process for Workana. Below are the instructions and details for completing the challenge.

## Instructions

1. **Fork this Repository**: Create a fork of the public repository [reactchallenge.git](https://github.com/sebasworkana/reactchallenge.git) on your own GitHub account.

2. **Clone and Push**: Clone the forked repository to your local machine. Push it to a branch named `react-challenge`. Then, send a pull request to your main branch and provide access to the GitHub user `sebasworkana`.

3. **Main Challenge**: Create a page with a specific style and format as described below.

4. **Styling Requirements**: Enumerate all elements of the periodic table using CSS classes. Highlight the words in the first name and last name by applying appropriate styles.

5. **React-Redux Integration**: Install `react-redux` and utilize the `useDispatch` and `useSelector` hooks in your components. Implement `redux-thunk` for managing asynchronous actions. Avoid using older techniques for sharing data among components.

6. **Linting**: Use ESLint for maintaining code quality and consistency.

7. **NPM Scripts and Readme**: Create NPM scripts to run the project. Include clear instructions in the Readme.md file for setting up and running the project.

8. **Docker Compose**: Provide a Docker Compose file to facilitate running the project environment.

9. **GitHub Pages Hosting**: Host the web application on GitHub Pages for testing purposes.

## Live Version

You can view the live version of this project [here](https://workana-react.netlify.app/).


## Step-by-Step Guide
1. **Fork this Repository**: Create a fork of the public repository [reactchallenge.git](https://github.com/sebasworkana/reactchallenge.git) on your own GitHub account.

2. **Clone and Push**: Clone the forked repository to your local machine. Push it to a branch named `react-challenge`. Then, send a pull request to your main branch and provide access to the GitHub user `sebasworkana`.

    ```bash
    git clone https://github.com/sebasworkana/reactchallenge.git
    cd reactchallenge
    ```

3. **Install Dependencies**: Install the required dependencies using npm or yarn:

    ```bash
    npm install
    ```

    or

    ```bash
    yarn install
    ```

4. **Implement Redux**: Install `react-redux` and `redux-thunk` for state management:

    ```bash
    npm install react-redux redux-thunk
    ```

    or

    ```bash
    yarn add react-redux redux-thunk
    ```

    Create Redux store, actions, and reducer as needed.

5. **Create Components**: Develop necessary components for the application, such as `Header`, `NameInputs`, `Button`, and `PeriodicTable`.

6. **Style the Application**: Use CSS to style the application. Modify the `App.css` and other CSS files as necessary to achieve the desired appearance.

7. **Test the Application**: Run the application in your local environment to test and ensure it functions correctly:

    ```bash
    npm start
    ```

    or

    ```bash
    yarn start
    ```

8. **Deploy to GitHub Pages**: Once satisfied with the application, deploy it to GitHub Pages for online accessibility.

9. **Create Docker Compose File**: Optionally, create a `docker-compose.yml` file to facilitate running the application in Docker containers.

## How Redux Works on the Page

Redux is used on the page to manage the global state of the application. A Redux store is created to store shared data between components, such as the user's first and last name input. Actions are used to make changes to the state, while the reducer specifies how those changes affect the global state. Components can then access the global state using the `useSelector` and `useDispatch` hooks provided by `react-redux`, enabling efficient communication between components without the need to manually pass props.


## 👨🏻‍💻 About Me:

<img  src="./programming.gif" height="290px" align="right" />
<br>

- All about me is at **[My Website](https://jompy31.github.io/)**

- I’m currently working on `Machine learning with Python`

- I’m currently learning `React Native and machine learning`

- I will make a autonomous vehicle with AI to controller all the vehicle, due this project i made projects I am working in my own AI with chatbot with a personalized voice with a specific profile and it will talk with the customer and will save a conversation summary and the customer think the vehicule like a friend due an excellent AI, other application that i made to my personal project is: applications for exclusive videos like netflix with own specific videos, geolocaliser with a interface using in transparent display to use at the window and the car will have automatic driving and I read 3 physics books to develop the motor with radial and axial technologies with that improve the torque in the motor and less consume with myself technology and I will make the body of the vehicle analyzing thermodynamics, dynamic resistance, and all the relevant aspects in the plans that I have in my house and I hope to be able to patent once finished. 

## 🛠️ Technologies and Tools I use:

<p>
<img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"  height="25px"/>
<img alt="Django" src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white"  height="25px"/>
<img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"  height="25px"/>
<img alt="CSS3" src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"  height="25px"/>
<img alt=".NET" src="https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white"  height="25px"/>
<img alt="Javascript" src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E"  height="25px"/>
<img alt="Node.js" src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white"  height="25px"/>
<img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white"  height="25px"/>
<img alt="Java" src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white"  height="25px"/>
<img alt="PHP" src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white"  height="25px"/>
<img alt="React" src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"  height="25px"/>
<img alt="React Native" src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"  height="25px"/>
<img alt="R" src="https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white"  height="25px"/>
<img alt="Kotlin" src="https://img.shields.io/badge/Kotlin-0095D5?&style=for-the-badge&logo=kotlin&logoColor=white"  height="25px"/>
<img alt="Ruby" src="https://img.shields.io/badge/Ruby-CC342D?style=for-the-badge&logo=ruby&logoColor=white"  height="25px"/>
<img alt="C#" src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white"  height="25px"/>
<img alt="Dart" src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white"  height="25px"/>
<img alt="Svelte" src="https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00"  height="25px"/>
<img alt="Bootstrap" src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white"  height="25px"/>
<img alt="JQuery" src="	https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white"  height="25px"/>
<img alt="Spring boot" src="https://img.shields.io/badge/Spring boot-white?style=for-the-badge&logo=Spring boot&logoColor=green" height="25px"/>
<img alt="Flask" src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" height="25px"/>
<img alt="Flutter" src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" height="25px"/>
<img alt="MySQL" src="https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white" height="25px"/>
<img alt="MongoDB" src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white" height="25px"/>
<img alt="Unity" src="https://img.shields.io/badge/Unity-100000?style=for-the-badge&logo=unity&logoColor=white" height="25px"/>
<img alt="Amazon Web Services" src="https://img.shields.io/badge/Amazon_AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" height="25px"/>
<img alt="Powershell" src="https://img.shields.io/badge/Powershell-2CA5E0?style=for-the-badge&logo=powershell&logoColor=white" height="25px"/>
<img alt="git" src="https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white" height="25px"/>
<img alt="Linux" src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" height="25px"/>


</p>

## ❤️ Let's get connected:

<p>
  <a href="https://www.linkedin.com/in/jean-pierre-barnett-caruzo-452b9a1b1/" target="_blank"><img alt="LinkedIn" target="_blank" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"  height="30px"/></a>

  
</p>


## Activities and Information GITHUB:

<div align="center">
  <img align="center" src="https://github-readme-stats-anuraghazra1.vercel.app/api?username=jompy31&show_icons=true" />
  <img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=jompy31" alt="Jean_Pierre" />
  <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=jompy31&show_icons=true&layout=compact&langs_count=10" alt="jorneylopez" />
</div>
