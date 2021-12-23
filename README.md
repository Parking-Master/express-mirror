# Mirror.js
An NPM package that lets you reflect existing webpages onto your own page.

## Install
```cli
$ npm install mirror
```

Install globally
```cli
$ npm install mirror -g
```

Install as project:
```cli
$ npm install mirror --save
```

## Example
```cli
$ npm install mirror --save
```

```javascript
let mirror = require("mirror");
```

```javascript
app.get("/", function(req, res) {
  mirror(res, "https://example.com");
});

app.listen(8080);
```

_Go to <kbd>[http://localhost:8080](http://localhost:8080)</kbd>, and you'll see <kbd>https://example.com</kbd> on your page!_

## License
MIT
