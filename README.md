# typescript_tutorial

* typescript install
```
npm i typescript
```

* ts-node install
```
npm i ts-node --save-dev
```

* tsconfig.json make

```
{
    "compilerOptions": {
        "strict": true,
        "module": "commonjs",
        "moduleResolution": "node",
        "lib": ["es2015","es2016","es2017","es2018","es2019","es2020"],
        "target": "ES5",
        "outDir": "./dist",
        "esModuleInterop": true
    },
    "exclude": ["node_modules"],
    "include": ["src/**/*"]
}

```

* Package.json

```
  "scripts": {
    "start": "tsc && node dist/index.js"
  },
  
```

* test file make

```
console.log("Hello TypeScript!!!");

```

```
npm i @types/node --save-dev
```



* 컴파일
```
npx tsc
```

* 실행
```
npm run start
```

