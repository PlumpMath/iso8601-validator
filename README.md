iso8601-validator
=================
Easily validate your ISO-8601 strings:

```javascript
var iso8601 = require('iso8601-validator')

iso8601('2015-06-10T10:40:38.974Z') // => true
iso8601('asdf') // => false
```

