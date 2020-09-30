# DevConnector
social network for developers

react project created using the MERN stack!

project is part of the "MERN Stack Front To Back" course on Udemy.

# How to view
Site is live at https://www.dmdrive/devconnector (this is just a redirect to the actual address)

# How to use app
Register/Sign in to enter the web page

Without registering/signing in you may still see the current developers and their profiles

After signed in, you can fill out your profile with experiences, education, and social media links

You may look at current posts posted by users, comment and like posts. You can also create your own posts

# Front-end
Front-end is created using React

# Back-end
The back-end server utilizes node.js and express.js

# Database
MongoDB is used as the database. For privacy reasons my mongoURI and other private keys are not included in the repo

# Running locally
To run locally and have functionality you would need to create your own default.json in config and add your mongoDB key, and jsonwebtoken key.
Example from my default.json that is not included in the repo:

{
    "mongoURI": "yourkeyhere",
    "jwtSecret": "yourkeyhere",
}

Then in root folder in terminal enter: npm run dev


