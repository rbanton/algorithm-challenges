# How to Work on This Project

- [General Instructions](#general-instructions)
- [How to add solution code](#how-to-add-solution-code)
- [How to add test code](#how-to-add-test-code)
- [How to add comments and documentation](#how-to-add-comments-and-documentation)
- [Examples of Acceptable Contributions for Full Credit :white_check_mark:](#examples-of-acceptable-contributions-for-full-credit-white_check_mark)
- [Examples of Unacceptable contributions :x:](#examples-of-unacceptable-contributions-x)

### General Instructions

1. Double check that you qualify to sign up for this task:
  - :white_check_mark: no more than 3 students working on this task (if there are, choose a different task).
  - :white_check_mark: you haven't already done this task for another challenge (if you have, choose one of the other two tasks for this project).
1. Add your name to the challenge you'd like to contribute to.
  <details>![add-name](https://cloud.githubusercontent.com/assets/16547949/19946796/bde8f780-a11b-11e6-964a-68421bde40a7.gif)</details>
1. Review the linked challenge on FreeCodeCamp for full instructions, and links to some resources you can use to help you.
  <details>![fcc-challenge](https://cloud.githubusercontent.com/assets/16547949/19946943/56f89e6c-a11c-11e6-8d69-418cc156950a.gif)</details>
1. If it's the first time you're working on this project, clone it to GitHub Desktop.
  <details>![clone](https://cloud.githubusercontent.com/assets/16547949/19947128/1e95d0d4-a11d-11e6-9447-f46c6b6d3ac7.gif)</details>
1. If it's not the first time you're working on this project, just click the <img width="78" alt="screen shot 2016-11-02 at 5 01 22 pm" src="https://cloud.githubusercontent.com/assets/16547949/19947340/00b4ad5a-a11e-11e6-8da3-15832aba478e.png"> button on GitHub Desktop so you have the most recent updates from your classmates as they work on various challenges.
1. Switch to the branch for your challenge. Then, locate the file to work on in the `challenges` folder of the location you saved your project to.
  <details>![branch](https://cloud.githubusercontent.com/assets/16547949/19947321/e3989e0c-a11d-11e6-8f90-7a7324cef1f0.gif)</details>
1. Once you've coded some work (it doesn't have to be complete), back up your work by committing to that branch, and publishing your changes to GitHub. If you need a reminder on how to do this, check out the [instructions for the previous project (with screenshots)](https://github.com/cop1000/js-koans#backup-and-submit-your-project).
1. :mega: :+1: Communicate early and often!  The proper way to communicate is to use the open pull request for the challenge you're working on to leave messages for your classmates, the instructor, or even notes for yourself if you're working on this over multiple days (which you probably will be). Gitter is good to check if someone else is online at the moment or a quick synchronous conversation.
1. If you struggle you have two avenues to ask for help:
  - :one: ask for help in Gitter chat, and
  - :two: @mention someone directly within your pull request to ask the for help. Since your classmates will be working across multiple challenges, they may help you understand something you're trying to do and maybe you can help them :wink:

### How to add solution code

1. Once you've switched to your challenge's branch (see instructions above), then navigate to the `challenges` folder of the project, and open the file that's titled with your challenge's number and name (for example `challenges/01-reverse-a-string.html`) in your favorite text editor.
1. In the first few lines of the HTML file, you'll find some embedded JavaScript and some comments that say `// This section is where you'll code the function. ----------`. Add your code in the `//COMMENT HERE` block. See the example below:
```js
// This section is where you'll code the function. ----------
function reverseString(str) {
  // ENTER YOUR CODE HERE
  return str;
}
// end code -------------------------------------------------
 ```
1. You can test your own code by opening the same file in a web browser (like FireFox, Chrome, or Safari). You can add tests or change the tests around to try different cases, but please don't commit your tests to the branch so that another student can fulfill their test requirements.
1. Commit your code to your branch (without committing the tests).
1. Push your changes up to GitHub so that others can see what you've done and work on the same challenge as you. Remember, you're collaborating, so if someone else has signed up to work on the same task with you, you should reach out to them on Gitter or via the Pull Request.

### How to add test code

1. Once you've switched to your challenge's branch (see instructions above), then navigate to the `challenges` folder of the project, and open the file that's titled with your challenge's number and name (for example `challenges/01-reverse-a-string.html`) in your favorite text editor.
1. In the HTML file, around line 11, you'll find some JavaScript and some comments that say `// This section is where you'll write your tests -----------`. One test is already written for you, you must write at least 3 other tests in this section:
```js
// This section is where you'll write your tests -----------
// Duplicate line 11 and change the specifics for each test
document.write( reverseString("hello") )
// YOUR TEST 1 GOES HERE
// YOUR TEST 2 GOES HERE
// YOUR TEST 3 GOES HERE
// end test -------------------------------------------------
```
1. Commit your code to your branch.
1. Push your changes up to GitHub so that others can see what you've done and work on the same challenge as you. Remember, you're collaborating, so if someone else has signed up to work on the same task with you, you should reach out to them on Gitter or via the Pull Request.

### How to add comments and documentation

1. Once you've switched to your challenge's branch (see instructions above), then navigate to the `challenges` folder of the project, and open the file that's titled with your challenge's number and name (for example `challenges/01-reverse-a-string.html`) in your favorite text editor.
1. The file will contain two sections: one for the solution, and one for tests. Add comments that document how either of these two things are coded (by definition, you cannot comment on a task that hasn't been completed).
1. Remember that you can write comments in two ways in JavaScript. A line comment `//can be written like this` and a multi-line comment:
```js
/* can be
   written like
   *** this *
*/
```
1. Commit your code to your branch.
1. Push your changes up to GitHub so that others can see what you've done and work on the same challenge as you. Remember, you're collaborating, so if someone else has signed up to work on the same task with you, you should reach out to them on Gitter or via the Pull Request.

### Examples of Acceptable Contributions for Full Credit :white_check_mark:
- I contribute:
  - :one: code to the solution of the `Reverse a String` challenge and there are no other contributors working with me
  - :two: tests to the `Truncate a String` challenge and there are two other contributors working with me, and
  - :three: comments and documentation to the `Chunky Monkey` challenge and there is one other contributor working with me.
- I contribute:
  - :one: code to the solution of the `Falsy Bouncer` challenge and there is one other contributor working with me,
  - :two: tests to the `Title Case a Sentence` challenege and there are no other contributors working with me,
  - :three: documentation and comments to the `Mutations` challenge and there is one other contributor working me.

### Examples of Unacceptable contributions :x:
- I contribute to:
  - :one: code to the solution of `Reverse a String`,
  - :two: tests for the same `Reverse a String` challenge, and
  - :three: documentation and comments to the `Falsy Bouncer` challenge.
  - *Solution: you must contribute to 3 different challenges.*
- I contribute to:
  - :one: code to the solution of `Caesars Cipher` challenge and there are 3 other contributors already working on this.
  - *Solution: each opportunity to contribute can have no more than 3 people, find a different challenge with less contributors.*
- I contribute to:
  - :one: code to the solution,
  - :two: tests, and
  - :three: documentation and comments to the `Seek and Destroy` challenge.
  - *Solution: you must contribute to 3 different challenges.*
