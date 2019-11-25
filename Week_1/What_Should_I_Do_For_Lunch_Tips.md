### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript
const whatToDoForLunch = function(hungry, availableTime) {
  if (!hungry) {
    console.log("Get back to work. You're not hungry!");
  } else if (availableTime < 20) {
    console.log("Pick something up and get back to work.");
  } else if (availableTime <= 30) {
    console.log("Find a place near by.");
  } else {
    console.log("You've got too much time! You're at bootcamp. Take a shorter lunch.");
  }
};
```
