# then-request

## Installation

    npm install then-request-proxy

## Usage

`request(method, url, options, callback?)`

e.g.

```js
var request = require('then-request-proxy');

request('GET', 'http://example.com').done(function (res) {
  console.log(res.getBody());
});
```

## License

  MIT
