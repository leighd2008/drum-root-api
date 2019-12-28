# Drum Root API

An Express REST API service for Creating and Sharing Drum Loops. See [Drum Root](https://github.com/rgavinc/drum-root) for Front End Service.

## Features

- Create Drum Loops
- Record Custom Sounds
- Save and Share Drum Loops With Others

## Tech

### Front End

- [React](https://reactjs.org/) - JavaScript UI Library
- [Next.js](https://nextjs.org/) - Server Side Rendering
- [Styled](https://www.styled-components.com/) Components - Styling
- [Jest](https://jestjs.io/) - JavaScript Testing Framework(Coming Soon)
- [Puppeteer](https://developers.google.com/web/tools/puppeteer) - A Node Library for Controlling Headless Chrome or Chromium. Used for Integration Testing.(Coming Soon)
- [Storybook](https://storybook.js.org/) - Tool for Developing UI Components in Isolation.(Coming Soon)

### Back End

- [Express](https://expressjs.com/) - Web Framework for Node.js
- [PostgreSql](https://www.postgresql.org/) - Relational Database(Coming Soon)
- [Redis](https://redis.io/) - In-Memory Data Structure Store. Used for Authorization.(Coming Soon)

## Team

- Project Lead - [rgavinc](https://github.com/rgavinc)
- Front End Lead - needed
- Back End Lead - [yashShelatkar](https://github.com/yashShelatkar)
- Database Lead - [Aneesh](https://github.com/aneesh4995)
- QA Lead - [zbc](https://github.com/zbc)
- Designer/ Styling Lead - needed

---

## Running Locally

To get started, fork the repository and run the following commands:

    npm install
    npm run start

## Running using Docker (Back End)

To get started clone the drum-root-api and run the following commands

    sudo docker-compose up --build (Gets running on port 3000)

To access the PSQL shell through local (goto a new terminal)

    docker exec -it drum-root-api_postgres_1 bash
    root@------:/# su postgres
    $ psql
