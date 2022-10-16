# Introducing Python

Python was created by Guido van Rossum as a successor to ABC, an educational programming language. Python is designed to be simple and fun to use - the name comes from the comedy group Monty Python. Python's not just a good first language though - Python is a truly powerful general purpose language, and it's widely used for just about everything, whether it's data science, devops, machine learning, robotics or web development. We're sure you'll get a lot out of working with Python, and we hope you enjoy it too!

## Video

Here's the [video](<!-- OMITTED -->) for this section.

## Learning objectives

In this section, you'll learn:

- One way of executing Python code
- How to create and concatenate Strings
- What is meant by _return value_
- How to _assign_ and _reassign variables_

## Prerequisites

* Your machine is [set up](https://github.com/makersacademy/basic-programming#phase-zero-development-setup), ready for some programming

## Part One: Executing Python Code in the Python REPL

Let's run some Python code. We can use the Python REPL to do this. REPL stands for Read-Evaluate-Print-Loop. That means you type in some code, press Enter and Python will run it, show you the result, and then loop back so you can type in some more code. It's extremely useful as a sketchbook or notepad for code, where we can quickly experiment or explore ideas.

To start the Python REPL, open your terminal and type `python3`.  You'll notice that the prompt changes (from `%` to `>>>`, if you're on a Mac).

```python
; python3
Python 3.9.13 (main, May 24 2022, 21:28:31) 
[Clang 13.1.6 (clang-1316.0.21.2)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>>
```

From now on, I'll use `>>>` as the prompt in code examples to show that I am using the Python REPL and the text immediately after the prompt will be what I typed. In this module (for the next 2 weeks) we ask that when you see this, you type along - don't copy and paste! Please start the Python REPL now and follow along :)

## Part Two: Hello Python!

Let's write some Python! Start by saying "hello" and Python, like an annoying sibling, will just repeat it back to you.

```python
>>> "hello"
'hello'
```

Let's breakdown what happened there – you created a `string` containing the letters `h`, `e`, `l`, `l` and `o`, then hit enter and saw the same string `return`ed back to you on the next line.

This leads us to think about two new things – `string`s and `return` values.

### Strings

`string`s are one of Python's _data types_. They're used to store any _sequence_ of letters, numbers or special characters. They could be words, like `"hello"`, names like `"Mandip"`, the flight number `"BA123"`, an emoji `":D"` or pretty much anything else you can imagine.

> Find a list of Python's other data types and make a note of them somewhere
### Return Values

A `return` value is what comes back after Python has executed some code. Not much happened in that first example, you created the `string` and Python just returned it.

Feel free to try some other examples.

```python
>>> "Farewell!"
'Farewell!'
>>> "Tis but a scratch."
'Tis but a scratch.'
>>> "A scratch? Your arm's off!"
"A scratch? Your arm's off!"
>>> "I do not know what else to say"
'I do not know what else to say'
```

### String Manipulation

In those examples, we're not really achieving anything useful – a `string` is created and then `return`ed. Let's try to do something with our `string`s.

```python
>>> "hello, " + "world!"
```

<details>
  <summary>Click here to see the expected return value</summary>
  <code>
    'hello, world!'
  </code>
</details>
<br>

Now we're getting somewhere! The `string`s have been joined or, to use the technical term, **concatenated** and a new `string` was returned. This is one example of `string` manipulation (changing a string). The first few programs you build in Python will focus on this.

There's a problem though! At the moment, the return value is sort of _lost_ and we would have to repeat the concatenation if we wanted to see the full message once again.

```python
>>> "hello, " + "world!"
'hello, world!'
```

If there's one thing you'll come to hate as a developer, it's repetition! So, wouldn't it be great if we could grab hold of the return value to use again later?  Well, we can do just that, using variables.

### Variables

Variables are flexible containers for things, such as `string`s. Putting something _in_ one of these containers is called _assignment_. Let's assign the return value of our String concatenation to a variable called `greeting`.

```python
>>> greeting = "hello, " + "world!"
>>> greeting
'hello, world!'
```

Variables can be _reassigned_ to contain different values, such as a different `string`, hence the name `variable`. Here's an example of reassignment.

```python
>>> greeting = "hello, " + "world!"
>>> greeting
'hello, world!'
>>> greeting = "hello again, " + "world!"
>>> greeting
'hello again, world!'
```

### Time to Break Stuff

We've seen that a `string` is created by enclosing some characters in quotes. What happens if you leave them out? Do that now in the Python REPL to find out.

I.e. Try this...

```python
>>> hello
```

When you've spent a few mins thinking and researching, move on and we'll come back to this in the next section, which focuses on error messages.
## Reflect and Review

So far, we've touched on quite a few things, very superficially but, rest assured, we'll dig deeper in later sections as these are some of the basic building blocks of almost every Python program.

### So far, we've encountered

- Executing Python code in the Python REPL
- Strings
- String concatenation
- Variables
- Return values

**Please pause at this point to reflect and review your learning...**

- Can you explain, verbally or in writing, each of the above in a couple of sentences?
- Make a note of anything that you are unsure about
- See if you can gain clarity by playing in the Python REPL


[Log your progress and go to the next challenge](https://makers-event-logger.herokuapp.com/?event=01_say_hello_to_python.md&repository=makersacademy%2Fpython_foundations&redirect=chapter1%2F02_error_messages.md)

<!-- BEGIN GENERATED SECTION DO NOT EDIT -->

---

**How was this resource?**  
[😫](https://airtable.com/shrUJ3t7KLMqVRFKR?prefill_Repository=makersacademy%2Fpython_foundations&prefill_File=chapter1%2F01_say_hello_to_python.md&prefill_Sentiment=😫) [😕](https://airtable.com/shrUJ3t7KLMqVRFKR?prefill_Repository=makersacademy%2Fpython_foundations&prefill_File=chapter1%2F01_say_hello_to_python.md&prefill_Sentiment=😕) [😐](https://airtable.com/shrUJ3t7KLMqVRFKR?prefill_Repository=makersacademy%2Fpython_foundations&prefill_File=chapter1%2F01_say_hello_to_python.md&prefill_Sentiment=😐) [🙂](https://airtable.com/shrUJ3t7KLMqVRFKR?prefill_Repository=makersacademy%2Fpython_foundations&prefill_File=chapter1%2F01_say_hello_to_python.md&prefill_Sentiment=🙂) [😀](https://airtable.com/shrUJ3t7KLMqVRFKR?prefill_Repository=makersacademy%2Fpython_foundations&prefill_File=chapter1%2F01_say_hello_to_python.md&prefill_Sentiment=😀)  
Click an emoji to tell us.

<!-- END GENERATED SECTION DO NOT EDIT -->