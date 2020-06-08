# Dev Connector

This Project is a Social Networking site for Developers to connect.
This project was developed as a code along from a Udemy course `MERN Stack Front to Back` created Brad Traversy
Developer can perform the following:
* Sign up/Login to the application
* Create their profile
* Add Experience & Education
* View all existing developers profiles
* Create a post and add comments to existing posts
* Delete his/her post/comment and account

## Tech-stack used

```
Front-end: HTML5, CSS3, JavaScript, React.js, Redux, axios
Back-end: JavaScript, Node.js, Express.js, MongoDB Atlas, REST API
```

## Getting Started

### Add a default.json file in config/ folder

```
{
    "mongoURI": "<Your_MongoDB_Atlas_URL_With_Credentials>",
    "jwtSecret": "<YourJWTSecret>",
    "githubClientId": "<YourGithubClientId>",
    "githubSecret": "<YourGithubSecretCodeForAuth>"
}
```

### Install server dependencies

```
npm install
```


### Install client dependencies

```
cd client
npm install
```

### Run Both Express and React from Root

```
npm run dev
```

## Deployment

This project is deployed on Heroku Cloud Application platform. The link to the deployed version is [here](https://secret-dusk-11551.herokuapp.com/)

## Authors

* **Suraj Singh** - *Initial work*
