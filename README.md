<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="assets/resources/appIcon-with-margin.png"  alt="App Icon" width="100" height="100">
  </a>

  <h1 align="center">Nova Wallet - Official repository</h1>

  <p align="center">
    Nova Wallet is a 100% Open Source app that tries to make personal finances easier. Fast, simple, without ads, without the need for an Internet connection and with a groundbreaking design, that's Nova Wallet.
    <br />
    <br />
    <br />
    <a href="https://play.google.com/store/apps/details?id=com.novawallet.app">
      <img src="https://play.google.com/intl/en_us/badges/images/generic/en-play-badge.png"  alt="Google Play Badge" height="68">
    </a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#why-Nova Wallet">Why Nova Wallet?</a></li>
        <li><a href="#tech-stack">Tech Stack</a></li>
      </ul>
    </li>
    <li>
      <a href="#run-the-code-locally-">Run the code locally</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
        <li>
      <a href="#contributing-">Contributing</a>
      <ul>
        <li><a href="#why-to-contribute">Why to contribute?</a></li>
      </ul>
    </li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

## About the project

|                                                                                                                    |                                                                                                                    |                                                                                                                    |                                                                                                                    |
| :----------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------: |
| ![1](https://github.com/enrique-lozano/Monekin/blob/main/app-marketplaces/screenshots/en/Mockups/Diapositiva1.PNG) | ![2](https://github.com/enrique-lozano/Monekin/blob/main/app-marketplaces/screenshots/en/Mockups/Diapositiva2.PNG) | ![3](https://github.com/enrique-lozano/Monekin/blob/main/app-marketplaces/screenshots/en/Mockups/Diapositiva3.PNG) | ![4](https://github.com/enrique-lozano/Monekin/blob/main/app-marketplaces/screenshots/en/Mockups/Diapositiva4.PNG) |
| ![5](https://github.com/enrique-lozano/Monekin/blob/main/app-marketplaces/screenshots/en/Mockups/Diapositiva5.PNG) | ![6](https://github.com/enrique-lozano/Monekin/blob/main/app-marketplaces/screenshots/en/Mockups/Diapositiva6.PNG) |

### Why Nova Wallet?

After a lot of research on the marketplaces I could not find any application that met all my needs. That is why I decided to start making my own app. After months of hard work, the first version was released on Google Play in October 2021. I decided to make it 100% Open Source shortly after, with the aim of increasing its user community, and that external developers could help and collaborate with me on the project. Since the day of its release, the app has been continuously improving and updating.

### Tech Stack

At the beggining the app was developed in Ionic and Angular. In 2023, in order to make our app better, we migrate the app to Flutter, which allow us to have a modern and scalable application for a large number of operating systems and platforms.

To store and persist your data in the app we store a SQLite database directly in your device, thanks to an opensource package called [drift](https://github.com/simolus3/drift)

## Run the code locally 🚀🧑‍💻

The following explains how to run the project code locally. This way you will be able to investigate on your own how it is done, create new features, fix bugs, etc.

### Prerequisites

As with any Flutter project, you need to install the framework in your machine. Visit the [official docs](https://docs.flutter.dev/get-started/install) for more info. You should also have git installed in your machine.

### Installation

Open a terminal on your computer and go to the folder where you want to place the project. Then clone the project and install the dependencies by typing the following commands:

```
git clone https://github.com/uranusnova/expense-tracker.git
```

```
flutter pub get
```

If everything went correctly these commands will finish executing without errors. Now you can run <code>flutter run</code> on your terminal to open the app locally in your device. The app will be refreshed when changes in the code appear. 