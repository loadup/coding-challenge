# LoadUp Engineering Coding Challenge

Thanks for applying! 

When you finish the exercises below, send this file back to engineering@goloadup.com to finish your application.

 * First Name:
 * Last Name:
 * Email:
 * GitHub:
 * Phone:

## QUESTION 1

This code is broken. Why?

```
(() => {
  foo();
  bar();
  var foo = () => console.log("THIS WON'T RUN");
  function bar() {
    console.log("This will run");
  }
})();
```

## QUESTION 2

Write a function (isMatch) that tests brackets and braces match, and are nested correctly.

For example:
 
Given a string "{{[()]}}", the brackets all have a match and are nested in the correct order. Return true.

Given a string "[(}}", the brackets do not all have matches and are not nested correctly. Return false.

```
isMatch(bracketString) {
	// Your code here
}
```




