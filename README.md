<div align="center">
  <h1>
    <br />
    <a href="https://github.com/edrys-org/edrys"><img src="./brand/logo.png" width="300px" alt="Edrys" /></a>
    <br />
    <br />
  </h1>

  <h4>The Open Remote Teaching Platform </h4>

  <p>
    <a href="https://gitter.im/edrys-org" target="_blank"><img src="https://badges.gitter.im/edrys-org.svg" alt="Gitter" /></a>
    <a href="https://github.com/edrys-org/edrys/blob/main/LICENSE" target="_blank"><img src="https://img.shields.io/github/license/edrys-org/edrys.svg" /></a>
  </p>

</div>

---

Edrys is a live teaching app and a collaborative ecosystem for building remote teaching experiences.

## ✨ Features

- **Live Classrooms**: Click on a student to talk to them, or create rooms and drag students in & out
- **Remote Labs**: Allow students to interact with your real live lab equipment remotely
- **Modular**: Build your class by combining Modules or make your own with an easy real-time API
- **Easy to start**: Download and run to start, no databases or any other dependencies to set up
- **Privacy-friendly**: Passwordless auth with minimal student PII stored
- **Fast & Modern**: Based on Deno and Vue with a deliberately small codebase
- **Free and Open Source**, forever: No paywalled features or lock-in

## 📸 Screenshots

- Classes dashboard: Select what class to enter or create as many as needed
<div align="center">
<img src="docs/index/screen-classes.png" style="width: 90%"/>
</div>

- Teacher class dashboard: Teachers get an overview of all rooms and can move students around to chat
<div align="center">
<img src="docs/index/screen-teacher.png" style="width: 90%"/>
</div>

- Student class view: Students see their current room and are able to interact with others in the room
<div align="center">
<img src="docs/index/screen-student.png" style="width: 90%"/>
</div>

- Class settings: Teachers can manage memberships, modules, and more to customize their class
<div align="center">
<img src="docs/index/screen-settings.png" style="width: 90%"/>
</div>

## 💡 Use cases

- **Live online teaching**: One to one, one to many, and many to many live classrooms
- **Remote Labs**: Allow students to access and control live equipment remotely (eg. remote Arduino fleet)
- **Flipped classrooms and blended learning**: Create modules to deliver virtually any content asynchronously
- **Group coursework**: Dynamic breakout rooms and easy jumping between rooms
- **Automated Grading**: Use Stations to securely auto-grade student submissions into your LMS 

With modular architecture anything is possible. A whiteboard, a discussion forum, polls, or even remote Arduino programming, are all easily encapsulated into shareable modules ([explore Edrys modules on GitHub](https://github.com/topics/edrys-module)).

## 💻 Getting Started

To start a local Edrys server:

1. Download [Deno](https://deno.land/) (minimum v1.20.1)
2. Clone our repo `git clone git@github.com:edrys-org/edrys.git` 
3. Run the server `deno run -A dist/app.js --address localhost:8000 --serve-path dist/static`

Next, 
- 🎉 Visit `localhost:8000` and log in, the email verification code will be logged in the server console
- 📖 Please [visit our documentation](docs) to continue setting up your server and adding Modules
- 💬 For questions and discussions, please visit our [Gitter community](https://gitter.im/edrys-org/community) 
- 🐞 For bug reports and feature requests, visit the [issues tab](https://github.com/edrys-org/edrys/issues)


## 🏦 Support & Contact

Edrys.org provides support and priority development as a service. 
For sponsorships, donations, support, or just to chat please contact [edrys.org@pm.me](mailto:edrys.org@pm.me).

Sponsors and known adopters (contact us for your logo here!):

<a href="https://tu-freiberg.de/impressum"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/de/Logo_TU_Bergakademie_Freiberg.svg/100px-Logo_TU_Bergakademie_Freiberg.svg.png" width="80px" alt="Edrys" /></a>

