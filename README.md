# congenial-enigma
An 11ty project with Netlify from scratch


2. npm install sass npm-run-all

then

3. 1. "watch:sass": "sass --watch src/sass:public/css"
   2. "build:sass": "sass src/sass:public/css" 
   3. "watch:eleventy": "eleventy --serve"
   4. "build:eleventy": "eleventy"   
   5. "start": "npm-run-all build:sass --parallel watch:*"
   6. "build": "npm-run-all build:*"