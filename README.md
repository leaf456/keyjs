# keyjs
Very simple js library for key detection.
# How to use
## Step one
Very simple to use, you can use locally or remotely.
locally: Shove keyjs.js somewhere in your project, and add `<script src="<PATH TO KEYJS>"></script>` just below `<head>`, above your other code.

remotely: add `<script src="https://leaf456.github.io/keyjs/keyjs.js"></script>` just below `<head>`, above your other code.
## step two
In your code, reference `keyjs.keysdown` for an array containing current keys down. The array will look similar to this: `['a', 'y']`.
For the last key down, reference `keyjs.lastkey`.
