# babel-preset-marpat

> This is a babel preset for marpat. This preset will allow you to use marpat with babel. Initial work done by for this preset done by [Scott Robison](https://github.com/scottwrobinson). I have simply forked his camo preset and modified it to match the marpat repo and make it easier to find. 

Testing to be added in the future.

## Install

```sh
$ npm install --save-dev babel-preset-marpat
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "presets": ["marpat"]
}
```

### Via CLI

```sh
$ babel script.js --presets marpat 
```

### Via Node API

```javascript
require("babel-core").transform("code", {
  presets: ["marpat"]
});
```
