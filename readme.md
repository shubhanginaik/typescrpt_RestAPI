
# steps to follow
- npm init -y
- tsc --init : to intialize tsconfig.json file
# Edit `tsconfig.json`
- target: ts2018
 "moduleResolution": "node"
 "rootDir":"./src"
     "outDir": "./dist"
- npm install --save express body-parser
- npm install --save-dev nodemon
- npm install --save-dev @types/node
- npm install --save-dev @types/express
"start":"nodemon dist/app.js"

we download Postman and then foll. pic.
![postman](postman.png)

