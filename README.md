# ansi-highlight

highlight javascript in the terminal

# example

``` js
var highlight = require('ansi-highlight')
var js = require('fs').readFileSync(__filename, 'utf8')
console.log(highlight(js))
```

## License

MIT
