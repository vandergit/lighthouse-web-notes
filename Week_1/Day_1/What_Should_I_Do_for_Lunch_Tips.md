### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) with node, which you can launch using the `node` command in Vagrant or directly in your M1 (like me!).

Work on your code iteratively – that means in small pieces.

Here I show the use of the `hungry` and `availableTime` parameters inside my function, try outputting their values to the Terminal for testing.

``` javascript
const whatToDoForLunch = function(hungry, availableTime) {
  if (!hungry) {
    return (console.log("Keep coding and have fun!"));
  }
  if (availableTime < 20) {
    return (console.log("Pick something up and eat in back in the Lab or in the kitchen, where you can get to know your fellow classmates."));
  }
  if (availableTime <= 30) {
    return (console.log("You deserve a break and could try a place in Gastown."));
  }
  if (availableTime > 30) {
    return (console.log("This is a bootcamp after all and you should probably reconsider."));
  }
};
```