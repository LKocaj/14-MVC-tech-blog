<div id="top"></div>

<br />
<div align="center">
  <a href="https://github.com/othneildrew/Best-README-Template">
  </a>

  <h1 align="center">14. Model-View-Controller (MVC) Challenge: Tech Blog</h1>

  <p align="center">
    A CMS-style blog site where developers can publish their blog posts and comment on other developers’ posts!
    <br />
    <a href="https://tech-block-14-mvc.herokuapp.com"><strong>Heroku deployed project</strong></a>
    <br />
    <br />
  
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
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
    <li><a href="#usage">Usage</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)

Writing about tech can be just as important as making it. Developers spend plenty of time creating new applications and debugging existing codebases, but most developers also spend at least some of their time reading and writing about technical concepts, recent advancements, and new technologies. A simple Google search for any concept covered in this course returns thousands of think pieces and tutorials from developers of all skill levels!

Your challenge this week is to build a CMS-style blog site similar to a Wordpress site, where developers can publish their blog posts and comment on other developers’ posts as well. You’ll build this site completely from scratch and deploy it to Heroku. Your app will follow the MVC paradigm in its architectural structure, using Handlebars.js as the templating language, Sequelize as the ORM, and the express-session npm package for authentication.



<p align="right">(<a href="#top">back to top</a>)</p>



## Built With

![Javascript](https://img.shields.io/badge/-JavaScript-f7df1e?style=for-the-badge&logo=javascript&logoColor=black)

![MySQL](https://img.shields.io/badge/-MySql-4479a1?style=for-the-badge&logo=mysql&logoColor=white)

![Insomnia](https://img.shields.io/badge/-Insomnia-5849BE?style=for-the-badge&logo=insomnia&logoColor=white)

![Heroku](https://img.shields.io/badge/-Heroku-430098?style=for-the-badge&logo=heroku&logoColor=white)

![Node.js](https://img.shields.io/badge/-Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white) 
with the following npm packages
* `express.js` 
* `dotenv`
* `Sequelize`
* `bcrypt`
* `express-handlebars` 
* `express-session`
* `connect-session-sequelize`

## Preview
### Screenshots
![Homepage](./assets/preview1.png)
![Dashboard](./assets/preview2.png)
![Create New Post](./assets/preview3.png)
![Single post view](./assets/preview4.png)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
# Getting Started
GIVEN a CMS-style blog site

WHEN I visit the site for the first time

THEN I am presented with the homepage, which includes existing blog posts if any have been posted; navigation links for the homepage and the dashboard; and the option to log in
WHEN I click on the homepage option

THEN I am taken to the homepage

WHEN I click on any other links in the navigation

THEN I am prompted to either sign up or sign in

WHEN I choose to sign up

THEN I am prompted to create a username and password

WHEN I click on the sign-up button

THEN my user credentials are saved and I am logged into the site

WHEN I revisit the site at a later time and choose to sign in

THEN I am prompted to enter my username and password

WHEN I am signed in to the site

THEN I see navigation links for the homepage, the dashboard, and the option to log out

WHEN I click on the homepage option in the navigation

THEN I am taken to the homepage and presented with existing blog posts that include the post title and the date created

WHEN I click on an existing blog post

THEN I am presented with the post title, contents, post creator’s username, and date created for that post and have the option to leave a comment

WHEN I enter a comment and click on the submit button while signed in

THEN the comment is saved and the post is updated to display the comment, the comment creator’s username, and the date created

WHEN I click on the dashboard option in the navigation

THEN I am taken to the dashboard and presented with any blog posts I have already created and the option to add a new blog post

WHEN I click on the button to add a new blog post

THEN I am prompted to enter both a title and contents for my blog post

WHEN I click on the button to create a new blog post

THEN the title and contents of my post are saved and I am taken back to an updated dashboard with my new blog post

WHEN I click on one of my existing posts in the dashboard

THEN I am able to delete or update my post and taken back to an updated dashboard

WHEN I click on the logout option in the navigation

THEN I am signed out of the site

WHEN I am idle on the site for more than a set time

THEN I am able to view comments but I am prompted to log in again before I can add, update, or delete comments

<br>

## Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* npm
  ```sh
  npm init -y
  ```

## Installation

1. Clone the repo
   ```sh
   git clone https://github.com/your_username_/Project-Name.git
   ```
2. Install NPM packages

<br>

<!-- USAGE EXAMPLES -->
# Usage

AS A developer who writes about tech

I WANT a CMS-style blog site

SO THAT I can publish articles, blog posts, and my thoughts and opinions

<br >

<!-- LICENSE -->
# License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<!-- CONTACT -->
# Contact

Lawrence Kocaj 

Email: lawrencecaj@gmail.com
<br>
<br>
Project Link: [https://github.com/lkocaj/14-MVC-challenge](https://github.com/your_username/repo_name)
<br>
<br>
Heroku: https://mvc-14-techblog.herokuapp.com/ <br>
https://git.heroku.com/mvc-14-techblog.git
<br>
<br>
Youtube: https://www.youtube.com/channel/UCT9VNw7nEAY0jqPlHM6zlSw

<p align="right">(<a href="#top">back to top</a>)</p>
