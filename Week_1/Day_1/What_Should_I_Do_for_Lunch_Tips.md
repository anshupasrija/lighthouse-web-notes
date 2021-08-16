### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript
 const whatToDoForLunch = function (hungry, availableTime) {
  if (hungry === false) {
    console.log("Get back to work");
    return "Get back to work";
  } else if (hungry === true && availableTime < 20) {
    console.log("Pick something up and eat in lab");
    return "Pick something up and eat in lab";
  } else if (hungry === true && availableTime >= 20 && availableTime <= 30) {
    console.log("Try a nearby place");
    return "Try a nearby place";
  } else {
    return "Please reconsider how much free time you have!";
  }
};```