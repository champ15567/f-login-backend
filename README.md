backend
npm init --y
npm install typescript ts-node ts-node-dev --save-dev
npx tsc --init

{
"compilerOptions": {
"target": "ES6",
"module": "CommonJS",
"outDir": "./dist",
"rootDir": "./src",
"strict": true,
"esModuleInterop": true,
"allowJs": true
},
"include": ["src/**/*.ts"],
"exclude": ["node_modules"]
}

npm i express
npm i @types/express --save-dev
npm i mongoose
npm i @types/mongoose --save-dev
npm i bcrypt
npm i --save-dev @types/bcrypt
npm i jsonwebtoken
npm i --save-dev @types/jsonwebtoken
npm i cors
npm i --save-dev @types/cors

frontend
npm create vite@latest
npm install @mui/material @emotion/react @emotion/styled
npm install @mui/icons-material
npm i axios
npm install react-router-dom

npm install serve --save-dev
serve -s dist
