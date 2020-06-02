<h1 align="center">
     <img src="./github/logo.svg" alt="GoBarber logo" width="400">
</h1>

<h3 align="center">
 GoBarber
</h3>

<p align="center">Gobarber is an application created for scheduling aesthetic services, the application allows viewing schedules in addition to making new schedules and cancellations, bringing together the js stack with nodejs, reactjs and react native.</p>

<p align="center">
  <a href="#rocket-technologies">Technologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-how-to-use">How to use</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-license">License</a>
</p>

<p align="center">
  <a href="https://opensource.org/licenses/MIT" >
    <img alt="License" src="https://img.shields.io/badge/license-MIT-%23F8952D">
  </a>
</p>

<div>
     <img src="./github/page1.png" alt="Login screenshot" width="880">
     <img src="./github/page2.png" alt="Cadastro screenshot" width="880">
</div>

<br />
<br />

## :rocket: Technologies

<br />
This app features all the latest tools and practices in mobile development!
<br />
<br />

- [React](https://reactjs.org)
- [React Native](https://facebook.github.io/react-native/)
- [Node.js](https://nodejs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Postgres SQL](https://www.postgresql.org/)
- [Mongo DB](https://www.mongodb.com/)
- [TypeORM](https://typeorm.io/)
- [JSON Web Tokens](hhttps://jwt.io/)

## 📢 How to use

<br />

**📡 Backend (Node Js)**

<br />

Step 1 - Access our application's node server folder with the command: `cd server`;

Step 2 - Download the npm packages used in the project with the command: `npm` , if you prefer yarn execute `yarn`;

Step 3 - Start the server with the command: `npm run dev`, if you prefer yarn run `yarn dev`;

- Node Server is required for both the frontend and the mobile.
- it is necessary to have a postgres database with the name `gobarber`.

<br />
<br />

**💻 Frontend (React Js)**

<br />

Step 1 - Access our application's frontend folder with the command: `cd web`;

Step 2 - Download the npm packages used in the project with the command: `npm` , if you prefer yarn execute `yarn`;

Step 3 - Start the application with the command: `npm run start`, if you prefer yarn run `yarn start`;

<br />
<br />

**📱 Mobile (React Native)**

<br />
Step 1 - Access our application's mobile folder with the command: `cd app`;

Step 2 - Download the npm packages used in the project with the command: `npm` , if you prefer yarn execute `yarn`;

Step 3 - Change `baseURL` in ./src/services/apiClient.ts, for the ip of your machine, this is important because the localhost would be the ip of the device or emulator and we need the ip of the server.;

Step 4 - Start the application with the command: `npm run start`, if you prefer yarn run `yarn start`;

<br />
<br />

## :memo: License

<br />
This project is licensed under the MIT License - see the details in <a href="https://opensource.org/licenses/MIT">page</a>.

---

Make with :purple_heart:
