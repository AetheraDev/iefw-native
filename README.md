# IEFW Native

*Upload framework for IECloud, and a optimized version of IEFW with native nodejs.*

### Installing IEFW-NATIVE:

```
npm install iefw-native
```

# Using IEFW NATIVE

**Simple example:**

```js
const ie = require('iefw-native');
const iecloud = new ie();

const file = './path/to/file';

iecloud.uploadFile(file)
  .then(() => {
    console.log('File uploaded successfully!');
  })
  .catch((error) => {
    console.error('Unable to send the file:', error);
  });

```
