# Assessment: JavaScript Katas 1

## Overview

A [kata](<https://en.wikipedia.org/wiki/Kata_(programming)>) is an individual exercise where you practice a programming skill through repetition. Today you will practice using JavaScript loops, conditionals, and expressions through a series of katas.

To start, go [here](https://gitlab.com/kenzie-academy/se/fe/getting-started-with-javascript/s_js-katas-1) then [fork](https://docs.gitlab.com/ee/gitlab-basics/fork-project.html) and [clone](http://docs.gitlab.com/ee/gitlab-basics/start-us%20ing-git.html#clone-a-repository) the repo.
Fill in the missing code inside the katas1.js file for each function. Use a `for` or `while` loop inside each function. Use console.log() to display your result in the console. Each correctly completed kata is worth 1 point.

### Example

```js
function oneThroughFive() {
  // Your code goes below
}
```

To test your functions, you will need to call them. Following the above example,
we would write `oneThroughFive()` to call the function oneThroughFive.
So for the example above, the final function and subsequent function call would look
like this:

```js
function oneThroughFive() {
  for (let counter = 1; counter <= 5; counter++) {
    console.log(counter);
  }
}

oneThroughFive();
```

## Katas

1.  Create a function that returns the numbers from 1 to 20. (1, 2, 3,..., 19, 20)
2.  Create a function that returns the even numbers from 1 to 20. (2, 4, 6,...18,20)
3.  Create a function that returns the odd numbers from 1 to 20. (1, 3, 5,...,17,19)
4.  Create a function that returns the multiples of 5 up to 100. (5, 10, 15, ..., 95, 100)
5.  Create a function that returns all numbers up to 100 that are perfect squares. (1, 4, 9, ..., 81, 100)
6.  Create a function that returns the numbers counting backwards from 20 to 1. (20, 19, 18, ..., 2, 1)
7.  Create a function that returns the even numbers counting backwards from 20. (20, 18, 16, ..., 4, 2)
8.  Create a function that returns the odd numbers from 20 to 1, counting backwards. (19, 17, 15, ..., 3, 1)
9.  Create a function that returns the multiples of 5, counting down from 100. (100, 95, 90, ..., 10, 5)
10. Create a function that returns the numbers that are perfect squares, counting down from 100. (100, 81, 64, ..., 4, 1)

***Note:*** Zero (0) will never be included in any of the answers. Read the answer snippets given after each problem to figure out what your solution should look like.

## Submission

Push your code into your GitLab repository and deploy it via GitLab pages. In Canvas, **please submit your Gitlab
Repo and in the comments your Gitlab Pages url (ex: https://username.gitlab.io/js-katas-01/)** and in GitLab
add KA_grading as a member on your project with "Reporter" permission.
