# eth-hd-keyring-browserified

Run the below in the console to generate bundle.js

### browserify index.js -o bundle.js -t [ babelify --presets [ es2015 ] ]

Then copy the contents of bundle.js into https://babeljs.io/repl/ selecting only Line Wrap and Minify. Paste the result into bundle.min.js