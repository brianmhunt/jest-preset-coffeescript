[_Jest_] + [CoffeeScript]
=========================
Easily write your [_Jest_]s in CoffeeScript.

Automatically handles [_transform_]ation, including even tests written in _[literate]_ CoffeeScript.

This will work on any `.`\[[`lit`]\][`coffee`]\[[`.md`]\] file in your `test`[`s`] folder by default.

Install
-------
`npm install jest-preset-coffeescript --save-dev`, then add the following to your `package.json`:
~~~ json
"jest": {
  "transform": {
    "coffee": "jest-preset-coffeescript"
  }
},
~~~

License
-------
[MIT] © [Daniel Bayley]

[MIT]:              LICENSE.md
[Daniel Bayley]:    https://github.com/danielbayley

[_jest_]:           https://facebook.github.io/jest
[_transform_]:      https://facebook.github.io/jest/docs/en/configuration.html#transform-object-string-string

[coffeescript]:     http://coffeescript.org
[literate]:         http://coffeescript.org/#literate

[`lit`]:            test/index.litcoffee
[`coffee`]:         test/index.coffee
[`.md`]:            test/index.coffee.md
