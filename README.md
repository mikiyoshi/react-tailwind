# Setting

```
git clone https://github.com/adrianhajdin/project_hoobank.git react-tailwind
cd react-tailwind
git config remote.origin.url
git remote set-url origin https://github.com/mikiyoshi/react-tailwind.git
```

# Deploy React App at Github pages

[React App at Github pages](https://mikiyoshi.github.io/react-tailwind)

- install gh-pages

```
npm install gh-pages --save-dev
```

- update package.json

```
  "homepage": "https://mikiyoshi.github.io/react-tailwind"

```

and ????

```
  "scripts": {
    "predeploy": "npm run build",
    "deploy": "gh-pages -d build",
```

- update vite.config.js // react-tailwind is your repo name
  - [Deploy React at Github pages with vita](https://dev.to/shashannkbawa/deploying-vite-app-to-github-pages-3ane)

and

```
export default defineConfig({
  base: '/react-tailwind/',
  plugins: [react()],
});
```

then

```
npm run deploy ????
npm run build
git add dist -f
git add .
git commit -m "Deploy"
git push origin main
git subtree push --prefix dist origin gh-pages
```

# Setup

- type command in git repo name one folder above

```
npm create vite@latest
```

react-tailwind // this is a same as git repo name and made a react setup files
react

```
npm install -D tailwindcss
npx tailwindcss init
```

# HooBank - Modern UI/UX website using React.js & Tailwind CSS

![HooBank](https://i.ibb.co/BK1Hn0x/Screenshot-2022-08-08-at-4-05-48-PM.png)

### Showcase your dev skills with practical experience and land the coding career of your dreams

💻 JS Mastery Pro - https://jsmastery.pro?discount=youtube
✅ A special YOUTUBE discount code is automatically applied!

📙 Get the Ultimate Frontend & Backend Development Roadmaps, a Complete JavaScript Cheatsheet, Portfolio Tips, and more - https://www.jsmastery.pro/links

```

```
