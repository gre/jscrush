JSCrush
===

Minimal version of a JSCrusher to be used for js#k golf contest.

```bash
npm install -g jscrush
```

Usage
---

For now, only one CLI format is supported:

```bash
cat source.js | jscrush 1> output.js
```

You can also use it in Node / Browserify:

```javascript
var jscrush = require("jscrush");
var crushed = jscrush(someJavascriptCode);
```

Credits
---

- http://www.iteral.com/jscrush/ by @aivopaas
- jscrush.js extracted from https://github.com/makepanic/grunt-jscrush/blob/master/tasks/lib/jscrush.js
