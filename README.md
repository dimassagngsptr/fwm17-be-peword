<div align="center">
  <a href="https://github.com/dimassagngsptr/Peworld">
      <img src="https://github.com/dimassagngsptr/Peworld/blob/development/public/screenshoot/foot-logo.png" width="350"/>
  </a>

  <h1 align="center">Peworld</h1>

  <p align="center">
    Peworld Implementation
    <br />
    <br />
   <a href="https://dimas-peworld.vercel.app/" target="_blank">View Website Demo</a>
    ·
    <a href="https://github.com/dimassagngsptr/fwm17-be-peword.git" target="_blank">View Back-End Repo</a>
  </p>
</div>

- [Table of Contents](#table-of-contents)
- [About The Project](#about-the-project)
  - [Built With](#built-with)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Contributing](#contributing)
- [Contact](#contact)
- [Documentation](#documentation)
- [Acknowledgements](#acknowledgements)
## About The Project

This back-end project for **Peworld** was developed by [muhammadrisano](https://github.com/muhammadrisano) using Express.js. Feel free to explore the source code, which I have forked from the original repository. It includes all the files and documentation needed to develop and run the server side of this application. Thank you for developing this back-end project.

### Built With

- [Express.js](https://expressjs.com/)
- [Node.js](https://nodejs.org/en)
- [MongoDB](https://www.mongodb.com/)

## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

Ensure you have the following installed on your local machine:

- node js
  ```sh
      node version 20
  ```
  [Visit Link to download Node.Js](https://nodejs.org/en)

- npm

  ```sh
     npm install npm@latest -g
  ```

### Installation

1. Clone Repo

   ```sh
     git clone https://github.com/dimassagngsptr/fwm17-be-peword.git
   ```

2. Go to folder

   ```sh
    cd fwm17-be-peword
   ```

   ```sh
     code .
   ```

3. Install NPM packages

   ```sh
     npm install
   ```

4. To start the development server:

   ```sh
     nodemon
   ```
   if doesnt work

   ```sh
      node index.js
   ```

## Usage

To use this project, follow the instructions below for understanding the project structure and how to use the provided API documentation.

## Project Structure

```sh
fwm17-be-peword/
├── node_modules/
├── src/
│   ├── config/
│   │   └── db.js
│   ├── controllers/
│   │   ├── auth/
│   │   │   ├── index.js
│   │   │   └── request_model.js
│   │   ├── experience/
│   │   │   ├── index.js
│   │   │   └── request_model.js
│   │   ├── hire/
│   │   │   ├── index.js
│   │   │   └── request_model.js
│   │   ├── portfolio/
│   │   │   ├── index.js
│   │   │   └── request_model.js
│   │   ├── recruiter/
│   │   │   ├── index.js
│   │   │   └── request_model.js
│   │   ├── skill/
│   │   │   ├── index.js
│   │   │   └── request_model.js
│   │   └── workers/
│   │       ├── index.js
│   │       └── request_model.js
│   ├── helpers/
│   │   ├── auth.js
│   │   └── common.js
│   ├── middlewares/
│   │   ├── auth.js
│   │   └── upload.js
│   ├── models/
│   │   ├── experience.js
│   │   ├── hire.js
│   │   ├── portfolio.js
│   │   ├── recruiter.js
│   │   ├── skill.js
│   │   ├── users.js
│   │   └── workers.js
│   ├── routes/
│   │   ├── auth.js
│   │   ├── experience.js
│   │   ├── hire.js
│   │   ├── index.js
│   │   ├── portfolio.js
│   │   ├── recruiter.js
│   │   ├── skill.js
│   │   ├── upload.js
│   │   └── workers.js
│   ├── utils/
│        └── cloudinary.js
│   
├── .gitignore
├── README.md
├── index.js
├── package-lock.json
├── package.json
├── vercel.json
└── yarn.lock
```

### Documentation

Access the API documentation for the **Peworld** project, also created by [him](https://github.com/muhammadrisano). Use this documentation to test endpoints and understand the structure and functionality of the available APIs in this project.

[![Peworld API Postman Documentation](https://run.pstmn.io/button.svg)](https://documenter.getpostman.com/view/7675329/2s9YysDhDY#d67edcdf-e1ef-468b-9877-2c3e930c82a9)

### Project Related

- [`Front-End Project Repository Link`](https://github.com/dimassagngsptr/Peworld.git)

- [`Front-End Demonstration Link`](https://dimas-peworld.vercel.app/)

- [`Back-End Demonstration Link`](https://fwm17-be-peword.vercel.app/v1/workers)

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Contact

If you have any questions or inquiries regarding this project, feel free to contact me at ryusuf05@gmail.com or [muhammadrisano](https://github.com/muhammadrisano) for back-end issues.

## Acknowledgements

Feel free to check it out:

- [Img Shields](https://shields.io)
- [Choose an Open Source License](https://choosealicense.com/)
- [GitHub Pages](https://pages.github.com/)
