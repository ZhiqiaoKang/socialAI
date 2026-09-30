# Getting Started with SocialAI

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, first, you need to enter a valid OpenAI key in the .env file, then can run:

## `npm start`

Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

## brief introduction
Social AI is a full-stack web application that combines generative artificial intelligence with social media functionality.

Users can register and log in to the platform, generate AI-generated images using natural language descriptions, or upload their own images or videos with captions. Generated or uploaded content is saved to the platform's content collection, which users can browse by image and video categories, or search for related posts by keywords or usernames.

The project offers a responsive image gallery and an immersive preview experience, supporting full-screen viewing, zooming, thumbnail navigation, and slideshow playback. Users can also manage and view published image content.

The front-end is built using technologies such as React, React Router, Material UI, Ant Design, Axios, React Photo Album, and Lightbox, and implements text-to-image generation functionality through the OpenAI interface. User identity is authenticated using tokens, and the front-end routing controls page access based on login status. The back-end provides services such as registration, login, file upload, post search, and deletion via REST APIs, and is currently deployed and running on Google Cloud Platform's App Engine.
