# First React App With Vite
Just testing it out, documenting any differences between using Vite and using create-react-app.
- it's main.jsx, not index.js like in create-react-app
- styling specific to what's in App.jsx is still in App.css
- index.css has general styling set, with a media query for prefers-color-scheme to match your system's color scheme

## How to setup a React app with Vite
- <code>npm create vite@latest</code>
- Name the app. For a full stack app name it <code>client</code>
- Select <code>react</code> or <code>react-ts</code>
- Select <code>JavaScript + SWC</code> or <code>TypeScript + SWC</code> option
- <code>cd your-project-name-here</code>
- <code>npm i</code>
- <code>npm run dev</code>
