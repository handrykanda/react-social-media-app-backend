# **React + Redux + Firebase Backend Project - [Airchat project](https://airchat-5d063.web.app)**

## **Live Demo:**

You can check out the live demo [Here](https://airchat-5d063.web.app).

## **Getting Started**

- Create Firebase project and add your [javascript project](https://github.com/handrykanda/react-social-media-app), your web app.

It's easy, just follow the steps on this [link](https://firebase.google.com/docs/web/setup#node.js-apps) for a step by step walkthrough.

After you complete all the steps you get a local directory that is linked to your Firebase project. This was created using `firebase init`. By now you also have an **firebaseConfig** object created when you initialize your Firebase app. Create this functions/util/firebaseConfig.js and just paste your **firebaseConfig** object in that file. It will look like this:

```
module.exports = {
  apiKey: "##################################",
  authDomain: "######################",
  databaseURL: "#################################",
  projectId: "##########",
  storageBucket: "#######################",
  messagingSenderId: "########",
  appId: "######################",
  measurementId: "############",
};
```

Great! You can now copy and paste other files in this repo. Navigate to the root directory of your Firebase project and run `cd functions`

- `npm install --save firebase express busboy cors` to install all the required dependencies for this project.

## **Testing**

You can test this using [Postman](https://www.postman.com/downloads) <br> OR
clone the repo on this [link](https://github.com/handrykanda/react-social-media-app), please note that it has some setup stuff that takes few minutes.

## **Functionality overview**

You can view a live demo over [here](https://airchat-5d063.web.app), the complete project.
