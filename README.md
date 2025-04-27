#    Reels Pro App
## Public

Welcome to the Reels Pro App repository! This React Native application for the Reels Pro project. Below, you'll find instructions on how to set up the development environment and configure necessary variables 

### Features

Reelzzz App is a powerful, High-performance Social Media app built using React Native. It features:

* 📸 Photo and Video Record Upload
* 🗿 Login with Google / Facebook React Native Node JS Mongoose
* 📱 Highly optimised Typescript Reel Scroll
* 🎞️ Streaming Videos / Uploading Videos and Photos (Chunk upload)
* 🗿 Using High Level Optimisation for react native ( Memoizing , Callbacks)
* 🎨 Hardcore Caching and Memory management
* 🔍 Fully Typescript
* 🎞️ GIPHY - gif Implementation
* ⚡ Mark Pin Comments, Liked By Author, 
* ❤️ Likes - comments, replies, reels | Follow | Unfollow with Flash Tricks


## Installation

Before you begin, make sure you have Node.js and npm installed on your system.You have setup configuration  Setup (PREFER CHAPTER 1) 

1. Clone this repository to your local machine:

```sh
   git clone https://github.com/SahilSuman1011/Reels-Pro
```

2. Navigate to the project directory:

```sh
   cd reels_public
 ```

3. Change the `GOOGLE CLIENT ID` | `FACEBOOK APP CREDENTIALS` | `GIPHY_API_KEY` | :

You can checkout the first video of this for configuration process of this 
setup the server also you are required to watch first video for all external config 
in this repo you just have to replace all credentials.


## Running the App

Once you have configured the all files, you can start the server by running:

```sh
npm install --force
```

for iOS
```sh
cd ios && pod install 
```

```sh
npm run android
npm run ios
```

Replace BASE_URL to your cloud deploy reels pro server or local IP address

This will install the necessary dependencies and start the server on the specified port.


## Server
This serves as the backend for the Reels Pro project. Below, you'll find instructions on how to set up the development environment and configure necessary variables using the `.env` file.


## Installation

Before you begin, make sure you have Node.js and npm installed on your system. You can download and install them from [Node.js official website](https://nodejs.org/).

1. Clone this repository to your local machine:

```sh
   git clone https://github.com/SahilSuman1011/Reels-Pro
```

2. Navigate to the project directory:

```sh
   cd reels_server
 ```

3. Rename the `env_template` according to your need local or prod file to `.env`:

```sh
   mv env_template .env
  ```

## Configuration

Open the `.env` file in your favorite text editor and fill in the required details. If you're unsure about what to fill, you can refer to the following YouTube playlist for guidance:


## Running the Server

Once you have configured the `.env` file, you can start the server by running:

```sh
npm install
npm start
```

This will install the necessary dependencies and start the server on the specified port.

## Contributing

If you'd like to contribute to this project, please fork the repository and create a pull request with your changes. We welcome any contributions, whether it's fixing bugs, adding features, or improving documentation.

## License

This project is licensed under the [MIT License](LICENSE), which means you are free to use, modify, and distribute the code as long as you include the original license in your distribution.

---

Happy coding! If you have any questions or need further assistance, feel free to reach out to us.
