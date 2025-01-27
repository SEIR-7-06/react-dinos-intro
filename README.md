# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png)    Dino Blog - React Edition

----

We have been contracted by a company (*Not Evil Inc.™*), to update their existing Dinosaur based blog platform to use React.JS. 

Before we jump ahead, let's build an example component for our new employer to show them how easy and fun React will be!

----
### Setup

Create a new react app called `dino-blog` using `create-react-app`.

----
### Create a React Component

Inside of `./src` folder, create a new React Component file called `Post.js`.

Write a new React component object that accepts the following **props**:

- `postTitle`
- `author`
- `content`: should render one or more paragraphs of content
- `comments`: should render one or more comments

Pass those **props** to the component.

**Hint:** an array will be passed in for the `content` and `comments` **props**. Within the `Post` component you'll loop through that array to display a list of paragraphs and a list of comments.

----
### Finished Product
Your final solution should look like the following rendered post:

![Solution for Project](images/props_solution.png)
