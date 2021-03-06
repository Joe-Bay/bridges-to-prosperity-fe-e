# Bridges To Prosperity

You can find the deployed project at https://b.bridgestoprosperity.dev/

You can find the demo video for this project at https://youtu.be/UkJIj0PbvIk


## 4️⃣ Contributors


|                                           [Devin Moore](https://github.com/devjaymoe)                                           |                                       [Joo Woon Kang](https://github.com/joowoonk)                                        |                                                     [Robert Misch](https://github.com/RobertMisch)                                                     |                                          [Jessica Cooper](https://github.com/JessicaGCooper)                                           |
| :-----------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------: |
|                     [<img src="./src/styles/imgs/devin.jpg" width = "200" />](https://github.com/devjaymoe)                     |                 [<img src="./src/styles/imgs/Joowoon.jpg" width = "200" />](https://github.com/joowoonk)                  | [<img src="https://www.dalesjewelers.com/wp-content/uploads/2018/10/placeholder-silhouette-male.png" width = "200" />](https://github.com/RobertMisch) |                     [<img src="./src/styles/imgs/Jessica.png" width = "200" />](https://github.com/JessicaGCooper)                     | [<img src="./" width = "200" />](https://github.com/) |
|                     [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/devjaymoe)                      |                   [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/joowoonk)                   |                                [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/RobertMisch)                                |                      [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/JessicaGCooper)                       |
| [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/in/devin-jay-moore) | [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/in/joowoonk/) |                     [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/)                      | [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/in/jessica-gertig-cooper/) |

<br>

## Project Overview

1️⃣ [Trello Board](https://trello.com/b/x1iIzJdj/labs25bridgesjessica)

1️⃣ [Product Canvas](https://whimsical.com/CenFtxG9x65uEptPgBSEQw)

[<img src="./src/styles/imgs/btp.png" width = "600" />](https://b.bridgestoprosperity.dev/)

<h2>Description</h2>

Our website receives and displays from data from our backend API. Displays data on mapbox interface, using React Map Gl, and also on ant design table. Users are unable to interact with the data on the mapbox interface and the table to view additional information and edit data points.

## 4️⃣ Key Features

- Mapbox Interface (React Map Gl)
- Ant Design Table
- Yup Validations Formik Form

## 1️⃣ Tech Stack

### Front end built using:

- Context API
- Okta
- Ant Design
- Axios
- React-map-gl
- React-map-gl-geocoder
- React-router-dom
- Formik & Yup
- Node-Sass


#### _Front end framework goes here_

- React

Why did you choose this framework?

- Our team had experience with the React Framework.

List the rest of the front end features and libraries in the same format as the framework above.

#### Front end deployed to `AWS`

https://b.bridgestoprosperity.dev/

#### [Back end] built using:

https://github.com/Lambda-School-Labs/Labs25-Bridges_to_Prosperity-TeamB-be

#### back end framework goes here

- nodejs
- express
- postgreSQL
- Docker

# APIs

## 2️⃣ Authentication API here


Okta API for Authentication:


The Okta Identity Cloud gives you one trusted platform to secure every identity in your organization and connect with all your customers.

## 3️⃣ Environment Variables


```md
REACT_APP_CLIENT_ID=0oalwt....
REACT_APP_OKTA_ISSUER_URI=https://auth.../default
REACT_APP_API_URI=http://localhost:8000
REACT_APP_MAPBOX_TOKEN='pk.eyJ1Ij......'
```

## 5️⃣ Content Licenses

🚫For all content - images, icons, etc, use this table to document permission of use. Remove the two placeholders and add you content to this table

| Image Filename    | Source / Creator | License                                          |
| ----------------- | ---------------- | ------------------------------------------------ |
| green bridge icon | Icons8           | [Icons8](https://icons8.com/license)             |
| rings.svg         | Sam Herbert      | [MIT](https://github.com/SamHerbert/SVG-Loaders) |


All the other images provided from Bridges to Prosperity

## 4️⃣ Testing

We used JEST to have basic testing for the front end.

## Other Scripts

```json
 "scripts": {
    "start": "craco --max_old_space_size=4096 start",
    "build": "craco --max_old_space_size=4096 build",
    "test": "craco test --env=jest-environment-jsdom-sixteen",
    "eject": "react-scripts eject",
    "prettier": "prettier --write \"**/*.+(js|jsx|json|css|md)\"",
    "coverage": "npm test -- --coverage --watchAll=false",
    "lint": "eslint 'src/**/*.{js,jsx}' --fix",
    "format": "prettier --write 'src/**/*.{js,jsx,css,scss}'",
    "storybook": "start-storybook",
    "deploy-storybook": "storybook-to-ghpages"
  },
```

### Feature Requests

We would love to hear from you about new features which would improve this app and further the aims of our project. Please provide as much detail and information as possible to show us why you think your new feature should be implemented.

### Pull Requests

If you have developed a patch, bug fix, or new feature that would improve this app, please submit a pull request. It is best to communicate your ideas with the developers first before investing a great deal of time into a pull request to ensure that it will mesh smoothly with the project.

Remember that this project is licensed under the MIT license, and by submitting a pull request, you agree that your work will be, too.

#### Pull Request Guidelines

- Ensure any install or build dependencies are removed before the end of the layer when doing a build.
- Update the README with details of changes to the interface, including new plist variables, exposed ports, useful file locations and container parameters.
- Ensure that your code conforms to our existing code conventions and test coverage.
- Include the relevant issue number, if applicable.
- You may merge the Pull Request in once you have the sign-off of two other developers, or if you do not have permission to do that, you may request the second reviewer to merge it for you.

## Documentation

See [Backend Documentation](https://github.com/Lambda-School-Labs/Labs25-Bridges_to_Prosperity-TeamB-be) for details on the backend of our project.

See [React Map GL](https://visgl.github.io/react-map-gl/) for details on the mapbox interface library.

![MIT](https://img.shields.io/packagist/l/doctrine/orm.svg)
![React](https://img.shields.io/badge/react-v16.7.0--alpha.2-blue.svg)

[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)
