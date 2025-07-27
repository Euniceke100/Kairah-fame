import React from "react";

export default function Home() {
  return (
    <div className="p-6 text-center">
      <h1 className="text-3xl font-bold text-purple-800">Welcome to Kairah Fame</h1>
      <p className="mt-2 text-gray-600">Your viral growth journey starts here.</p>
    </div>
  );
}
import React from "react";

export default function Boost() {
  return (
    <div className="p-6">
      <h2 className="text-2xl font-semibold text-purple-700">Boost Tools</h2>
      <p className="mt-2">Coming soon: AI scripts, trending audio, hashtags & more.</p>
    </div>
  );
}

import React from "react";

export default function Templates() {
  return (
    <div className="p-6">
      <h2 className="text-2xl font-semibold text-purple-700">Viral Templates</h2>
      <p className="mt-2">Explore short-form viral video templates here soon.</p>
    </div>
  );
}
import React from "react";

export default function Login() {
  return (
    <div className="p-6 text-center">
      <h2 className="text-2xl font-semibold">Sign In</h2>
      <p className="text-gray-500">Firebase Auth setup will be added here.</p>
    </div>
  );
}
module.exports = {
  content: ["./src/**/*.{js,jsx}"],
  theme: {
    extend: {},
  },
  plugins: [],
};
// Replace with your actual Firebase config
import { initializeApp } from "firebase/app";
import { getAuth } from "firebase/auth";

const firebaseConfig = {
  apiKey: "YOUR_KEY",
  authDomain: "YOUR_DOMAIN",
  projectId: "YOUR_ID",
  appId: "YOUR_APP_ID",
};

const app = initializeApp(firebaseConfig);
export const auth = getAuth(app);
