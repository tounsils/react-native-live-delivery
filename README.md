
[![GitHub release](https://img.shields.io/github/release/tounsils/react-native-live-delivery?color=blue)](https://github.com/tounsils/react-native-live-delivery/releases)
[![GitHub stars](https://img.shields.io/github/stars/tounsils/react-native-live-delivery?color=yellow)](https://github.com/tounsils/react-native-live-delivery/stars)


# react-native-live-delivery

React native live delivery or track sample app 

# Start
$ npm start
http://localhost:8081/

$ npm run ios
$ npm start android

# Git
…or create a new repository on the command line

echo "# react-native-live-delivery" >> README.md

git init

git add README.md

git commit -m "first commit"

git remote add origin https://github.com/tounsils/react-native-live-delivery.git

git add -A

git commit -m "initial commit"

git push origin master


…or push an existing repository from the command line

git remote add origin https://github.com/tounsils/react-native-live-delivery.git

git push -u origin master

# From react-native-cli to expo-cli

        "scripts": {
        "start": "expo start",
        "eject": "expo eject",
        "android": "expo start --android",
        "ios": "expo start --ios",
        "test": "jest"
        }

    Replace react-native-scripts with expo in the scripts configuration in package.json. See the example above.

    Remove react-native-scripts from devDependencies.

    run $ npm install
    Expo CLI will be installed automatically the first time you run npm start.

    # Issues
    - ISSUE: Cannot determine which native SDK version your project uses because the module `expo` is not installed. Please install it with `yarn add expo` and try again.
    + FIX : npm install expo  OR  npm install -g expo 
