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
  .then((fileUrl) => {
    console.log('File uploaded successfully!');
    console.log('File URL', fileUrl);
  })
  .catch((error) => {
    console.error('An error occurred while uploading the file:', error);
  });
```
