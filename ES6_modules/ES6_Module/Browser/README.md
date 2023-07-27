SyntaxError: Cannot use import statement outside a module (at main.js:1:1)

We must must must in our html script use type="module"
if not, we will had rendering SyntaxError

We dont need after that change our file roots for mjs
example: main.mjs <--- lib.mjs

But if we will not type in our html script type or modude we will had the problem always.
