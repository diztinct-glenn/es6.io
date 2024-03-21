Arrow Functions are much more concise than regular functions.
They have implicit returns, which allows us to write these nifty one-liners.
They don't rebind the value of this when you use an arrow function inside of another function. Helpful when doing things like click handlers and such.


Arrow functions are always anonymous functions.

Named function Ex. =
function sayMyName(name) {
  alert(`Hello ${name}`);
}

Arrow functions don't have names, but you can pass them into variables. Ex:
const sayMyName = (name) => { alert(`Hello ${name}`) };

Call it with this:
sayMyName('Glenn);
