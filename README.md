all thing like [style-loader](https://github.com/webpack-contrib/style-loader)

but made something change

if you not understand style-loader

first you should learn about

```diff
"var content = require(" + loaderUtils.stringifyRequest(this, "!!" + remainingRequest) + ");",
+ "var html = document.querySelector('html').innerHTML;",
+ "var htmlStyle = html.indexOf(content.toString())",
```