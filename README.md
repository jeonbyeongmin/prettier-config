# @jeonbyeongmin/prettier-config

### Installation

```bash
npm install --save-dev @jeonbyeongmin/prettier-config prettier
```

```bash
yarn add --dev @jeonbyeongmin/prettier-config prettier
```


### Usage

1. json format
```json
"@jeonbyeongmin/prettier-config"

```

2. js format for override
```js
module.exports = {
  ...require("@jeonbyeongmin/prettier-config"),
  // Input here to override config
  semi: false,
};
```
