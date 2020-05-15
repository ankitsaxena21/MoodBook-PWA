

# Firebase
Install the Firebase CLI globally: `npm install -g firebase-tools`.

Visit your Firebase project (in the browser) and download your security key file (Settings => Service Accounts). Store it in the functions/ folder and adjust your code in the function to grab that file.

Make sure to enter your Firebase project id into the `.firebaserc` file - deploy your project via `firebase deploy` thereafter.