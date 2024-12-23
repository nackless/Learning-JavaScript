---
title: Data types
author: analytical bull
description: In this lesson, I am learning about data types and conditionals.
pubDate: 2024-12-23
tags:
  - javascript
  - web
  - dev
  - self
  - learning
---




8 data types

1. Number
2. BigInt
3. string
4. boolean
5. null
6. undefined
7. object and symbol
8. typeof operator


8 Data types in [Javascript](https://javascript.info/types)[^data_types]

[^data_types]: https://javascript.info/types


# Strings

Are potentially what makes JavaScript special. You get the power to manipulate stings in Javascript and that make it all interesting. This can be a custom message or a prompt. Understanding how to  manipulate strings would potentially be an important step in mastering JS.

This is the [MDN page](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Scripting/Strings)[^MDN_strings] on strings.

[^MDN_strings]: https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Scripting/Strings
## Basic String Methods

Javascript strings are primitive and immutable: All string methods produce a new string without altering the original string.

Learn more about <strong>String methods</strong> on this [W3schools page](https://www.w3schools.com/js/js_string_methods.asp)[^methods]

[^methods]: https://www.w3schools.com/js/js_string_methods.asp


Also, [MDN Web]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) Docs for strings[^MDN_web_docs_strings] provides useful reference resource. 


[^MDN_web_docs_strings]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String

### Conditionals

- Conditionals are what makes us tell computers how to make decisions.

Step 1: Learn about [comparisons](https://javascript.info/comparison)[^comparisons]

[^comparisons]:https://javascript.info/comparison


Comparisons use <, >, ==, >=, <=, !=

Also, use === for strict comparisons.

```
'a' >  'b'; // false - `Compare the first character
of both strings.`

'Glow'> Glee; // true - `Both strings first characters
are the same, compare the second characters, repeat until
the end of either string.`

'Bee' > 'Be'; // true - `if both strings end at the same length, then they are equal. Otherwise, the longer
string is greater.`

```



#### References: