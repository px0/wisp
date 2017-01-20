A little Clojure-like LISP in JavaScript.

<!-- interactive demo -->

1. Read about the [language essentials & documentation](https://github.com/chr15m/wisp/doc/language-essentials.md).

2. Drop [wisp.min.js](https://github.com/chr15m/wisp/raw/gh-pages/dist/wisp.min.js) into your browser:

```html
<script src="wisp.min.js"></script>

<script type="application/wisp">
  (alert "Hello world!")
</script>

<!-- Load from a file: -->
<script type="application/wisp" src="my-script.wisp"></script>
```

3. Or install the binary with npm:

	`npm install wisp`

4. Compile wisp code to native JS just like CoffeeScript:

	`cat my-script.wisp | node_modules/.bin/wisp > my-script.js`

5. Fire up a REPL to explore the language:

	`./node_modules/.bin/wisp`

[More info](https://github.com/chr15m/wisp/blob/master/doc/more-info.wisp).

This is a fork of [wisp by @Gozala](https://github.com/Gozala/wisp).
