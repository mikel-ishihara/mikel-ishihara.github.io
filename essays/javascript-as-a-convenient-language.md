---
layout: essay
type: essay
title: The Conveniece of JavaScript
# All dates must be YYYY-MM-DD format!
date: 2020-09-02
labels:
  - Software engineering
  - JavaScript
---

<p align = "center">
  <img src = "../images/68747470733a2f2f64336a32706b6d6a74696e366f752e636c6f756466726f6e742e6e65742f636f64696e672d61742d7468652d7768697465626f6172642d73696c69636f6e2d76616c6c65792e706e67.png">
</p>

## Great things about high-level languages
Being a computer engineering major, I have been educated in lower-level programming languages such as assembly code and C/C++. In comparison to these languages, Javascript is easy to pick up because it automatically allocates and frees memory, which is arguably the most confusing part about C/C++. I remember it took me months to understand pointers and references, especially with data structures such as binary search trees. Another plus is that I don’t have to declare variables as much in Javascript. From a software engineering perspective, I think certain data structures and manipulations are easier to solve in Javascript and I would highly consider using it for coding interviews.

One really useful trick I learned from the ES6 module in https://www.freecodecamp.org/ was the ternary operator. For example, the following function determines if a number is odd.

```JavaScript
function isOdd(number) {
  if (number % 2 == 0) {
    return false;
  else {
    return true;
}
```

Instead of using an if, else statement, I could write this function as:

```JavaScript
function isOdd(number) {
  return (number % 2 == 0 ? false : true);
}
```

## Learning to code efficiently
The athletic software engineering method is great from a learning and professional perspective. The fast pace of the program forces one to learn, or at least be able to implement, different techniques in coding. The Workout of the Day (WOD) helps students learn how to create logical functions quickly and correctly. This special skill is essential for a software engineer’s professional career since many companies have coding/whiteboard interviews as part of their hiring process. I enjoy the WODs because it is more satisfying to write code efficiently than having homework where I spend hours looking at google for help. I can say for certain that I’m learning more because of the fast pace!
 

