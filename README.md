simple-corsproxy
==========
> Proxy to access resources that lack the Access-Control-Allow-Origin * header

Install
-------
```$ npm install simple-corsproxy -g```

Usage
-----

```
$ simple-corsproxy
=> Listening on port: 8080 # or environment variable PORT
```

Add the url to the proxy path, like:
```http://localhost:8080/https://google.com```

License
-------
[MIT](https://raw.github.com/bmpvieira/simple-corsproxy/master/LICENSE)
