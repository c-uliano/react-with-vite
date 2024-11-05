# First React App With Vite
Just testing it out, documenting any differences between using Vite and using create-react-app.
- it's `main.jsx`, not `index.js` like in `create-react-app`
- `index.css` has general styling set, with a media query for prefers-color-scheme to match your system's color scheme

## How to setup a React app with Vite
- <code>npm create vite@latest</code>
- Name the app. For a full stack app name it <code>client</code>
- Select <code>react</code> or <code>react-ts</code>
- Select <code>JavaScript + SWC</code> or <code>TypeScript + SWC</code> option
- <code>cd your-project-name-here</code>
- <code>npm i</code>
- <code>npm run dev</code>

## Quicker way to set it up
- You can specify everything in one line:
  - `npm create vite@latest my-react-app -- --template react-ts`
  - this creates a React with TypeScript app called my-react-app
- List of available presets can be found [here](https://github.com/vitejs/vite/tree/main/packages/create-vite)

## Additional packages to install
- `npm i sass`
