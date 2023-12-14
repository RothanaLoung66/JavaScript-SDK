npm install firebase
// Import the functions you need from the SDKs you need
import { initializeApp } from "firebase/app";
import { getAnalytics } from "firebase/analytics";
// TODO: Add SDKs for Firebase products that you want to use
// <https://firebase.google.com/docs/web/setup#available-libraries>

// Your web app's Firebase configuration
// For Firebase JS SDK v7.20.0 and later, measurementId is optional
const firebaseConfig = {
  apiKey: "AIzaSyB9oPN2xTMe46mZa6RMn9772w5uqeNv_2o",
  authDomain: "series-studio-ba2fa.firebaseapp.com",
  databaseURL: "<https://series-studio-ba2fa-default-rtdb.asia-southeast1.firebasedatabase.app>",
  projectId: "series-studio-ba2fa",
  storageBucket: "series-studio-ba2fa.appspot.com",
  messagingSenderId: "587535277841",
  appId: "1:587535277841:web:6c3bf78b7296d6e136f6b0",
  measurementId: "G-L0ZTTSYEDM"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);
const analytics = getAnalytics(app);
