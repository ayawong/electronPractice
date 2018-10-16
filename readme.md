1. ```npm install electron```

2. ```npm init -y```

3. `npm install electron --save-dev`
[Electron 文件](https://electronjs.org/docs/tutorial/installation)

4. edit package.json
```
{
  "name": "demo",
  "version": "1.0.0",
  "description": "",
  "main": "main.js",
  "scripts": {
    "start": "electron ."
  },
  "keywords": [],
  "author": "",
  "license": "ISC",
  "dependencies": {
    "electron": "^1.7.10"
  }
}
```
5. strt `npm start`


>Couldn't set selectedTextBackgroundColor from default ()
>https://github.com/electron/electron/issues/4420#issuecomment-241428502 # electronPractice
