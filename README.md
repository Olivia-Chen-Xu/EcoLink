# Introducing, EcoLink

## Demo

https://user-images.githubusercontent.com/85253089/172278094-ea9bdc99-d174-4a82-b5e0-30795c150e92.mp4


## How to Run
NOTE: Currently, the app is incompatible with the latest verison of Node, use nvm to downgrade to version 16.13.0 and run these commands
- clone repo
- cd to `/QueensGDSC/App/`
- Run `npm install`
- Replace all image paths with either their corresponding local paths on your device, or their uri from an online source (however the code will still compile without this step, just that the image will not show up)
- Replace the `API_KEY` in Scan.js with your own Google Cloud (with full account) API key
- Install expo: `npm install --global expo-cli`, and run `expo start`

- Once the app is running, you can sign up by filling out the signup form, or use an existing account (email: olivia@test.com, password: 123456)

(As of now the camera and gallery access are only configured on ios so an ios emulator is needed to display all features of this app, and the ideal emulator is iPhone 13)

## About Our Project

Hi there, this is Joshua Gonzales, Alessia Panzica, Olivia Xu, and Aaliyah Chang's from Queen's University and this is our submission for Google's 2022 Solution's Challenge.

EcoLink is a mobile application that encourages sustainable living by allowing users to scan trash articles, determine it's recycability, search for disposal areas via EcoLin's database and post about ecofriendly events happening in their communities.

Although our application's front and back end were developed in React Native and Firebase, EcoLink was first modelled and tested in Figma. The link to the mostly functional prototype is as follows:
https://www.figma.com/proto/40tFoXuueuNcOStK7mxIZg/Trash-Detection-Algo-App-%5BWorking-Title%5D?node-id=117%3A624&scaling=scale-down&page-id=0%3A1&starting-point-node-id=139%3A589
You can click through available buttons to navigate through the application in Figma, but all the pages can be seen by clicking on the arrows directly below the simulated screen to simply slide through each page part of the model.

As per the Solution Challenge, most of the app has been designed to work with Google technologies and we have outlined them in the following section.

### Technologies and Next Steps

UI/UX: Figma, Photoshop
Front-End: React, Expo
Back-End (WIP): Firebase, Google Vision API, Google Maps API
