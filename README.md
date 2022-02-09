<div align="center">
  <h1>
    <br />
    <a href="https://github.com/edrys-org/edrys"><img src="./brand/logo.png" width="300px" alt="Edrys" /></a>
    <br /><br/>
  </h1>

  <h4>The Open Remote Teaching Platform</h4>

  <p>
    <a href="https://gitter.im/edrys-org" target="_blank"><img src="https://badges.gitter.im/edrys-org.svg" alt="Gitter" /></a>
    <a href="https://github.com/edrys-org/edrys/blob/main/LICENSE" target="_blank"><img src="https://img.shields.io/github/license/edrys-org/edrys.svg" /></a>
  </p>

</div>

---

Edrys is an online live teaching app and a collaborative ecosystem for remote teaching.

## ✨ Features

- **Modular**: Build your class by combining Modules or make your own with an easy real-time API
- **Intuitive Live Classrooms**: Click on a student to talk to them, or create rooms and drag students in & out
- **Collaborative**: Classes and Modules are simple JSON files that are easy to share between educators
- **Download & Run**: No setups, containers, or databases to set up. Edrys servers are fully self-contained
- **Secure & Privacy-Friendly**: Passwordless auth with minimal user PII stored
- **Fast & Modern**: Based on Deno and Vue with a deliberately small codebase
- **Free and Open Source**, forever: No paywalled features or lock-in

## 💡 Use cases

- **Live online teaching**: One to one, one to many, and many to many live classrooms
- **Remote Labs**: Allow students to access and control live equipment remotely
- **Flipped classrooms and blended learning**: Create modules to deliver virtually any content asynchronously
- **Group coursework**: Dynamic breakout rooms and easy jumping between rooms
- **Automated Grading**: Use Stations to securely auto-grade student submissions into your LMS 

With modular architecture anything is possible. A whiteboard, a discussion forum, a poll, or even remote arduino programming, are all easily encapsulated into shareable modules (each a GitHub repo that can be added by pasting its link into the app).

## 💻 Getting Started

To start a local Edrys server:

1. Download [Deno](https://deno.land/)
2. Clone our repo `git clone git@github.com:edrys-org/edrys.git` 
3. Run the server `deno run -A dist/app.js --address localhost:8000 --secret makeUpSomeSecretTextHere`

Next, 
- 🎉 Visit `localhost:8000` and log in. The email verification code will be printed to console
- 📖 Please [visit our documentation](docs) to continue setting up your server and adding Modules
- 💬 For questions and discussions, please visit our [Gitter community](https://gitter.im/edrys-org/community) 
- 🐞 For bug reports and feature requests, visit the [issues tab](https://github.com/edrys-org/edrys/issues)


## 🏦 Support & Contact

Edrys.org provides support and priority development as a service. 
For sponsorships, donations, or support, please contact [edrys.org@pm.me](mailto:edrys.org@pm.me).

Sponsors and known adopters:

<a href="https://tu-freiberg.de/impressum"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/de/Logo_TU_Bergakademie_Freiberg.svg/100px-Logo_TU_Bergakademie_Freiberg.svg.png" width="80px" alt="Edrys" /></a>

