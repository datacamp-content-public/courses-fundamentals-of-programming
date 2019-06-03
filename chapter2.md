---
title: 'Topic 0 - Introductory Exercises'
description: ""
---

## Hello world!

```yaml
type: NormalExercise
key: e3c880f914
xp: 100
```

Before we dive into any complicated programming, it is important to first understand how we can view and represent objects in Python. You may think of Python as a translator that works between you and the computer. 

Instead of dealing with`1`s and `0`s, we can give Python simple commands to execute. Python allows us to view a visual representation of our data with the `print()` function.

`@instructions`
Write your first ever program!

Try and `print` the following text:
```
"Hello world!"
```

Here's an example:
```
>>> print("Bonjour")
>>> "Bonjour"
```
**Note the quotation marks are required in order to print it, more on that later on**

`@hint`
Use the `print()` function with your required text between quotation marks.

`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}

```

`@solution`
```{python}
print("Hello world!")
```

`@sct`
```{python}
Ex().check_function('print').has_equal_output("Failed the first test case!")
success_msg("Passed the first test case!")
```

---

## Python as a Calculator

```yaml
type: VideoExercise
key: 6ce7340466
xp: 50
```

`@projector_key`
25c9b7aea1a61fa9abc7d0c8fa6db8c0

---

## Factorial Made Easy

```yaml
type: NormalExercise
key: a7939c0ff9
xp: 100
```

The factorial of a number $n$ is made by multiplying all the number between 1 and itself.

For example, the factorial of $4$ is:  
$4 * 3 * 2 * 1 = 24$

`@instructions`
Write a program that prints the factorial of $8$.

Here's an example:
```
>>> print(4*3*2*1)
>>> 24
```

`@hint`


`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}

```

`@solution`
```{python}
print(8*7*6*5*4*3*2*1)
```

`@sct`
```{python}
Ex().check_function("print").check_args().has_equal_value().has_equal_output("Failed the first test case!")
success_msg("Passed the first test case!")
```
