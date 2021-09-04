# React Tailwind Starter

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/783903973878136843/883583890965545020/1_1-zdwf7FmfzCQ1IEw-XGbg-removebg-preview.png" alt="Material Bread logo">
</p>


 # Setup 💻

 ```bash
 git clone https://github.com/apoorvcodes/react-tailwind-starter/
 
 cd project-path
 
 yarn start
 
 ```
 
 # Custimization 
 
 ## Tailwind Config
 ```js
 module.exports = {
  purge: [],
  darkMode: false, // or 'media' or 'class'
  theme: {
    extend: {},
  },
  variants: {
    extend: {},
  },
  plugins: [],
}
```
Note : You can add 
```js 
purge: ["/src/**/*.{js,jsx,ts,tsx}', './public/index.html"] 
```
to remove unused stylings for better performance

