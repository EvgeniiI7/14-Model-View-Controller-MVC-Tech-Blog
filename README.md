# Tech Blog

This is a CMS-style blog site similar to a Wordpress site, where developers can publish their blog posts and comment on other developers’ posts as well. The application follows the MVC paradigm in its architectural structure, using Handlebars.js as the templating language, Sequelize as the ORM, and the express-session npm package for authentication.

## User Story
```
As a developer who writes about tech, I want a CMS-style blog site so that I can publish articles, blog posts, and my thoughts and opinions.
```
## User Experience

Given a CMS-style blog site, when I visit the site for the first time I am presented with the homepage, which includes existing blog posts if any have been posted; navigation links for the homepage and the dashboard; and the option to log in.

When I click on the homepage optio I am taken to the homepage. I click on any other links in the navigation I am prompted to either sign up or sign in. Then I choose to sign up I am prompted to create a username and password
When I click on the sign-up button my user credentials are saved and I am logged into the site
When I revisit the site at a later time and choose to sign in I am prompted to enter my username and password
When I am signed in to the site I see navigation links for the homepage, the dashboard, and the option to log out
When I click on the homepage option in the navigation I am taken to the homepage and presented with existing blog posts that include the post title and the date created
When I click on an existing blog post I am presented with the post title, contents, post creator’s username, and date created for that post and have the option to leave a comment
When I enter a comment and click on the submit button while signed in the comment is saved and the post is updated to display the comment, the comment creator’s username, and the date created
When I click on the dashboard option in the navigation I am taken to the dashboard and presented with any blog posts I have already created and the option to add a new blog post
When I click on the button to add a new blog post I am prompted to enter both a title and contents for my blog post
When I click on the button to create a new blog post the title and contents of my post are saved and I am taken back to an updated dashboard with my new blog post
When I click on one of my existing posts in the dashboard I am able to delete or update my post and taken back to an updated dashboard
When I click on the logout option in the navigation I am signed out of the site
When I am idle on the site for more than a set time I am able to view comments but I am prompted to log in again before I can add, update, or delete comments

## Description
A Tech Blog where you can create a username and make post to the community.  After logining in, you will see all the post you've made and see an option to make a new post.  On the homepage, you will see all the post from the community where you can make comments on and if needed, add new posts.  You can also edit or delete previous post incase of any errors.

## Installation
* npm i express sequelize mysql2<br>
* npm install --save sequelize<br>
* npm i bcrypt<br>
* npm i dotenv<br>
* npm i connect-session-sequelize<br>
* npm i express-handlebars<br>
* npm i express-session<br>

 [Link to deployed App](https://morning-ocean-66291.herokuapp.com)
