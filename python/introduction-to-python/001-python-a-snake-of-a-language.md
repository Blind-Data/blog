---
title: Python - A Snake of a Language
domain: blind-data.com 
tags: python, learning, programming-blogs, beginners, codenewbies
subtitle: Python is among the most loved programming languages. It is easy to learn and has a huge community. Join along as we learn the basics of Python!
slug: python-a-snake-of-a-language
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1667680373137/jyfv3ghVG.png
series: Introduction to Python
publishAs: dimboump
---

## What is Python?

Python is a programming language that is easy to learn and use. It is used in many fields, such as data science, web development, and machine learning. It is also used in many applications, such as games, websites, and even operating systems.

It is an strongly-typed, dynamic, high-level, interpreted language. I know that's a mouthful, but let's break up what each of these characteristics mean, in reverse:

### Interpreted

This means that Python does not need to be compiled into machine code before it can be run. Instead, it is interpreted by a Python interpreter. This makes it easier to use and debug but slower to run compared to compiled languages such as C or C++.

### High-level

This essentially means that Python is easy to read and write. This results from Python's syntax often imitating the English language, which makes it easy to understand. Let's take a look at an example (don't worry if you don't understand everything yet, we'll get to that later):

```python
def is_vowel(letter):
    """Check whether a letter is a vowel."""
    if letter in {'a', 'e', 'i', 'o', 'u'}:
        return True
    return False
```

Even if you don't know what this code does, you can probably understand what it is *trying* to do. This is because the code is written in a way that is similar to how we would write it in English. Let's break it down step by step to demontrate it:

- Line 1 is equivalent to "Define (`def`) a function called `is_vowel` that takes a `letter` as input".
- Line 2 is not a Python command, but a comment. It is used to explain what the function does. It is written between `"""` to indicate that it is a comment that the Python interpreter will ignore but that humans will read.
- Lines 3 and 4 are equivalent to "If the letter is in the set of vowels, return `True`" (i.e. yes, it is a vowel).
- Line 5 is equivalent to "Otherwise, return `False`" (i.e. no, it is not a vowel).

Let's see it in action:

```python
is_vowel("a")
```

**Output:**

`True`

Looks like it works! Now let's try it with a consonant:

```python
is_vowel("m")
```

**Output:**

`False`

Great, it works!

### Dynamic

This means that Python does not need to know the type (i.e. whether it is a number, a collection of characters, a list of items, etc.) of a variable before it is used. Other languages require that the type of a variable be declared before its use. While this saves us a couple of key strokes, it also means that Python is less efficient, as it needs to check the type of a variable every time it is used. As your learning in Python progresses, you will find yourself using type hints to specify the type of a variable, which allows Python to be more efficient and to catch errors before they occur.

### Strongly-typed

It means that Python is strict about the types of variables that can be used in an operation. For example, you cannot add a number to a string. This is different from other languages, such as JavaScript, which will automatically convert a number to a string if it is added to a string. The upside of this is that the variables won't change unexpectedly, which can lead to bugs. The downside, however, is that it can be annoying, especially in your early days of learning Python, to have to convert variables to the correct type before using them. Let's see what happens when we try to add a number to a string:

```python
1 + "1"
```

**Output:**

`TypeError: unsupported operand type(s) for +: 'int' and 'str'`

As you can see, Python tells us that it cannot add an integer (`int`) to a string (`str`).

To avoid this, we can convert the string to an integer before summing them up by using the `int()` function:

```python
1 + int("1")
```

**Output:**

`2`

Voilà! We have successfully added a number to a string without Python complaining.

As you can see, Python is very straightforward to use and has many tricks up its... skin. It is based on the idea that readability is more important than efficiency. This makes it a great language to learn for beginners, as efficiency is not a priority. However, as you dive deeper in Python, you will find that you will need to be more efficient and learn how to write efficient code.

But why should you learn Python? Let's take a look at some of the reasons.

## Why Python?

Python is a great language for beginners to start coding with. As we saw previously, it is easy to read and write yet very practical, readable, and versatile. Its popularity also leads to a large number of resources being available for one to learn (hopefully, you have landed on the best one out there!). Finally, many of the concepts found in Python apply in other languages as well (e.g. object-oriented programming &ndash; OOP), making it a great stepping stone for your programming journey.

Python is the go-to language for data science. It is used in many applications, such as data analysis, data visualization, and machine learning. It is also used in many fields, such as finance, healthcare, and education, making a very handy and general-purpose language to know. In this series, we will be using Python to analyze data and build machine learning models, primarily for text data.

In this series, and from now on, Python is not a snake, just as Java is not a coffee, and C# is not a note. Is your new best friend!

If you are interested in learning more about Python, I recommend you sign up for our newsletter so you don't miss out on the next article in this series!

If you have any questions, feel free to leave a comment below or reach out to me on Twitter [@dimboump](https://twitter.com/dimboump).

See you next time!
