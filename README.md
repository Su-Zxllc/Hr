# Hr
typescript + electron + react + rxdb + antd

# Command
```bash
npm run dev:server	

npm run dev:render	

npm run dev:file	

npm run dll	
```

# Project Directory 
```
Hr
├─ .babelrc
├─ .gitignore
├─ README.md
├─ app  
│  ├─ browser-window
│  │  ├─ index.ts
│  │  └─ windows
│  │     ├─ login-register-window.ts
│  │     └─ main-window.ts
│  ├─ constants
│  │  └─ index.ts
│  ├─ dialog
│  │  └─ index.ts
│  ├─ global.d.ts
│  ├─ main.ts
│  ├─ preload
│  │  └─ index.ts
│  └─ webpack
│     ├─ webpack.config.base.js
│     ├─ webpack.config.main.js
│     └─ webpack.config.preload.js
├─ gulpfile.js  
├─ package.json
├─ postcss.config.js
├─ src  
│  ├─ components
│  │  ├─ Avatar
│  │  │  ├─ index.tsx
│  │  │  └─ style.less
│  │  ├─ ChatList
│  │  │  ├─ index.tsx
│  │  │  └─ style.less
│  │  └─ Header
│  │     ├─ index.tsx
│  │     └─ style.less
│  ├─ constants
│  │  └─ index.ts
│  ├─ index.tsx
│  ├─ mock
│  │  ├─ index.ts
│  │  └─ login.ts
│  ├─ modules
│  │  └─ Http.ts
│  ├─ pages
│  │  ├─ Login.less
│  │  ├─ Login.tsx
│  │  ├─ Main.less
│  │  └─ Main.tsx
│  ├─ public
│  │  └─ index.html
│  ├─ redux // redux-observable + redux-toolkit
│  │  ├─ epics
│  │  │  ├─ counterEpic.ts
│  │  │  └─ index.ts
│  │  ├─ index.ts
│  │  └─ reducers
│  │     ├─ counterReducer.ts
│  │     └─ index.ts
│  ├─ services  
│  │  ├─ index.ts
│  │  └─ login.ts
│  ├─ utils.ts
│  └─ webpack  
│     ├─ webpack.config.base.js
│     ├─ webpack.config.dev.js
│     ├─ webpack.config.dll.js
│     └─ webpack.config.prod.js
└─ tsconfig.json

```
