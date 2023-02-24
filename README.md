# vue3-ts-demo

# USING POSTMAN TO IMITATE/MOCK A VIRTUAL SERVER

### Compiles and minifies for production

```
npm run build
```

### Lints and fixes files

```
npm run lint
```

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).

### ABOUT VSCODE FORMAT

> shift + cmd + p
> select Format Document --> to choose which formatter to be your default formatter

### ABOUT NPM DEPENDENCIES
- pinia-plugin-persistedstate
Configurable persistence and rehydration of Pinia stores.


# Q&A

#### What if sometimes find the css or layout wierd?

> maybe it's the cache, hard refresh it by pressing ctrl + F5 or using Incogito mode of Chrome

#### How to update Typescript version?

> sudo npm install -g typescript@latest

### In real produce environment we need to run lint

### and write jest to retrieve the coverage

### In Api.ts file cannot export more than 1 default function

### Failed to resolve component: Record

This error message means we lose to import the relative components when we use
