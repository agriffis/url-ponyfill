# URL-ponyfill

UMD & [ponyfill](https://ponyfill.com) fork of [webcomponents/URL](https://github.com/webcomponents/polyfills/tree/master/packages/url)

# Usage

ES2015 (webpack, rollup, etc)
```
import { URL } from 'url-ponyfill'
```

Node.js
```
const { URL } = require('url-ponyfill')
```


## Polyfill

```
import { URL, hasNativeURL } from 'url-ponyfill';

if (!hasNativeURL) {
    self.URL = URL;
}
```

# License

[MIT](./LICENSE)
