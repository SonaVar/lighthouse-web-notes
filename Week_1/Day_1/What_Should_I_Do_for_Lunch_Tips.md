### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```
const whatToDoForLunch = function(hungry, availableTime) {
  if (hungry) {
    if (availableTime < 20) {
      console.log('Pick something up to eat at the back of the Lab or in the kitchen!');
    } else if (availableTime >= 20 && availableTime <= 30) {
      console.log('You deserve a break! How about you try a place in Gastown?');
    } else if (availableTime > 30) {
      console.log('This is a bootcamp after all..you should probably reconsider.');
    }
  } else {
    console.log('Get back to work!');
  }
};
```