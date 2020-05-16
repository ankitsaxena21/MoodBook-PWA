# MoodBook-PWA ([Live App](https://moodbook-1e901.web.app/))

MoodBook is a progressive web app(PWA) built with vanilla javascript. It have features like push notification, background synchronization, offline support and much more.

## Getting Started

### Prerequisites

This project runs on [Node.js](https://nodejs.org/en/)

After installation, run `node -v` to make sure node installed correctly. Example

```
$ node -v
v8.9.1
```

### Install Dependencies

```
npm install
```

### Firebase

Install the Firebase CLI globally: `npm install -g firebase-tools`.

Visit your Firebase project (in the browser) and download your security key file (Settings => Service Accounts). Store it in the functions/ folder and adjust your code in the function to grab that file.

Make sure to enter your Firebase project id into the `.firebaserc` file - deploy your project via `firebase deploy` thereafter.

### Start the application

```
npm run start
```
