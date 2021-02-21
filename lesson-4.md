# First language

## Original plan: ~~Python~~

~~We will learn Python as our first programming language.~~

<details>
  <summary>Reasons:</summary>

  Python has been chosen because:

  - it's nearly ubiquitous (a version is preinstalled on macOS, Linux and is even easy to install on Windows)
  - it's a popular and new dev friendly language, with plenty of questions and answers on the internet
  - it generally uses english words instead of symbols, which may help for memorizing it quicker
  - it's probably the simplest for basic file manipulation
  - because it's easy for new devs to get something working quickly it can help get people to the "critical point"
    (basic coding becomes useful and exploratory as you get ideas of things you could use it for -> learning -> repeat with new knowledge)

  However it does have some downsides:

  - Sometimes Python is version 2 and sometimes it's version 3, and they are not generally interoperable
  - Some pretty useful functions have hard to remember, long or unusual names (e.g. `enumerate`)
  - All the typical problems that can occur with tabs and spaces for indentation
  - It's actually pretty old these days
  - I have bad experiences with `pip` - the dependency manager for python (often to get your code working with other people's code)
</details>

## New plan: JavaScript

We will learn JavaScript as our first language.

Initially, Python made the most sense, but upon reflection JavaScript is a better candidate.

* It's the most useful language for the most people
  > "any application that can be written in JavaScript, will eventually be written in JavaScript"
  > - Jeff Atwood
* It is very flexible (you can make the language do things it wasn't designed for)
* It doesn't overcomplicate things
* It integrates with millions of tools and libraries (<- pieces of reusable code written by others)
* The language was written in 5 days, meaning to memorize the whole core of the language takes less time than others
* It provides built-in JSON support, which is useful as it's a very popular data format (you've seen it before, lots)
* Actually setting it up to run code is generally easier (for Macs) than Python
* I find it easier to find good advice from a google search for JavaScript than Python
  * A lot of correct answers for Python are no longer correct due to changes, for example

However, it does have some issues that were originally the reason I felt Python might be better for a first language.

- It uses less "english words" than python, instead choosing symbols
  - over time, this becomes a positive, but it might make it harder to read in the early stages
- JavaScript has had a weird history, and as its design was literally by committee, it suffered until about 2010.
  Since then, new syntax (i.e. ways of writing code) has replaced most of the worst stuff. Still, sometimes some
  skeletons cause issues. For instance, actually reading input and output from a program is messier than in Python,
  as JavaScript was only designed to be run in the browser, where this was not needed.

---

Example code samples:

```python
NumList = []
Number = int(input("How many element in list, Please enter num :- "))
for i in range(1, Number + 1):
    value = int(input("Please enter the Value of %d Element : " %i))
    NumList.append(value)
```

```js
const numList = []
const number = parseInt(readline("How many element in list, Please enter num :- "))
for (let i = 0; i < Number + 1; i++) {
  value = parseInt(readline(`Please enter the Value of ${i} Element : `))
  numList.push(value)
}
```

---

The remainder of this lesson is to work out where JavaScript fits into your computer and your browser.

High-level, what is a:

* Server
* Browser
* Application

This distinction is made a lot more obious when we:

* build a quick website

---

Other common words:

* Library
* Package
* Program
* Command
* Interface

And common abbreviations:

* CLI
* API
* WWW vs Internet
* HTTP
