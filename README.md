# React Tailwind Starter

<p align="center">
  <img src="https://cdn.discordapp.com/attachments/783903973878136843/883583890965545020/1_1-zdwf7FmfzCQ1IEw-XGbg-removebg-preview.png" alt="react+tailwind">
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
Note : You can add this config to remove unused stylings for better performance 
```js 
purge: ["/src/**/*.{js,jsx,ts,tsx}', './public/index.html"] 
```
## Carco Config 

```js
module.exports = {
	style: {
	  postcss: {
	    plugins: [
	      require('tailwindcss'),
	      require('autoprefixer'),
	    ],
	  },
	},
} 
```

You can add more plugins read here [Carco Docs]("https://www.npmjs.com/package/@craco/craco)

<p align="center">

  <img src="https://cdn.discordapp.com/attachments/783903973878136843/883587565867925514/download-removebg-preview.png" alt="happy coding">
</p>


