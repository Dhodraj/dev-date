# dev-date

A Tinder-style front end: a stack of cards you swipe left or right, with a chat screen behind it. No real matching; it is a UI build.

Built in 2021.

A React app on Firebase. Cards come from Firestore, swiping uses `react-tinder-card`, and sign-in is Google through Firebase Auth. The old demo site is down.

## Run it

```bash
cd my-app
npm install
npm start
```

It reads Firebase config from `my-app/src/firebase.js`, which ships with a placeholder API key. Add your own Firebase web config there, and enable Firestore and Google sign-in in your Firebase project.
