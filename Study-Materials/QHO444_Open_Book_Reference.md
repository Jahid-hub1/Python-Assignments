> **GitHub edition:** Use the contents links or browser Ctrl+F to search. The original HTML search shortcuts, colour themes and interactive controls are not available here. Solutions are expanded; typed input is marked with ↵.

Problem Solving Through Programming

# QHO444 Open-Book Reference

Every Python pattern from the module, findable in seconds: task index, cheat sheets, error lookup, quiz traps and corrections.

Built for the AE1 open-book assessment. Press <span class="kbd">/</span> anywhere to search.

Python 3.9 compatible · every snippet executed · no AE2 solutions.

## Contents

1.  [How to use this reference](#c0-how-to-use-this-reference)
    - [Finding things in seconds](#c0-finding-things-in-seconds)
    - [How the code is presented](#c0-how-the-code-is-presented)
    - [Exam-day routine for AE1](#c0-exam-day-routine-for-ae1)
2.  [Part 1: Syntax at a glance](#c1-syntax-at-a-glance)
    - [Values and types](#c1-values-and-types)
    - [Operators](#c1-operators)
    - [Output and input](#c1-output-and-input)
    - [Decisions](#c1-decisions)
    - [Loops](#c1-loops)
    - [Functions](#c1-functions)
    - [Collections](#c1-collections)
    - [Files](#c1-files)
    - [Classes](#c1-classes)
    - [Program skeleton](#c1-program-skeleton)
3.  [Part 2: Task index 1: I/O, numbers, strings, decisions, loops](#c2-task-index-1-io-numbers-strings-decisions-loops)
    - [Input and output](#c2-input-and-output)
    - [Numbers and maths](#c2-numbers-and-maths)
    - [Strings](#c2-strings)
    - [Decisions](#c2-decisions)
    - [Loops](#c2-loops)
4.  [Part 3: Task index 2: functions, modules, lists, tuples, sets, dictionaries](#c3-task-index-2-functions-modules-lists-tuples-sets-dictionaries)
    - [Functions](#c3-functions)
    - [Modules and program structure](#c3-modules-and-program-structure)
    - [Lists](#c3-lists)
    - [Tuples](#c3-tuples)
    - [Sets](#c3-sets)
    - [Dictionaries](#c3-dictionaries)
5.  [Part 4: Task index 3: files, JSON, charts, classes](#c4-task-index-3-files-json-charts-classes)
    - [Paths and folders](#c4-paths-and-folders)
    - [Text files](#c4-text-files)
    - [CSV files](#c4-csv-files)
    - [JSON files](#c4-json-files)
    - [Charts (matplotlib)](#c4-charts-matplotlib)
    - [Classes and objects](#c4-classes-and-objects)
6.  [Part 5: Error lookup](#c5-error-lookup)
    - [Errors before the program even starts](#c5-errors-before-the-program-even-starts)
    - [Name and type problems](#c5-name-and-type-problems)
    - [Value problems](#c5-value-problems)
    - [Index and key problems](#c5-index-and-key-problems)
    - [Attribute problems](#c5-attribute-problems)
    - [File problems](#c5-file-problems)
    - [Maths](#c5-maths)
    - [Objects and classes](#c5-objects-and-classes)
    - [Problems with no error message](#c5-problems-with-no-error-message)
    - [Debugging routine](#c5-debugging-routine)
7.  [Part 6: Quiz traps: predict the output](#c6-quiz-traps-predict-the-output)
    - [Numbers](#c6-numbers)
    - [Strings](#c6-strings)
    - [Booleans and conditions](#c6-booleans-and-conditions)
    - [Loops and range](#c6-loops-and-range)
    - [Lists, tuples, sets, dicts](#c6-lists-tuples-sets-dicts)
    - [Functions](#c6-functions)
    - [Classes](#c6-classes)
8.  [Part 7: Week-by-week cheat sheets](#c7-week-by-week-cheat-sheets)
    - [Week 1: Python, Git, output and input](#c7-week-1-python-git-output-and-input)
    - [Week 2: Decisions](#c7-week-2-decisions)
    - [Week 3: Loops](#c7-week-3-loops)
    - [Week 4: Functions and modules](#c7-week-4-functions-and-modules)
    - [Week 5: Ordered data structures](#c7-week-5-ordered-data-structures)
    - [Week 6: Files](#c7-week-6-files)
    - [Week 7: Sets, dictionaries, JSON](#c7-week-7-sets-dictionaries-json)
    - [Week 8: Third-party libraries (matplotlib)](#c7-week-8-third-party-libraries-matplotlib)
    - [Week 9: Object-oriented programming](#c7-week-9-object-oriented-programming)
    - [Week 10: Inheritance and abstraction](#c7-week-10-inheritance-and-abstraction)
    - [Week 11: Case studies](#c7-week-11-case-studies)
    - [Week 12: Assessment support](#c7-week-12-assessment-support)
9.  [Part 8: Lookup tables](#c8-lookup-tables)
    - [Built-in functions you are likely to need](#c8-built-in-functions-you-are-likely-to-need)
    - [String methods](#c8-string-methods)
    - [List methods](#c8-list-methods)
    - [Dictionary methods](#c8-dictionary-methods)
    - [Set methods](#c8-set-methods)
    - [f-string format specification](#c8-f-string-format-specification)
    - [Printable ASCII codes (32–126)](#c8-printable-ascii-codes-32126)
    - [Python keywords](#c8-python-keywords)
    - [Comparison of collection types](#c8-comparison-of-collection-types)
10. [Part 9: Corrections to the course materials](#c9-corrections-to-the-course-materials)
    - [Week 1–3](#c9-week-13)
    - [Week 4–5](#c9-week-45)
    - [Week 6](#c9-week-6)
    - [Week 7–8](#c9-week-78)
    - [Week 9–10](#c9-week-910)
    - [Week 11 case studies](#c9-week-11-case-studies)
11. [Part 10: Git, PyCharm and PEP-8 quick reference](#c10-git-pycharm-and-pep-8-quick-reference)
    - [Git commands](#c10-git-commands)
    - [PyCharm](#c10-pycharm)
    - [PEP-8 essentials](#c10-pep-8-essentials)
    - [Professional issues (LSEP) to mention in reports](#c10-professional-issues-lsep-to-mention-in-reports)

<a name="c0-how-to-use-this-reference"></a>

## How to use this reference

This book is for the room, not the sofa. It assumes you already met each idea once (the learning book does that) and need it back **fast**, under time pressure, with no one to ask.

<a name="c0-finding-things-in-seconds"></a>

### Finding things in seconds

- **Press `/`** (or `Ctrl+K`) anywhere to search every heading, explanation and code sample. Type the *thing you want to do*, not the name of the function: `count words`, `skip header`, `sort descending`, `average`, `KeyError`.
- The **Task index** chapters are organised as *"How do I…?"* questions. Each answer is a short, runnable snippet plus the output it really produces.
- If your code crashes, go straight to **Error lookup** and search the last line of the red error message.
- **Quiz traps** lists the questions that are designed to catch you out: predict-the-output questions about `range`, slicing, integer division, `and`/`or` and so on.

<a name="c0-how-the-code-is-presented"></a>

### How the code is presented

Every snippet in this book was executed with Python before it was printed, so the output underneath is what actually happens, not what should happen. When a program reads input, the text a user typed is shown in **amber** followed by `↵`, exactly where it would appear in the PyCharm console.

```python
name = input("What is your name? ")
print(f"Hello {name}!")
```

**Output**

```text
What is your name? Ada ↵
Hello Ada!
```

All code uses only features available in **Python 3.9**, which is the version the module's setup guide specifies.

<a name="c0-exam-day-routine-for-ae1"></a>

### Exam-day routine for AE1

**Before you start**

1.  Open this file, PyCharm, and a scratch file named `scratch.py`. Test every answer there before you submit it, because running code beats guessing.
2.  Read each question twice. Underline the **exact output wording** the question asks for: spaces, capitals, full stops.
3.  For "what does this print?" questions, **paste the code into `scratch.py` and run it**. That is allowed and it is faster than tracing by hand.
4.  If an answer needs a function, check: correct name? correct parameters? does it `return` or `print`, whichever the question asked for?

**What this book deliberately does not contain**

Nothing in here is written to solve the AE2 coursework. The AE2 brief forbids using AI to produce any part of the solution, so the examples use other data (clothing, scores, robots, Titanic, Olympics), and nothing is shaped like the AE2 tasks.

<a name="c1-syntax-at-a-glance"></a>

## Part 1: Syntax at a glance

One screen per topic. If you only remember where this chapter is, you can rebuild almost anything.

<a name="c1-values-and-types"></a>

### Values and types

| Type    | Example                 | Convert with    | Notes                                                                          |
|---------|-------------------------|-----------------|--------------------------------------------------------------------------------|
| `str`   | `"hello"`, `'hi'`, `""` | `str(x)`        | Text. Immutable. `input()` **always** returns `str`.                           |
| `int`   | `42`, `-7`, `0`         | `int("42")`     | Whole numbers. `int("4.5")` fails; `int(4.9)` gives `4` (truncates).           |
| `float` | `3.14`, `-0.5`, `2.0`   | `float("3.14")` | Decimals. `float("7")` gives `7.0`.                                            |
| `bool`  | `True`, `False`         | `bool(x)`       | Capital T and F. `0`, `""`, `[]`, `{}`, `None` count as false.                 |
| `None`  | `None`                  |                 | "No value". What a function returns if it has no `return`.                     |
| `list`  | `[1, "a", 2.5]`         | `list(x)`       | Ordered, changeable, duplicates allowed.                                       |
| `tuple` | `(1, "a")`, `(5,)`      | `tuple(x)`      | Ordered, **unchangeable**. One item needs a trailing comma.                    |
| `set`   | `{1, 2, 3}`, `set()`    | `set(x)`        | Unordered, **no duplicates**, no indexing. `{}` is an empty *dict*, not a set. |
| `dict`  | `{"a": 1}`, `{}`        | `dict(x)`       | Key → value. Keys unique. Ordered by insertion (3.7+).                         |

```python
print(type(7), type(7.0), type("7"), type(True), type(None))
print(int("42") + 1, float("2.5") * 2, str(10) + "0")
```

**Output**

```text
<class 'int'> <class 'float'> <class 'str'> <class 'bool'> <class 'NoneType'>
43 5.0 100
```

<a name="c1-operators"></a>

### Operators

| Kind               | Operators              | Example → result                        |
|--------------------|------------------------|-----------------------------------------|
| Arithmetic         | `+ - * /`              | `7 / 2` → `3.5` (always a float)        |
| Floor division     | `//`                   | `7 // 2` → `3`                          |
| Remainder (modulo) | `%`                    | `7 % 2` → `1` (even test: `n % 2 == 0`) |
| Power              | `**`                   | `2 ** 3` → `8`                          |
| Comparison         | `== != < > <= >=`      | `3 == 3.0` → `True`                     |
| Logical            | `and or not`           | `not (a and b)`                         |
| Membership         | `in`, `not in`         | `"a" in "cat"` → `True`                 |
| Assignment         | `= += -= *= /=`        | `count += 1` means `count = count + 1`  |
| String             | `+` joins, `*` repeats | `"ab" * 3` → `"ababab"`                 |

**Precedence** (highest first): `**` → unary `-` → `* / // %` → `+ -` → comparisons → `not` → `and` → `or`. If in doubt, add brackets.

<a name="c1-output-and-input"></a>

### Output and input

```python
print("Hello", "world")              # items separated by a space
print("a", "b", sep="-")             # custom separator
print("no newline...", end="")       # stay on the same line
print("done")
name = input("Name? ")               # always a string
age = int(input("Age? "))            # convert straight away
height = float(input("Height (m)? "))
print(f"{name} is {age} and {height:.2f} m tall")
```

**Output**

```text
Hello world
a-b
no newline...done
Name? Ada ↵
Age? 37 ↵
Height (m)? 1.8 ↵
Ada is 37 and 1.80 m tall
```

**Escape characters:** `\n` new line, `\t` tab, `\\` backslash, `\"` double quote, `\'` single quote.

<a name="c1-decisions"></a>

### Decisions

```python
score = 67
if score >= 70:
    grade = "Distinction"
elif score >= 60:
    grade = "Merit"
elif score >= 40:
    grade = "Pass"
else:
    grade = "Fail"
print(grade)
```

**Output**

```text
Merit
```

The colon `:` opens a block and everything indented underneath belongs to it. Python checks `if`/`elif` conditions **top to bottom and stops at the first true one**.

<a name="c1-loops"></a>

### Loops

```python
# while: repeat while a condition is true (unknown number of repeats)
count = 0
while count < 3:
    count += 1
print("count is", count)

# for + range: a known number of repeats
for i in range(1, 6, 2):        # start, stop (excluded), step
    print(i, end=" ")
print()

# for over any collection
for letter in "abc":
    print(letter.upper(), end="")
print()
```

**Output**

```text
count is 3
1 3 5 
ABC
```

`break` leaves the loop immediately. `continue` skips to the next pass.

<a name="c1-functions"></a>

### Functions

```python
def area(width, height=1):          # height has a default value
    """Return the area of a rectangle."""
    return width * height

print(area(3, 4))       # positional arguments
print(area(5))          # uses the default height
print(area(height=2, width=6))  # keyword arguments
```

**Output**

```text
12
5
12
```

<a name="c1-collections"></a>

### Collections

```python
nums = [4, 1, 3]
nums.append(2)                      # [4, 1, 3, 2]
first, last = nums[0], nums[-1]
point = (3, 5)                      # tuple
x, y = point                        # unpacking
seen = {"red", "blue", "red"}       # set: duplicates vanish
ages = {"Ann": 34, "Tom": 29}       # dict
ages["Raj"] = 41                    # add or update
print(nums, first, last, x, y, len(seen), ages["Ann"])
```

**Output**

```text
[4, 1, 3, 2] 4 2 3 5 2 34
```

<a name="c1-files"></a>

### Files

```python
import csv
with open("clothing.csv") as file:          # closes automatically
    reader = csv.reader(file)
    headings = next(reader)                 # first row only
    for row in reader:                      # each row is a list of strings
        print(row[1])
```

**Output**

```text
Shirt
Coat
Trousers
```

<a name="c1-classes"></a>

### Classes

```python
class Robot:
    MAX_ENERGY = 100                        # class attribute (shared)

    def __init__(self, name="Robot"):
        self.name = name                    # instance attribute
        self.energy = 0

    def charge(self, amount):
        self.energy = min(self.energy + amount, Robot.MAX_ENERGY)

    def __str__(self):
        return f"{self.name} ({self.energy}%)"


bot = Robot("Bolt")
bot.charge(150)
print(bot)
```

**Output**

```text
Bolt (100%)
```

<a name="c1-program-skeleton"></a>

### Program skeleton

```python
import csv              # imports at the top


def main():
    """Program starts here."""
    print("Program started")


if __name__ == "__main__":     # only runs when this file is run directly
    main()
```

<a name="c2-task-index-1-io-numbers-strings-decisions-loops"></a>

## Part 2: Task index 1: I/O, numbers, strings, decisions, loops

Every answer here is a pattern you can copy and adapt. Headings are phrased the way you would think of the problem.

<a name="c2-input-and-output"></a>

### Input and output

<a name="c2-read-a-whole-number-or-a-decimal-from-the-user"></a>

#### Read a whole number (or a decimal) from the user

```python
print("How many apples?")
apples = int(input())
print("Price per apple?")
price = float(input())
print(f"Total: {apples * price}")
```

**Output**

```text
How many apples?
12 ↵
Price per apple?
2.5 ↵
Total: 30.0
```

**Common mistake**

`input()` returns text. `"12" + "3"` is `"123"`, not `15`. Convert with `int()` or `float()` **before** you do maths.

<a name="c2-keep-asking-until-the-input-is-valid"></a>

#### Keep asking until the input is valid

```python
while True:
    text = input("Enter a positive whole number: ")
    if text.isdigit() and int(text) > 0:
        number = int(text)
        break
    print("Invalid, try again.")
print("You entered", number)
```

**Output**

```text
Enter a positive whole number: ten ↵
Invalid, try again.
Enter a positive whole number: -3 ↵
Invalid, try again.
Enter a positive whole number: 7 ↵
You entered 7
```

`str.isdigit()` is `True` only for strings made entirely of the digits 0–9, so `"-3"` and `"2.5"` are rejected. For decimals or negatives, use `try`/`except` (see *Handle a conversion that might fail* below).

<a name="c2-handle-a-conversion-that-might-fail"></a>

#### Handle a conversion that might fail

```python
def read_float(prompt):
    while True:
        try:
            return float(input(prompt))
        except ValueError:
            print("That is not a number.")


value = read_float("Weight in kg: ")
print(value * 2)
```

**Output**

```text
Weight in kg: abc ↵
That is not a number.
Weight in kg: 4.5 ↵
9.0
```

<a name="c2-print-on-the-same-line-or-with-a-custom-separator"></a>

#### Print on the same line, or with a custom separator

```python
print("Loading", end="")
for i in range(3):
    print(".", end="")
print(" done")
print("2026", "11", "17", sep="-")
```

**Output**

```text
Loading... done
2026-11-17
```

<a name="c2-format-numbers-decimal-places-padding-alignment"></a>

#### Format numbers: decimal places, padding, alignment

```python
bmi = 21.604938
print(f"{bmi:.2f}")           # 2 decimal places
print(f"{bmi:.1f}")           # 1 decimal place
print(f"{1234567:,}")         # thousands separator
print(f"{0.256:.1%}")         # percentage
print(f"[{'left':<10}]")      # pad to 10, left-aligned
print(f"[{'right':>10}]")     # right-aligned
print(f"[{'mid':^10}]")       # centred
print(f"[{42:5}]")            # numbers right-align by default
print(f"[{7:03}]")            # zero-pad
print(round(bmi, 2))          # round() gives a number, not text
```

**Output**

```text
21.60
21.6
1,234,567
25.6%
[left      ]
[     right]
[   mid    ]
[   42]
[007]
21.6
```

<a name="c2-print-a-table-with-aligned-columns"></a>

#### Print a table with aligned columns

```python
rows = [("Gold", 13372), ("Silver", 13116), ("Bronze", 13295)]
for medal, count in rows:
    print(f"| {medal:<8} | {count:>6} |")
```

**Output**

```text
| Gold     |  13372 |
| Silver   |  13116 |
| Bronze   |  13295 |
```

<a name="c2-print-a-line-of-dashes-the-same-length-as-a-title"></a>

#### Print a line of dashes the same length as a title

```python
title = "Weekly Report Generator"
print("-" * len(title))
print(title)
print("-" * len(title))
```

**Output**

```text
-----------------------
Weekly Report Generator
-----------------------
```

<a name="c2-print-a-multi-line-block-ascii-art-menus"></a>

#### Print a multi-line block (ASCII art, menus)

```python
print("""
##########
#  o  o  #
#  ----  #
##########""")
```

**Output**

```text
##########
#  o  o  #
#  ----  #
##########
```

A triple-quoted string keeps its line breaks. Backslashes inside still act as escape characters, so write `\\` for a literal backslash.

<a name="c2-numbers-and-maths"></a>

### Numbers and maths

<a name="c2-even-or-odd-divisible-by-n"></a>

#### Even or odd, divisible by n

```python
for n in [4, 7, 15]:
    if n % 2 == 0:
        print(n, "is even")
    else:
        print(n, "is odd")
print(15 % 5 == 0)      # divisible by 5?
```

**Output**

```text
4 is even
7 is odd
15 is odd
True
```

<a name="c2-whole-number-division-and-remainder-together"></a>

#### Whole-number division and remainder together

```python
minutes = 135
hours = minutes // 60
left = minutes % 60
print(f"{hours}h {left}m")
print(divmod(135, 60))
```

**Output**

```text
2h 15m
(2, 15)
```

<a name="c2-sum-average-min-max-of-numbers"></a>

#### Sum, average, min, max of numbers

```python
values = [12, 7, 30, 5]
total = sum(values)
average = total / len(values)
print(total, average, min(values), max(values))
```

**Output**

```text
54 13.5 5 30
```

**Divide by zero**

`sum([]) / len([])` crashes with `ZeroDivisionError`. Check `if len(values) > 0:` first.

<a name="c2-a-running-total-in-a-loop-accumulator"></a>

#### A running total in a loop (accumulator)

```python
total = 0
for n in range(1, 101):
    total += n
print(total)
```

**Output**

```text
5050
```

<a name="c2-count-how-many-items-match-a-condition-counter"></a>

#### Count how many items match a condition (counter)

```python
numbers = [2, 4, 5, 8, 11]
evens = 0
odds = 0
for n in numbers:
    if n % 2 == 0:
        evens += 1
    else:
        odds += 1
print(f"There were {evens} even and {odds} odd numbers.")
```

**Output**

```text
There were 3 even and 2 odd numbers.
```

<a name="c2-random-numbers"></a>

#### Random numbers

```python
import random

print(random.randint(1, 10))          # 1 to 10 INCLUSIVE
print(random.randrange(1, 10))        # 1 to 9 (stop excluded, like range)
print(random.choice(["rock", "paper", "scissors"]))
print(random.sample(range(100), 5))   # 5 different numbers
```

**Output**

```text
6
3
paper
[83, 6, 9, 68, 12]
```

<a name="c2-absolute-value-power-rounding"></a>

#### Absolute value, power, rounding

```python
print(abs(-7), 2 ** 10, pow(3, 2), round(3.14159, 2), round(2.5), round(3.5))
```

**Output**

```text
7 1024 9 3.14 2 4
```

`round()` uses *banker's rounding* for exact halves: `round(2.5)` is `2`, `round(3.5)` is `4`.

<a name="c2-strings"></a>

### Strings

<a name="c2-length-index-slice"></a>

#### Length, index, slice

```python
word = "Python"
print(len(word))        # 6
print(word[0], word[-1])  # first, last
print(word[1:4])        # index 1 up to (not incl.) 4
print(word[:2], word[2:])
print(word[::-1])       # reversed
```

**Output**

```text
6
P n
yth
Py thon
nohtyP
```

<a name="c2-change-case-test-content"></a>

#### Change case, test content

```python
s = "Hello World"
print(s.upper(), s.lower(), s.title(), s.swapcase())
print(s.startswith("He"), s.endswith("!"), "World" in s)
print("123".isdigit(), "abc".isalpha(), "   ".isspace())
```

**Output**

```text
HELLO WORLD hello world Hello World hELLO wORLD
True False True
True True True
```

<a name="c2-clean-up-user-input-spaces-case"></a>

#### Clean up user input (spaces, case)

```python
answer = input("Continue? ").strip().lower()
if answer == "yes":
    print("Continuing")
```

**Output**

```text
Continue?    YeS   ↵
Continuing
```

<a name="c2-split-a-sentence-into-words-and-join-words-back"></a>

#### Split a sentence into words, and join words back

```python
sentence = "the quick brown fox"
words = sentence.split()            # splits on any whitespace
print(words)
print("-".join(words))
print("a,b,,c".split(","))          # note the empty string
```

**Output**

```text
['the', 'quick', 'brown', 'fox']
the-quick-brown-fox
['a', 'b', '', 'c']
```

<a name="c2-replace-find-count"></a>

#### Replace, find, count

```python
s = "banana"
print(s.replace("a", "o"), s.find("n"), s.find("z"), s.count("a"))
```

**Output**

```text
bonono 2 -1 3
```

`find` returns `-1` when the text is not found. `index` would crash instead.

<a name="c2-loop-through-characters-with-their-positions"></a>

#### Loop through characters with their positions

```python
word = "Hello"
for position in range(len(word)):
    print(f"index {position}: {word[position]}")
```

**Output**

```text
index 0: H
index 1: e
index 2: l
index 3: l
index 4: o
```

`for position, char in enumerate(word):` gives you both at once (see *Loop with an index and the item* below).

<a name="c2-reverse-a-string-with-a-loop-no-slicing"></a>

#### Reverse a string with a loop (no slicing)

```python
phrase = "sucoP sucoH"
reversed_phrase = ""
for i in range(len(phrase) - 1, -1, -1):
    reversed_phrase += phrase[i]
print(reversed_phrase)
```

**Output**

```text
Hocus Pocus
```

<a name="c2-character-ascii-code"></a>

#### Character ↔ ASCII code

```python
print(ord("a"), ord("A"), chr(109), chr(65))
code = 109
if code in range(32, 127):            # printable characters 32-126
    print(f"The character for {code} is {chr(code)}")
```

**Output**

```text
97 65 m A
The character for 109 is m
```

<a name="c2-repeat-a-string-mirror-it-alternate-case"></a>

#### Repeat a string, mirror it, alternate case

```python
word = "Hello"
print(word * 3)
print(f"{word} | {word[::-1]}")
for i in range(4):
    print(word.upper() if i % 2 == 0 else word.lower())
```

**Output**

```text
HelloHelloHello
Hello | olleH
HELLO
hello
HELLO
hello
```

<a name="c2-decisions"></a>

### Decisions

<a name="c2-choose-between-several-mutually-exclusive-options"></a>

#### Choose between several mutually exclusive options

```python
direction = input("Which way? ")
if direction == "up":
    print("Moving up")
elif direction == "down":
    print("Moving down")
elif direction == "left" or direction == "right":
    print(f"Moving {direction}")
else:
    print("Unknown direction")
```

**Output**

```text
Which way? left ↵
Moving left
```

<a name="c2-test-a-value-against-a-list-of-options"></a>

#### Test a value against a list of options

```python
shape = "rhombus"
if shape in ("square", "rectangle", "rhombus"):
    print("This shape is a parallelogram.")
```

**Output**

```text
This shape is a parallelogram.
```

<a name="c2-check-a-number-is-inside-a-range"></a>

#### Check a number is inside a range

```python
age = 17
if 13 <= age <= 19:
    print("teenager")
if age < 0 or age > 120:
    print("invalid age")
```

**Output**

```text
teenager
```

<a name="c2-combine-conditions-with-and-or-not"></a>

#### Combine conditions with and / or / not

```python
heard, saw = "grrr", "two red eyes"
if heard == "grrr" and saw == "two red eyes":
    print("Run!")
if not (heard == "hoot"):
    print("Not an owl")
```

**Output**

```text
Run!
Not an owl
```

**Classic trap**

`if colour == "red" or "blue":` is **always true**, because `"blue"` on its own is truthy. Write `colour == "red" or colour == "blue"`, or use `colour in ("red", "blue")`.

<a name="c2-nested-decision-a-question-that-depends-on-the-answer-before"></a>

#### Nested decision (a question that depends on the answer before)

```python
activity = input("What should I do (recover/study)? ")
if activity == "recover":
    how = input("How (sleep/socialise)? ")
    if how == "sleep":
        print("zzzZZZzzz")
    else:
        print("I will text my friends!")
else:
    print("I will study")
```

**Output**

```text
What should I do (recover/study)? recover ↵
How (sleep/socialise)? sleep ↵
zzzZZZzzz
```

<a name="c2-loops"></a>

### Loops

<a name="c2-repeat-exactly-n-times"></a>

#### Repeat exactly n times

```python
times = int(input("How many? "))
for i in range(times):
    print("Removed apple.")
```

**Output**

```text
How many? 3 ↵
Removed apple.
Removed apple.
Removed apple.
```

<a name="c2-count-down"></a>

#### Count down

```python
for steps in range(5, 0, -1):
    print(f"{steps} steps remaining")
print("Target achieved!")
```

**Output**

```text
5 steps remaining
4 steps remaining
3 steps remaining
2 steps remaining
1 steps remaining
Target achieved!
```

<a name="c2-even-numbers-odd-numbers-every-nth"></a>

#### Even numbers, odd numbers, every nth

```python
print(list(range(2, 11, 2)))
print(list(range(1, 10, 2)))
print(list(range(0, 31, 10)))
```

**Output**

```text
[2, 4, 6, 8, 10]
[1, 3, 5, 7, 9]
[0, 10, 20, 30]
```

<a name="c2-read-numbers-until-the-user-types-a-stop-word-sentinel-loop"></a>

#### Read numbers until the user types a stop word (sentinel loop)

```python
total = 0
while True:
    entry = input("Number (or 'done'): ")
    if entry == "done":
        break
    total += int(entry)
print("Total:", total)
```

**Output**

```text
Number (or 'done'): 4 ↵
Number (or 'done'): 10 ↵
Number (or 'done'): done ↵
Total: 14
```

<a name="c2-a-menu-that-repeats-until-the-user-quits"></a>

#### A menu that repeats until the user quits

```python
def show_menu():
    print("[a] Say hello")
    print("[q] Quit")
    return input("Choice: ").strip().lower()


while True:
    choice = show_menu()
    if choice == "a":
        print("Hello!")
    elif choice == "q":
        print("Goodbye")
        break
    else:
        print("Invalid option! Please try again.")
```

**Output**

```text
[a] Say hello
[q] Quit
Choice: a ↵
Hello!
[a] Say hello
[q] Quit
Choice: z ↵
Invalid option! Please try again.
[a] Say hello
[q] Quit
Choice: q ↵
Goodbye
```

**AE1 tip**

Loading data and printing a title belong **before** the loop. Anything inside `while True:` happens again on every pass.

<a name="c2-a-grid-with-nested-loops"></a>

#### A grid with nested loops

```python
rows, cols = 2, 3
for r in range(rows):
    for c in range(cols):
        print(":-)", end=" ")
    print()          # new line after each row
```

**Output**

```text
:-) :-) :-) 
:-) :-) :-) 
```

<a name="c2-build-a-growing-bar-or-pattern"></a>

#### Build a growing bar or pattern

```python
for bars in range(1, 6):
    print("Charging: " + "█ " * bars)
for level in range(2, 7, 2):
    print("Brightness level: " + "*" * level)
```

**Output**

```text
Charging: █ 
Charging: █ █ 
Charging: █ █ █ 
Charging: █ █ █ █ 
Charging: █ █ █ █ █ 
Brightness level: **
Brightness level: ****
Brightness level: ******
```

<a name="c2-count-characters-between-two-markers"></a>

#### Count characters between two markers

```python
sequence = "--x---x--"
marker = "x"
first = sequence.find(marker)
second = sequence.find(marker, first + 1)
print("The distance between the markers is", second - first - 1)
```

**Output**

```text
The distance between the markers is 3
```

<a name="c2-loop-over-two-lists-side-by-side"></a>

#### Loop over two lists side by side

```python
names = ["Ann", "Tom", "Raj"]
ages = [34, 29, 41]
for name, age in zip(names, ages):
    print(f"{name} is {age}")
```

**Output**

```text
Ann is 34
Tom is 29
Raj is 41
```

<a name="c2-loop-with-an-index-and-the-item-enumerate"></a>

#### Loop with an index and the item (enumerate)

```python
items = ["Move Forward", "Move Backward", "Turn Left"]
for index, item in enumerate(items):
    print(f"{index}: {item}")
for number, item in enumerate(items, start=1):
    print(f"[{number}] {item}")
```

**Output**

```text
0: Move Forward
1: Move Backward
2: Turn Left
[1] Move Forward
[2] Move Backward
[3] Turn Left
```

<a name="c3-task-index-2-functions-modules-lists-tuples-sets-dictionaries"></a>

## Part 3: Task index 2: functions, modules, lists, tuples, sets, dictionaries

<a name="c3-functions"></a>

### Functions

<a name="c3-write-a-function-that-takes-inputs-and-gives-back-a-result"></a>

#### Write a function that takes inputs and gives back a result

```python
def sum_weights(person, inventory):
    return person + inventory


def calc_avg_weight(person, inventory):
    return sum_weights(person, inventory) / 2


print(sum_weights(12, 6), calc_avg_weight(12, 6))
```

**Output**

```text
18 9.0
```

**print vs return**

`print` shows a value on screen and the function still gives back `None`. `return` hands the value back to the caller so it can be stored or used. If a question says "the function should **return**…", printing inside it is wrong.

```python
def shout_print(word):
    print(word.upper())


def shout_return(word):
    return word.upper()


a = shout_print("hi")     # prints HI, but a is None
b = shout_return("hi")    # prints nothing, b is "HI"
print(a, b)
```

**Output**

```text
HI
None HI
```

<a name="c3-return-more-than-one-value"></a>

#### Return more than one value

```python
def min_max(values):
    return min(values), max(values)      # really returns a tuple


low, high = min_max((50, 38, 27, 99, 4))
print(f"Minimum: {low}%  Maximum: {high}%")
```

**Output**

```text
Minimum: 4%  Maximum: 99%
```

<a name="c3-give-a-parameter-a-default-value"></a>

#### Give a parameter a default value

```python
def started(msg=""):
    print("-" * 30)
    print(f"Operation started: {msg}...")


started("Reading data")
started()
```

**Output**

```text
------------------------------
Operation started: Reading data...
------------------------------
Operation started: ...
```

Defaults must come **after** parameters without defaults: `def f(a, b=1)` is fine, `def f(a=1, b)` is a `SyntaxError`.

<a name="c3-use-a-global-variable-inside-a-function"></a>

#### Use a global variable inside a function

```python
records = []          # global


def load():
    records.append("row 1")      # changing a list in place: no 'global' needed


def reset():
    global records               # REASSIGNING needs 'global'
    records = []


load()
load()
print(len(records))
reset()
print(len(records))
```

**Output**

```text
2
0
```

**Tip**

Prefer passing values in as parameters and handing results back with `return` over using globals. The module's Titanic case study uses globals, but parameters and return values are what the marking criteria reward.

<a name="c3-write-a-docstring"></a>

#### Write a docstring

```python
def display_box(name):
    """Display 'Hello {name}' inside a box of asterisks.

    name -- the text to greet
    """
    message = f"* Hello {name} *"
    print("*" * len(message))
    print(message)
    print("*" * len(message))
```

<a name="c3-modules-and-program-structure"></a>

### Modules and program structure

<a name="c3-import-a-module-a-function-or-rename-it"></a>

#### Import a module, a function, or rename it

```python
import random
import random as rnd
from random import randrange
import math

print(random.randint(1, 3), rnd.randint(1, 3), randrange(1, 3), math.sqrt(16), math.pi)
```

**Output**

```text
2 1 2 4.0 3.141592653589793
```

<a name="c3-split-a-program-across-files-and-call-functions-in-another-file"></a>

#### Split a program across files and call functions in another file

File: tui.py

```python
def error(msg):
    print(f"Error! {msg}")


def menu():
    print("[a] Run")
    print("[q] Quit")
    return input("Your selection: ")
```

File: main.py

```python
import tui


def run():
    while True:
        selection = tui.menu()
        if selection == "a":
            print("Running...")
        elif selection == "q":
            break
        else:
            tui.error("Invalid Selection!")


if __name__ == "__main__":
    run()
```

**Output**

```text
[a] Run
[q] Quit
Your selection: x ↵
Error! Invalid Selection!
[a] Run
[q] Quit
Your selection: q ↵
```

Both files must be in the **same folder** (or a package path such as `import week1.output_tasks as wk1_output`).

<a name="c3-stop-a-files-code-running-when-it-is-imported"></a>

#### Stop a file's code running when it is imported

```python
def simple_message():
    print("Welcome!")


# True only when THIS file is run directly, not when imported
if __name__ == "__main__":
    simple_message()
```

<a name="c3-lists"></a>

### Lists

<a name="c3-create-add-insert-remove"></a>

#### Create, add, insert, remove

```python
fruits = ["apple", "banana"]
fruits.append("cherry")          # end
fruits.insert(0, "kiwi")         # at index 0
fruits.remove("banana")          # first matching VALUE
last = fruits.pop()              # removes + returns the last item
del fruits[0]                    # by INDEX
print(fruits, last)
```

**Output**

```text
['apple'] cherry
```

<a name="c3-access-change-slice"></a>

#### Access, change, slice

```python
nums = [10, 20, 30, 40, 50]
nums[1] = 99
print(nums[0], nums[-1], nums[1:3], nums[:2], nums[3:], nums[::2])
print(len(nums), 30 in nums, nums.index(30), nums.count(10))
```

**Output**

```text
10 50 [99, 30] [10, 99] [40, 50] [10, 30, 50]
5 True 2 1
```

<a name="c3-build-a-list-from-user-input"></a>

#### Build a list from user input

```python
colours = []
for i in range(3):
    colours.append(input(f"Colour {i + 1}: "))
print(colours)
```

**Output**

```text
Colour 1: red ↵
Colour 2: blue ↵
Colour 3: red ↵
['red', 'blue', 'red']
```

<a name="c3-build-a-list-from-another-list-filter-transform"></a>

#### Build a list from another list (filter, transform)

```python
scores = [72, 45, 88, 30, 61]
passed = []
for s in scores:
    if s >= 40:
        passed.append(s)
print(passed)
doubled = [s * 2 for s in scores]                 # list comprehension
print(doubled, [s for s in scores if s < 50])
```

**Output**

```text
[72, 45, 88, 61]
[144, 90, 176, 60, 122] [45, 30]
```

<a name="c3-sort-in-place-vs-a-new-copy-ascending-vs-descending"></a>

#### Sort: in place vs a new copy, ascending vs descending

```python
nums = [3, 1, 2]
print(sorted(nums), nums)            # new list; original unchanged
nums.sort(reverse=True)              # changes nums, returns None
print(nums)
words = ["pear", "fig", "banana"]
print(sorted(words, key=len))        # by length
print(sorted(words, key=str.lower))  # case-insensitive
```

**Output**

```text
[1, 2, 3] [3, 1, 2]
[3, 2, 1]
['fig', 'pear', 'banana']
['banana', 'fig', 'pear']
```

<a name="c3-find-the-largestsmallest-item-and-where-it-is"></a>

#### Find the largest/smallest item and where it is

```python
temps = [19, 23, 21, 18, 22]
hottest = max(temps)
print(hottest, temps.index(hottest))
```

**Output**

```text
23 1
```

<a name="c3-copy-a-list-so-changes-do-not-affect-the-original"></a>

#### Copy a list (so changes do not affect the original)

```python
a = [1, 2, 3]
b = a            # same list, two names
c = a.copy()     # real copy (also: list(a) or a[:])
a.append(4)
print(a, b, c)
```

**Output**

```text
[1, 2, 3, 4] [1, 2, 3, 4] [1, 2, 3]
```

<a name="c3-a-list-of-lists-rows-and-columns"></a>

#### A list of lists (rows and columns)

```python
rows = [["id", "name"], ["1", "Shirt"], ["2", "Coat"]]
headings = rows[0]
for row in rows[1:]:
    print(row[1])
print(rows[2][1])
```

**Output**

```text
Shirt
Coat
Coat
```

<a name="c3-tuples"></a>

### Tuples

<a name="c3-create-read-unpack"></a>

#### Create, read, unpack

```python
person = ("Bob", 40, "Lecturer")
name, age, job = person
print(person[0], age, len(person), "Lecturer" in person)
single = (5,)      # one-item tuple needs a comma
print(type(single), type((5)))
```

**Output**

```text
Bob 40 3 True
<class 'tuple'> <class 'int'>
```

<a name="c3-a-list-of-tuples-filtered-into-two-groups"></a>

#### A list of tuples, filtered into two groups

```python
steps = [("step 1", 50), ("step 2", 38), ("step 3", 27), ("step 4", 99), ("step 5", 4)]
good_steps, bad_steps = [], []
for step in steps:
    if step[1] >= 50:
        bad_steps.append(step)
    else:
        good_steps.append(step)
print(f"Good steps: {len(good_steps)}, Bad steps: {len(bad_steps)}")
```

**Output**

```text
Good steps: 3, Bad steps: 2
```

<a name="c3-sort-a-list-of-tuples-by-the-second-item"></a>

#### Sort a list of tuples by the second item

```python
steps = [("step 1", 50), ("step 2", 38), ("step 5", 4)]
print(sorted(steps, key=lambda step: step[1]))
print(sorted(steps, key=lambda step: step[1], reverse=True))
```

**Output**

```text
[('step 5', 4), ('step 2', 38), ('step 1', 50)]
[('step 1', 50), ('step 2', 38), ('step 5', 4)]
```

<a name="c3-sets"></a>

### Sets

<a name="c3-remove-duplicates"></a>

#### Remove duplicates

```python
observations = ["Car", "Sky Scraper", "Sky Scraper", "Bike", "House", "House"]
unique = set(observations)
print(len(unique), sorted(unique))
```

**Output**

```text
4 ['Bike', 'Car', 'House', 'Sky Scraper']
```

<a name="c3-collect-distinct-values-while-looping"></a>

#### Collect distinct values while looping

```python
import csv

houses = set()
with open("scores.csv") as file:
    reader = csv.reader(file)
    next(reader)
    for row in reader:
        houses.add(row[1])
print(sorted(houses))
print(sorted(houses, reverse=True))   # sorted() returns a LIST
```

**Output**

```text
['Blue', 'Green', 'Red']
['Red', 'Green', 'Blue']
```

<a name="c3-add-remove-test-membership"></a>

#### Add, remove, test membership

```python
s = {"Chrome", "Firefox"}
s.add("Edge")
s.add("Edge")                 # duplicate ignored
s.discard("Opera")            # no error if missing
s.remove("Firefox")           # KeyError if missing
print(sorted(s), "Edge" in s)
```

**Output**

```text
['Chrome', 'Edge'] True
```

<a name="c3-union-intersection-difference"></a>

#### Union, intersection, difference

```python
a = {1, 2, 3, 4}
b = {3, 4, 5}
print(a | b, a & b, a - b, a ^ b)
print(a.union(b), a.intersection(b), a.difference(b))
```

**Output**

```text
{1, 2, 3, 4, 5} {3, 4} {1, 2} {1, 2, 5}
{1, 2, 3, 4, 5} {3, 4} {1, 2}
```

<a name="c3-dictionaries"></a>

### Dictionaries

<a name="c3-create-read-add-change-delete"></a>

#### Create, read, add, change, delete

```python
stock = {"Cake": 1, "Car": 1}
stock["Ribbons"] = 100       # add
stock["Cake"] = 2            # change
print(stock["Cake"], len(stock))
del stock["Car"]
print(stock)
print(stock.get("Balloons"), stock.get("Balloons", 0))   # safe read
```

**Output**

```text
2 3
{'Cake': 2, 'Ribbons': 100}
None 0
```

<a name="c3-loop-through-keys-values-or-both"></a>

#### Loop through keys, values, or both

```python
sequences = {"Short Sequence": 3, "Medium Sequence": 2, "Long Sequence": 1}
for key in sequences:
    print(key)
for value in sequences.values():
    print(value)
for key, value in sequences.items():
    print(f"{key}: {value}")
```

**Output**

```text
Short Sequence
Medium Sequence
Long Sequence
3
2
1
Short Sequence: 3
Medium Sequence: 2
Long Sequence: 1
```

<a name="c3-count-how-often-each-value-occurs"></a>

#### Count how often each value occurs

```python
words = ["red", "blue", "red", "green", "red", "blue"]
counts = {}
for w in words:
    if w in counts:
        counts[w] += 1
    else:
        counts[w] = 1
print(counts)

counts2 = {}
for w in words:
    counts2[w] = counts2.get(w, 0) + 1     # same thing in one line
print(counts2 == counts)
```

**Output**

```text
{'red': 3, 'blue': 2, 'green': 1}
True
```

<a name="c3-tally-fixed-categories-start-every-count-at-zero"></a>

#### Tally fixed categories (start every count at zero)

```python
results = ["Gold", "NA", "Silver", "Gold", "Bronze", "NA"]
tally = {"Gold": 0, "Silver": 0, "Bronze": 0}
for medal in results:
    if medal in tally:
        tally[medal] += 1
print(tally)
```

**Output**

```text
{'Gold': 2, 'Silver': 1, 'Bronze': 1}
```

<a name="c3-group-rows-by-a-category-dictionary-of-lists"></a>

#### Group rows by a category (dictionary of lists)

```python
import csv

by_house = {}
with open("scores.csv") as file:
    reader = csv.reader(file)
    next(reader)
    for name, house, subject, score in reader:
        if house not in by_house:
            by_house[house] = []
        by_house[house].append(int(score))
print(by_house)
```

**Output**

```text
{'Red': [72, 88, 60], 'Blue': [65, 54, 83], 'Green': [91, 77]}
```

<a name="c3-average-per-category"></a>

#### Average per category

```python
by_house = {"Red": [72, 88, 60], "Blue": [65, 54, 83], "Green": [91, 77]}
averages = {}
for house, scores in by_house.items():
    averages[house] = sum(scores) / len(scores)
for house, avg in averages.items():
    print(f"{house:<6} {avg:.1f}")
```

**Output**

```text
Red    73.3
Blue   67.3
Green  84.0
```

<a name="c3-nested-dictionary-a-count-per-category-per-group"></a>

#### Nested dictionary: a count per category per group

```python
rows = [("Finland", "Gold"), ("Norway", "Silver"), ("Finland", "Bronze"), ("Finland", "Gold")]
team_tally = {}
for team, medal in rows:
    if team not in team_tally:
        team_tally[team] = {"Gold": 0, "Silver": 0, "Bronze": 0}
    team_tally[team][medal] += 1
for team, medals in team_tally.items():
    print(team)
    print(f"  Gold:{medals['Gold']}, Silver:{medals['Silver']}, Bronze:{medals['Bronze']}")
```

**Output**

```text
Finland
  Gold:2, Silver:0, Bronze:1
Norway
  Gold:0, Silver:1, Bronze:0
```

<a name="c3-sort-a-dictionary-by-value-and-take-the-top-n"></a>

#### Sort a dictionary by value and take the top n

```python
averages = {"Red": 73.3, "Blue": 67.3, "Green": 84.0, "Pink": 70.1}
ranked = sorted(averages.items(), key=lambda pair: pair[1], reverse=True)
print(ranked)
for name, value in ranked[:2]:
    print(name, value)
```

**Output**

```text
[('Green', 84.0), ('Red', 73.3), ('Pink', 70.1), ('Blue', 67.3)]
Green 84.0
Red 73.3
```

`dict.items()` gives `(key, value)` pairs, `key=lambda pair: pair[1]` sorts by the value, and `[:n]` keeps the first n.

<a name="c3-get-the-keys-and-values-as-separate-lists-for-charts"></a>

#### Get the keys and values as separate lists (for charts)

```python
tally = {"Gold": 13372, "Silver": 13116, "Bronze": 13295}
labels = list(tally.keys())
values = list(tally.values())
print(labels, values)
```

**Output**

```text
['Gold', 'Silver', 'Bronze'] [13372, 13116, 13295]
```

<a name="c3-find-the-key-with-the-biggest-value"></a>

#### Find the key with the biggest value

```python
counts = {"red": 3, "blue": 2, "green": 1}
best = max(counts, key=counts.get)
print(best, counts[best])
```

**Output**

```text
red 3
```

<a name="c4-task-index-3-files-json-charts-classes"></a>

## Part 4: Task index 3: files, JSON, charts, classes

<a name="c4-paths-and-folders"></a>

### Paths and folders

<a name="c4-see-where-python-is-running-and-what-files-are-there"></a>

#### See where Python is running and what files are there

```python
import os

path = os.getcwd()
print(f"The current working directory is {path}")
for name in os.listdir(path):
    print(name)
```

Relative paths like `"data.csv"` are looked up **from the current working directory**, not from the folder your `.py` file is in. In PyCharm that is normally the folder of the file you clicked Run on, but check with `os.getcwd()` when a file "cannot be found".

<a name="c4-relative-path-cheat-sheet"></a>

#### Relative path cheat sheet

| Path                                    | Means                              |
|-----------------------------------------|------------------------------------|
| `data.csv` or `./data.csv`              | in the current folder              |
| `data/data.csv`                         | in a sub-folder called `data`      |
| `../data.csv`                           | in the parent folder               |
| `../../x.txt`                           | two folders up                     |
| `/home/me/x.txt` or `C:/Users/me/x.txt` | absolute path (starts at the root) |

Use forward slashes `/`. They work on Windows too. A Windows backslash path needs `r"C:\Users\me\x.txt"`, because `\U` and `\n` are escape characters.

<a name="c4-check-a-file-exists-before-opening-it"></a>

#### Check a file exists before opening it

```python
import os

for name in ["clothing.csv", "nope.csv"]:
    print(name, os.path.exists(name))
```

**Output**

```text
clothing.csv True
nope.csv False
```

<a name="c4-text-files"></a>

### Text files

<a name="c4-read-the-whole-file-a-few-characters-or-the-first-line"></a>

#### Read the whole file, a few characters, or the first line

```python
with open("library.txt") as file:
    print(file.read(5))            # first 5 characters
with open("library.txt") as file:
    print(file.readline().strip()) # first line, without the \n
with open("library.txt") as file:
    text = file.read()             # everything as one string
print(text.split("\n"))
```

**Output**

```text
The L
The Law Section
['The Law Section', 'The Art Section', 'The Technology Section', 'The History Section', '']
```

<a name="c4-read-line-by-line"></a>

#### Read line by line

```python
with open("library.txt") as file:
    for line in file:
        print(f"Looked in {line.strip()}")
print("...Done!")
```

**Output**

```text
Looked in The Law Section
Looked in The Art Section
Looked in The Technology Section
Looked in The History Section
...Done!
```

Each `line` ends with `\n`. Without `.strip()` you get blank lines between the printed ones.

<a name="c4-all-lines-as-a-list"></a>

#### All lines as a list

```python
with open("library.txt") as file:
    lines = file.read().splitlines()   # no \n characters
print(lines)
```

**Output**

```text
['The Law Section', 'The Art Section', 'The Technology Section', 'The History Section']
```

<a name="c4-write-overwrite-and-append"></a>

#### Write (overwrite) and append

```python
with open("output.txt", "w") as file:      # "w" wipes the file first
    file.write("first line\n")
    file.write("second line\n")
with open("output.txt", "a") as file:      # "a" adds to the end
    file.write("third line\n")
with open("output.txt") as file:
    print(file.read())
```

**Output**

```text
first line
second line
third line
```

**Common mistake**

`write` does **not** add a newline for you. Forget the `\n` and every value ends up on one line.

<a name="c4-file-modes"></a>

#### File modes

| Mode            | Opens for                      | If missing                | If exists               |
|-----------------|--------------------------------|---------------------------|-------------------------|
| `"r"` (default) | reading                        | error `FileNotFoundError` | reads it                |
| `"w"`           | writing                        | creates it                | **empties it**          |
| `"a"`           | appending                      | creates it                | adds to the end         |
| `"x"`           | creating                       | creates it                | error `FileExistsError` |
| add `"b"`       | binary, e.g. `"rb"` for images |                           |                         |

<a name="c4-csv-files"></a>

### CSV files

<a name="c4-read-a-csv-keeping-headings-separate"></a>

#### Read a CSV, keeping headings separate

```python
import csv

with open("clothing.csv") as file:
    reader = csv.reader(file)
    headings = next(reader)
    print("Headings:", headings)
    for values in reader:
        print(values)
```

**Output**

```text
Headings: ['id', 'name', 'colour']
['1', 'Shirt', 'Mercury']
['2', 'Coat', 'Boulder']
['3', 'Trousers', 'Black']
```

<a name="c4-load-every-row-into-a-list-and-report-how-many"></a>

#### Load every row into a list (and report how many)

```python
import csv


def load_data(file_path):
    rows = []
    with open(file_path) as file:
        reader = csv.reader(file)
        next(reader)                       # skip headings
        for row in reader:
            rows.append(row)
    return rows


data = load_data("scores.csv")
print(f"Successfully loaded {len(data)} records.")
```

**Output**

```text
Successfully loaded 8 records.
```

<a name="c4-convert-columns-to-numbers-while-reading"></a>

#### Convert columns to numbers while reading

```python
import csv

total = 0
with open("scores.csv") as file:
    reader = csv.reader(file)
    next(reader)
    for row in reader:
        total += int(row[3])      # every CSV value arrives as a string
print(total)
```

**Output**

```text
590
```

<a name="c4-values-with-commas-or-blanks-why-you-use-the-csv-module"></a>

#### Values with commas or blanks (why you use the csv module)

```python
import csv

with open("people.csv") as file:
    reader = csv.reader(file)
    next(reader)
    for row in reader:
        name, age_text = row[1], row[2]
        if age_text == "":
            print(f"{name}: age unknown")
        else:
            print(f"{name}: {float(age_text)}")   # float, because ages like 0.5 exist
```

**Output**

```text
Smith, Ann: 34.0
Jones, Tom: age unknown
Patel, Raj: 0.5
```

The name `"Smith, Ann"` contains a comma. `line.split(",")` would break it into two columns, but `csv.reader` respects the quotes.

<a name="c4-read-rows-as-dictionaries-column-names-as-keys"></a>

#### Read rows as dictionaries (column names as keys)

```python
import csv

with open("clothing.csv") as file:
    for row in csv.DictReader(file):
        print(row["name"], row["colour"])
```

**Output**

```text
Shirt Mercury
Coat Boulder
Trousers Black
```

<a name="c4-write-a-csv-file"></a>

#### Write a CSV file

```python
import csv

rows = [["id", "name", "colour"], [4, "Skirt", "Cyan"], [5, "Hat", "Red"]]
with open("exported.csv", "w", newline="") as file:
    writer = csv.writer(file)
    writer.writerows(rows)             # or writer.writerow(one_row)
with open("exported.csv") as file:
    print(file.read())
```

**Output**

```text
id,name,colour
4,Skirt,Cyan
5,Hat,Red
```

`newline=""` stops blank lines appearing between rows on Windows.

<a name="c4-append-one-line-to-an-existing-csv-by-hand"></a>

#### Append one line to an existing CSV by hand

```python
with open("clothing.csv", "a") as file:
    file.write("4,Skirt,Cyan\n")
with open("clothing.csv") as file:
    print(file.read())
```

**Output**

```text
id,name,colour
1,Shirt,Mercury
2,Coat,Boulder
3,Trousers,Black
4,Skirt,Cyan
```

<a name="c4-json-files"></a>

### JSON files

<a name="c4-read-json-into-python"></a>

#### Read JSON into Python

```python
import json

with open("robots.json") as file:
    data = json.load(file)                 # dict / list structure
print(f"Place Name: {data['location']}")
print(f"Population Size: {data['population']}")
for bot in data["bots"]:
    stats = bot["stats"]
    print(f"{bot['name']} has a strength level of {stats['strength']} and a speed level of {stats['speed']}.")
```

**Output**

```text
Place Name: Earth
Population Size: 1000000
Bolt has a strength level of 8 and a speed level of 5.
Cog has a strength level of 10 and a speed level of 3.
Spark has a strength level of 5 and a speed level of 10.
```

JSON `{}` becomes a Python `dict`, `[]` a `list`, `true`/`false` `True`/`False`, and `null` `None`.

<a name="c4-write-python-data-to-json"></a>

#### Write Python data to JSON

```python
import json

data = {"name": "Bolt", "type": "Bot", "tags": ["fast", "small"]}
with open("exported.json", "w") as file:
    json.dump(data, file, indent=4)
with open("exported.json") as file:
    print(file.read())
print(json.dumps(data))            # to a string instead of a file
```

**Output**

```text
{
    "name": "Bolt",
    "type": "Bot",
    "tags": [
        "fast",
        "small"
    ]
}
{"name": "Bolt", "type": "Bot", "tags": ["fast", "small"]}
```

<a name="c4-charts-matplotlib"></a>

### Charts (matplotlib)

<a name="c4-line-chart-with-labels-and-title"></a>

#### Line chart with labels and title

```python
import matplotlib.pyplot as plt

x_values = [1, 2, 3, 4, 5]
y_values = [1, 4, 9, 16, 25]
plt.plot(x_values, y_values, "ro--", label="squares")   # red, circles, dashed
plt.title("Square numbers")
plt.xlabel("n")
plt.ylabel("n squared")
plt.legend()
plt.show()
```

**Output**

![matplotlib output](images/QHO444_Open_Book_Reference/figure-01.png) <a name="c4-format-strings-for-pltplot"></a>

#### Format strings for `plt.plot`

| Part   | Codes                                                                                                    |
|--------|----------------------------------------------------------------------------------------------------------|
| Colour | `r` red, `g` green, `b` blue, `c` cyan, `m` magenta, `y` yellow, `k` black, `w` white                    |
| Marker | `o` circle, `s` square, `^` triangle up, `v` triangle down, `p` pentagon, `*` star, `x` cross, `.` point |
| Line   | `-` solid, `--` dashed, `-.` dash-dot, `:` dotted                                                        |

Combine them in any order: `"g--s"`, `"bp-"`, `"k:"`. A marker with no line code draws markers only.

<a name="c4-several-lines-on-one-chart"></a>

#### Several lines on one chart

```python
import matplotlib.pyplot as plt

plt.plot([0, 1, 1, 0, 0], [0, 0, 1, 1, 0], "r:o", label="small")
plt.plot([-1, 2, 2, -1, -1], [-1, -1, 2, 2, -1], "g--s", label="medium")
plt.plot([-2, 3, 3, -2, -2], [-2, -2, 3, 3, -2], "b-p", label="large")
plt.title("Nested squares")
plt.legend()
plt.axis("equal")
plt.show()
```

**Output**

![matplotlib output](images/QHO444_Open_Book_Reference/figure-02.png) <a name="c4-bar-chart-from-a-dictionary"></a>

#### Bar chart from a dictionary

```python
import matplotlib.pyplot as plt

tally = {"Gold": 13372, "Silver": 13116, "Bronze": 13295}
plt.bar(list(tally.keys()), list(tally.values()), color=["gold", "silver", "peru"])
plt.title("Medals awarded, 1896-2016")
plt.xlabel("Medal")
plt.ylabel("Number awarded")
plt.show()
```

**Output**

![matplotlib output](images/QHO444_Open_Book_Reference/figure-03.png) <a name="c4-bar-chart-with-long-labels-rotate-or-go-horizontal"></a>

#### Bar chart with long labels (rotate or go horizontal)

```python
import matplotlib.pyplot as plt

names = ["Technology", "History", "Law", "Art and Design", "Geography"]
counts = [42, 30, 25, 18, 9]
plt.figure(figsize=(7, 4))
plt.bar(names, counts)
plt.xticks(rotation=45, ha="right")
plt.title("Books per section")
plt.ylabel("Books")
plt.tight_layout()
plt.show()
```

**Output**

![matplotlib output](images/QHO444_Open_Book_Reference/figure-04.png)

`plt.barh(names, counts)` draws horizontal bars, which suits long names. `plt.tight_layout()` stops rotated labels being cut off.

<a name="c4-pie-chart-with-labels-and-percentages"></a>

#### Pie chart with labels and percentages

```python
import matplotlib.pyplot as plt

labels = ["Red", "Blue", "Green"]
sizes = [3, 3, 2]
plt.pie(sizes, labels=labels, autopct="%1.1f%%", startangle=90)
plt.title("Students per house")
plt.axis("equal")
plt.show()
```

**Output**

![matplotlib output](images/QHO444_Open_Book_Reference/figure-05.png)

`autopct="%1.1f%%"` prints each slice's percentage to one decimal place. The doubled `%%` produces a literal percent sign.

<a name="c4-set-axis-limits-grid-save-to-a-file"></a>

#### Set axis limits, grid, save to a file

```python
import matplotlib.pyplot as plt

plt.plot([1, 2, 3], [3, 1, 2], "b-o")
plt.ylim(0, 5)
plt.grid(True)
plt.title("With limits and grid")
plt.savefig("chart.png")       # save BEFORE show
plt.show()
```

**Output**

![matplotlib output](images/QHO444_Open_Book_Reference/figure-06.png) <a name="c4-bar-values-printed-on-top-of-bars"></a>

#### Bar values printed on top of bars

```python
import matplotlib.pyplot as plt

names = ["A", "B", "C"]
values = [4.2, 3.1, 4.8]
bars = plt.bar(names, values)
for bar, value in zip(bars, values):
    plt.text(bar.get_x() + bar.get_width() / 2, value + 0.05, f"{value:.1f}", ha="center")
plt.ylim(0, 5.5)
plt.title("Labelled bars")
plt.show()
```

**Output**

![matplotlib output](images/QHO444_Open_Book_Reference/figure-07.png) <a name="c4-classes-and-objects"></a>

### Classes and objects

<a name="c4-define-a-class-with-attributes-and-methods"></a>

#### Define a class with attributes and methods

```python
class Human:
    MAX_ENERGY = 100

    def __init__(self, name="Human", age=0):
        self.name = name
        self.age = age
        self.energy = Human.MAX_ENERGY

    def grow(self):
        self.age += 1

    def eat(self, amount):
        self.energy = min(self.energy + amount, Human.MAX_ENERGY)

    def move(self, distance):
        self.energy = max(self.energy - distance, 0)

    def display(self):
        print(f"I am {self.name}")


h = Human("Ada")
h.move(130)
h.grow()
h.display()
print(h.age, h.energy)
```

**Output**

```text
I am Ada
1 0
```

<a name="c4-control-how-an-object-prints-str-and-repr-"></a>

#### Control how an object prints: `__str__` and `__repr__`

```python
class Robot:
    def __init__(self, name="Robot", age=0):
        self.name = name
        self.age = age

    def __repr__(self):
        return f"Robot(name={self.name!r}, age={self.age})"

    def __str__(self):
        return f"Robot {self.name} is {self.age} years old."


r = Robot("Bolt", 3)
print(r)              # uses __str__
print(repr(r))        # uses __repr__
print([r])            # lists show their items' __repr__
```

**Output**

```text
Robot Bolt is 3 years old.
Robot(name='Bolt', age=3)
[Robot(name='Bolt', age=3)]
```

<a name="c4-class-attribute-static-method-class-method"></a>

#### Class attribute, static method, class method

```python
class Robot:
    laws = "Protect, Obey and Survive"       # shared by every Robot

    def __init__(self, name="Robot"):
        self.name = name

    @staticmethod
    def the_laws():                          # no self, no cls
        print(Robot.laws)

    @classmethod
    def assemble(cls):                       # cls is the class itself
        return cls("Assembled Robot")


Robot.the_laws()
bot = Robot.assemble()
print(bot.name)
```

**Output**

```text
Protect, Obey and Survive
Assembled Robot
```

<a name="c4-store-objects-in-a-list-and-loop-over-them"></a>

#### Store objects in a list and loop over them

```python
class Pet:
    def __init__(self, name, kind):
        self.name = name
        self.kind = kind


pets = [Pet("Rex", "dog"), Pet("Tom", "cat"), Pet("Fido", "dog")]
dogs = [p.name for p in pets if p.kind == "dog"]
print(dogs)
```

**Output**

```text
['Rex', 'Fido']
```

<a name="c4-one-class-containing-others-has-a"></a>

#### One class containing others (has-a)

```python
class Planet:
    def __init__(self, name):
        self.name = name
        self.inhabitants = []

    def add_inhabitant(self, inhabitant):
        self.inhabitants.append(inhabitant)

    def remove_inhabitant(self, inhabitant):
        self.inhabitants.remove(inhabitant)

    def __str__(self):
        return f"{self.name}: {len(self.inhabitants)} inhabitants"


earth = Planet("Earth")
earth.add_inhabitant("Ada")
earth.add_inhabitant("Bolt")
print(earth)
```

**Output**

```text
Earth: 2 inhabitants
```

<a name="c4-inherit-from-a-parent-class-is-a-call-the-parents-init-"></a>

#### Inherit from a parent class (is-a), call the parent's `__init__`

```python
class Inhabitant:
    MAX_ENERGY = 100

    def __init__(self, name="Inhabitant", age=0, energy=MAX_ENERGY):
        self.name = name
        self.age = age
        self.energy = energy

    def grow(self):
        self.age += 1


class Human(Inhabitant):
    def __init__(self, name="Human", age=0):
        super().__init__(name, age)          # let the parent set name/age/energy

    def display(self):
        print(f"I am {self.name}, energy {self.energy}")


class Robot(Inhabitant):
    def __init__(self, name="Robot", age=0):
        super().__init__(name, age, energy=0)

    def display(self):
        print(f"BEEP. Unit {self.name}, charge {self.energy}")


for being in [Human("Ada"), Robot("Bolt")]:
    being.grow()                 # inherited method
    being.display()              # each class's own version
```

**Output**

```text
I am Ada, energy 100
BEEP. Unit Bolt, charge 0
```

<a name="c4-check-what-type-an-object-is"></a>

#### Check what type an object is

```python
class Inhabitant: pass
class Human(Inhabitant): pass
class Robot(Inhabitant): pass

everyone = [Human(), Robot(), Human()]
num_humans = 0
for being in everyone:
    if isinstance(being, Human):
        num_humans += 1
print(f"Found {num_humans} humans.")
print(isinstance(Human(), Inhabitant))     # a Human IS an Inhabitant
```

**Output**

```text
Found 2 humans.
True
```

<a name="c4-abstract-class-and-abstract-method"></a>

#### Abstract class and abstract method

```python
from abc import ABC, abstractmethod


class Tech(ABC):
    @abstractmethod
    def activate(self):
        pass

    @abstractmethod
    def deactivate(self):
        pass


class Laser(Tech):
    def activate(self):
        print("Laser charging...")

    def deactivate(self):
        print("Laser off.")

    def fire(self):
        print("Pew!")


laser = Laser()
laser.activate()
laser.fire()
```

**Output**

```text
Laser charging...
Pew!
```

```python
from abc import ABC, abstractmethod


class Tech(ABC):
    @abstractmethod
    def activate(self):
        pass


gadget = Tech()        # not allowed: Tech is abstract
```

**Output (error)**

```text
Traceback (most recent call last):
  File "main.py", line 10, in <module>
    ...
TypeError: Can't instantiate abstract class Tech without an implementation for abstract method 'activate'
```

**Week 10 example**

The course page writes `class Tech:` and `def activate():`. Without `(ABC)` the `@abstractmethod` rule is **not enforced**, and without `self` the method fails as soon as you call it on an object. Use `class Tech(ABC):` and `def activate(self):`.

<a name="c4-class-diagram-notation-for-reports"></a>

#### Class diagram notation (for reports)

```text
+---------------------------+          +----------------------+
|        Inhabitant         |          |        Planet        |
|      <<abstract>>         |          +----------------------+
+---------------------------+  0..*    | name: str            |
| name: str                 |<- - - - -| inhabitants: list    |
| age: int                  |  has     +----------------------+
| energy: int               |          | add_inhabitant()     |
+---------------------------+          | remove_inhabitant()  |
| grow(): None              |          +----------------------+
| eat(amount: int): None    |
| move(distance: int): None |
+---------------------------+
        ^           ^
        | is-a      | is-a        (solid arrow, hollow head = inherits)
+-------------+ +-------------+
|    Human    | |    Robot    |
+-------------+ +-------------+
| display()   | | display()   |
+-------------+ +-------------+
```

Each box has three parts: name, attributes (`name: type`), and methods (`name(params): return type`). A solid line with a hollow triangle means *inherits from*. A dashed arrow means *has / uses*.

<a name="c5-error-lookup"></a>

## Part 5: Error lookup

Read a traceback **from the bottom up**. The last line names the error and gives the message. The `File "...", line N` line above it tells you where. Search this chapter for the error name or a word from the message.

**Python versions**

The messages below come from a recent Python. Newer versions add hints like `Did you mean: 'total'?` and `expected ':'`. On Python 3.9 the same mistakes give the same **error name** with a shorter message, often just `invalid syntax`. Match on the error name.

<a name="c5-errors-before-the-program-even-starts"></a>

### Errors before the program even starts

<a name="c5-syntaxerror-invalid-syntax-expected"></a>

#### SyntaxError: invalid syntax / expected ':'

```python
if score > 50
    print("pass")
```

```text
    if score > 50
                 ^
SyntaxError: expected ':'
```

**Causes:** missing `:` after `if`/`elif`/`else`/`for`/`while`/`def`/`class`; unclosed bracket or quote on this line **or the line above**; using `=` where `==` was meant inside a condition; a keyword spelt wrong (`esle`).

<a name="c5-indentationerror-expected-an-indented-block-unexpected-indent-unindent-does-not-match"></a>

#### IndentationError: expected an indented block / unexpected indent / unindent does not match

```python
def greet():
print("hi")
```

```text
    print("hi")
    ^
IndentationError: expected an indented block after function definition on line 1
```

**Fix:** use 4 spaces per level, consistently. In PyCharm, select the code and press `Ctrl+Alt+L` to reformat. Never mix tabs and spaces. A block needs at least one statement, so use `pass` as a placeholder.

<a name="c5-syntaxerror-unterminated-string-literal-eol-while-scanning"></a>

#### SyntaxError: unterminated string literal / EOL while scanning

A quote was opened and not closed, often because a `'` inside the text ended the string early: `'It's'`. Write `"It's"` or `'It\'s'`.

<a name="c5-name-and-type-problems"></a>

### Name and type problems

<a name="c5-nameerror-name-x-is-not-defined"></a>

#### NameError: name 'x' is not defined

```python
total = 10
print(totl)
```

**Output (error)**

```text
Traceback (most recent call last):
  File "main.py", line 2, in <module>
    ...
NameError: name 'totl' is not defined. Did you mean: 'total'?
```

**Causes:** a typo, or using a variable before it is assigned. Also: a variable created inside a function and used outside it (scope), a forgotten `import`, or a function called before the line where it is defined.

<a name="c5-typeerror-can-only-concatenate-str-not-int-to-str"></a>

#### TypeError: can only concatenate str (not "int") to str

```python
age = 37
print("Age: " + age)
```

**Output (error)**

```text
Traceback (most recent call last):
  File "main.py", line 2, in <module>
    ...
TypeError: can only concatenate str (not "int") to str
```

**Fix:** `"Age: " + str(age)`, or better an f-string `f"Age: {age}"`.

<a name="c5-typeerror-unsupported-operand-types-for-int-and-str"></a>

#### TypeError: unsupported operand type(s) for +: 'int' and 'str'

```python
apples = input("Apples? ")
print(apples + 1)
```

**Output (error)**

```text
Apples? 3 ↵
```

```text
Traceback (most recent call last):
  File "main.py", line 2, in <module>
    ...
TypeError: can only concatenate str (not "int") to str
```

`input()` gave a string. Use `int(input(...))`.

<a name="c5-typeerror-str-object-cannot-be-interpreted-as-an-integer"></a>

#### TypeError: 'str' object cannot be interpreted as an integer

```python
times = "3"
for i in range(times):
    print(i)
```

**Output (error)**

```text
Traceback (most recent call last):
  File "main.py", line 2, in <module>
    ...
TypeError: 'str' object cannot be interpreted as an integer
```

`range` needs an `int`: `range(int(times))`.

<a name="c5-typeerror-f-missing-1-required-positional-argument"></a>

#### TypeError: f() missing 1 required positional argument

```python
def climb_ladder(remaining, crossed):
    print(remaining > crossed)


climb_ladder(5)
```

**Output (error)**

```text
Traceback (most recent call last):
  File "main.py", line 5, in <module>
    ...
TypeError: climb_ladder() missing 1 required positional argument: 'crossed'
```

The function call must supply every parameter that has no default.

<a name="c5-typeerror-f-takes-0-positional-arguments-but-1-was-given"></a>

#### TypeError: f() takes 0 positional arguments but 1 was given

```python
class Robot:
    def beep():
        print("beep")


Robot().beep()
```

**Output (error)**

```text
Traceback (most recent call last):
  File "main.py", line 6, in <module>
    ...
TypeError: Robot.beep() takes 0 positional arguments but 1 was given
```

Inside a class, every normal method needs `self` as its first parameter: `def beep(self):`.

<a name="c5-typeerror-nonetype-object-is-not-subscriptable-has-no-len"></a>

#### TypeError: 'NoneType' object is not subscriptable / has no len()

```python
def directions():
    steps = ["Move Forward", "Turn Left"]
    # forgot: return steps


route = directions()
print(route[0])
```

**Output (error)**

```text
Traceback (most recent call last):
  File "main.py", line 7, in <module>
    ...
TypeError: 'NoneType' object is not subscriptable
```

The function printed or built something but didn't `return` it, so the caller received `None`.

<a name="c5-typeerror-int-object-is-not-iterable-not-callable"></a>

#### TypeError: 'int' object is not iterable / not callable

```python
count = 5
for i in count:
    print(i)
```

**Output (error)**

```text
Traceback (most recent call last):
  File "main.py", line 2, in <module>
    ...
TypeError: 'int' object is not iterable
```

Loop over `range(count)`. "Not callable" means you wrote `x()` where `x` is not a function. This often happens when a variable name hides a built-in, such as `list = [...]` and then `list(...)`, or `sum = 0` and then `sum(...)`.

<a name="c5-typeerror-not-supported-between-instances-of-str-and-int"></a>

#### TypeError: '\<' not supported between instances of 'str' and 'int'

Comparing or sorting text with numbers. Convert the strings from the CSV or `input()` first.

<a name="c5-value-problems"></a>

### Value problems

<a name="c5-valueerror-invalid-literal-for-int-with-base-10"></a>

#### ValueError: invalid literal for int() with base 10

```python
print(int("4.5"))
```

**Output (error)**

```text
Traceback (most recent call last):
  File "main.py", line 1, in <module>
    ...
ValueError: invalid literal for int() with base 10: '4.5'
```

`int()` accepts only whole-number text. Use `float("4.5")`, or `int(float("4.5"))` if you need to truncate. Empty strings fail too: `int("")`. Check `if text != "":` first.

<a name="c5-valueerror-could-not-convert-string-to-float"></a>

#### ValueError: could not convert string to float

`float("abc")` or `float("")`. Validate first, or wrap the conversion in `try`/`except ValueError`.

<a name="c5-valueerror-too-many-values-to-unpack-not-enough-values-to-unpack"></a>

#### ValueError: too many values to unpack / not enough values to unpack

```python
name, age = ("Bob", 40, "Lecturer")
```

**Output (error)**

```text
Traceback (most recent call last):
  File "main.py", line 1, in <module>
    ...
ValueError: too many values to unpack (expected 2)
```

The number of names on the left must match the number of items on the right.

<a name="c5-valueerror-listremovex-x-not-in-list"></a>

#### ValueError: list.remove(x): x not in list

`remove` crashes if the value isn't there. Check with `if x in items:` first.

<a name="c5-index-and-key-problems"></a>

### Index and key problems

<a name="c5-indexerror-list-index-out-of-range-string-index-out-of-range"></a>

#### IndexError: list index out of range / string index out of range

```python
items = ["a", "b", "c"]
print(items[3])
```

**Output (error)**

```text
Traceback (most recent call last):
  File "main.py", line 2, in <module>
    ...
IndexError: list index out of range
```

Valid indexes run from `0` to `len(items) - 1`. Usual causes: `range(len(x) + 1)`, a CSV row shorter than expected (often a blank last line), or `items[0]` on an empty list.

<a name="c5-keyerror-something"></a>

#### KeyError: 'something'

```python
stock = {"Cake": 1}
stock["Balloons"] += 1
```

**Output (error)**

```text
Traceback (most recent call last):
  File "main.py", line 2, in <module>
    ...
KeyError: 'Balloons'
```

The key doesn't exist yet. Create it first (`if key not in d: d[key] = 0`), or read safely with `d.get(key, 0)`. Also check capitalisation and stray spaces: `"Paris"` is not `"Paris "` and not `"paris"`.

<a name="c5-keyerror-on-a-set-setremove"></a>

#### KeyError on a set: `set.remove`

`my_set.remove(x)` raises `KeyError` when `x` is missing. Use `my_set.discard(x)`.

<a name="c5-attribute-problems"></a>

### Attribute problems

<a name="c5-attributeerror-list-object-has-no-attribute-add"></a>

#### AttributeError: 'list' object has no attribute 'add'

You called a method that belongs to a different type. Lists use `append`, sets use `add`, and strings have neither. The same applies to `'str' object has no attribute 'append'`.

<a name="c5-attributeerror-nonetype-object-has-no-attribute"></a>

#### AttributeError: 'NoneType' object has no attribute ...

Usually caused by `x = some_list.sort()`, which returns `None`. Use `x = sorted(some_list)`. Or a function returned nothing.

<a name="c5-attributeerror-robot-object-has-no-attribute-name"></a>

#### AttributeError: 'Robot' object has no attribute 'name'

```python
class Robot:
    def __init__(self, name):
        name = name            # forgot self.

    def show(self):
        print(self.name)


Robot("Bolt").show()
```

**Output (error)**

```text
Traceback (most recent call last):
  File "main.py", line 6, in show
    ...
AttributeError: 'Robot' object has no attribute 'name'
```

Attributes must be stored on the object with `self.name = name`.

<a name="c5-attributeerror-module-x-has-no-attribute-y"></a>

#### AttributeError: module 'x' has no attribute 'y'

A typo in the function name, or your own file has the same name as a library module (`random.py`, `csv.py`, `json.py`) and Python imported yours instead. Rename your file.

<a name="c5-file-problems"></a>

### File problems

<a name="c5-filenotfounderror-errno-2-no-such-file-or-directory"></a>

#### FileNotFoundError: \[Errno 2\] No such file or directory

```python
with open("missing.csv") as file:
    print(file.read())
```

**Output (error)**

```text
Traceback (most recent call last):
  File "main.py", line 1, in <module>
    ...
FileNotFoundError: [Errno 2] No such file or directory: 'missing.csv'
```

Check, in this order:

1.  the spelling and the extension;
2.  `print(os.getcwd())`, because relative paths start there;
3.  whether the file is in a sub-folder (`data/file.csv`).

<a name="c5-unicodedecodeerror-charmap-codec-cant-decode-byte"></a>

#### UnicodeDecodeError: 'charmap' codec can't decode byte

The file has characters your system's default encoding cannot read, which is common on Windows. Open with `open(path, encoding="utf-8")`.

<a name="c5-permissionerror"></a>

#### PermissionError

The file is open in another program (Excel locks CSVs), or you tried to open a folder as a file.

<a name="c5-maths"></a>

### Maths

<a name="c5-zerodivisionerror-division-by-zero"></a>

#### ZeroDivisionError: division by zero

```python
scores = []
print(sum(scores) / len(scores))
```

**Output (error)**

```text
Traceback (most recent call last):
  File "main.py", line 2, in <module>
    ...
ZeroDivisionError: division by zero
```

Guard the calculation: `if len(scores) > 0:`.

<a name="c5-objects-and-classes"></a>

### Objects and classes

<a name="c5-typeerror-cant-instantiate-abstract-class-x-with-abstract-methods"></a>

#### TypeError: Can't instantiate abstract class X with abstract method(s) ...

You tried to create an object directly from an abstract class, or a subclass forgot to implement one of its abstract methods. Implement every `@abstractmethod` in the subclass.

<a name="c5-typeerror-init-missing-1-required-positional-argument"></a>

#### TypeError: **init**() missing 1 required positional argument

The class's `__init__` needs arguments you didn't pass when creating the object. Pass them, or give the parameters defaults.

<a name="c5-typeerror-str-returned-non-string"></a>

#### TypeError: **str** returned non-string

`__str__` and `__repr__` must `return` a string, not `print` it.

<a name="c5-problems-with-no-error-message"></a>

### Problems with no error message

| Symptom                                         | Likely cause                                                                |
|-------------------------------------------------|-----------------------------------------------------------------------------|
| Program never ends                              | `while` condition never becomes false; you forgot `count += 1` or a `break` |
| Loop runs one time too few or too many          | `range` stop is excluded: `range(1, 10)` stops at 9                         |
| Blank lines between printed file lines          | missing `.strip()` on each line                                             |
| Output all on one line in a file                | `write()` without `"\n"`                                                    |
| A function prints nothing                       | you defined it but never called it, or you called it without `()`           |
| Value prints as `None`                          | you printed the result of a function that only prints                       |
| `if` branch never runs                          | comparing a string to a number: `"5" == 5` is `False`                       |
| Totals are text like `"1020"`                   | adding strings: convert with `int()`                                        |
| A chart window never appears                    | missing `plt.show()`                                                        |
| Chart labels overlap or are cut off             | `plt.xticks(rotation=45, ha="right")` and `plt.tight_layout()`              |
| Two charts drawn on top of each other           | call `plt.figure()` before each new chart, or `plt.close()` after `show`    |
| Changing one list changes another               | `b = a` makes two names for the same list; use `a.copy()`                   |
| Objects print as `<__main__.X object at 0x...>` | add a `__str__` or `__repr__` method                                        |

<a name="c5-debugging-routine"></a>

### Debugging routine

1.  Read the **last** line of the traceback, then the line number above it.
2.  Put `print(repr(variable), type(variable))` just before the crash. `repr` reveals hidden spaces and `\n`.
3.  Shrink the problem: copy the failing lines into `scratch.py` with hard-coded values.
4.  In PyCharm: click in the gutter to set a breakpoint, run with **Debug** (the bug icon), then step through the code with `F8`.

<a name="c6-quiz-traps-predict-the-output"></a>

## Part 6: Quiz traps: predict the output

These are the small details that "what does this print?" questions are built on. Each one was run, and the output shown is real. In the exam, if you are unsure, **paste the code into a scratch file and run it**.

<a name="c6-numbers"></a>

### Numbers

<a name="c6-always-gives-a-float-floors"></a>

#### `/` always gives a float, `//` floors

```python
print(7 / 2, 6 / 2, 7 // 2, -7 // 2, 7 % 3, -7 % 3)
```

**Output**

```text
3.5 3.0 3 -4 1 2
```

`6 / 2` is `3.0`, not `3`. `//` rounds **down**, so `-7 // 2` is `-4`.

<a name="c6-integer-vs-float-equality-and-float-rounding"></a>

#### Integer vs float equality and float rounding

```python
print(3 == 3.0, 0.1 + 0.2 == 0.3, 0.1 + 0.2, round(0.1 + 0.2, 2) == 0.3)
```

**Output**

```text
True False 0.30000000000000004 True
```

<a name="c6-int-truncates-round-rounds-and-halves-go-to-even"></a>

#### `int()` truncates, `round()` rounds, and halves go to even

```python
print(int(3.99), int(-3.99), round(3.5), round(4.5), round(2.675, 2))
```

**Output**

```text
3 -3 4 4 2.67
```

`round(2.675, 2)` gives `2.67`, not `2.68`, because the float stored for `2.675` is really `2.67499999…`. Use f-string formatting for display and don't rely on exact halves.

<a name="c6-operator-precedence"></a>

#### Operator precedence

```python
print(2 + 3 * 4, (2 + 3) * 4, 2 ** 3 ** 2, -2 ** 2, 10 - 4 - 3)
```

**Output**

```text
14 20 512 -4 3
```

`**` groups right-to-left: `2 ** 3 ** 2` is `2 ** 9`. And `-2 ** 2` is `-(2 ** 2)`.

<a name="c6-strings"></a>

### Strings

<a name="c6-and-on-strings"></a>

#### `+` and `*` on strings

```python
print("3" + "4", "3" * 4, "-" * 0 == "", len("hi " * 2))
```

**Output**

```text
34 3333 True 6
```

<a name="c6-indexes-and-slices"></a>

#### Indexes and slices

```python
s = "Python"
print(s[0], s[-1], s[1:3], s[:3], s[3:], s[-3:], s[::2], s[::-1], s[10:], s[2:2] == "")
```

**Output**

```text
P n yt Pyt hon hon Pto nohtyP  True
```

Slices never crash on out-of-range numbers, but a single index does (`s[10]` is an `IndexError`).

<a name="c6-strings-are-immutable"></a>

#### Strings are immutable

```python
s = "cat"
s[0] = "b"
```

**Output (error)**

```text
Traceback (most recent call last):
  File "main.py", line 2, in <module>
    ...
TypeError: 'str' object does not support item assignment
```

Build a new string instead: `s = "b" + s[1:]`.

<a name="c6-methods-return-new-strings"></a>

#### Methods return new strings

```python
name = "  ada  "
name.strip()
print(f"[{name}]")
name = name.strip().title()
print(f"[{name}]")
```

**Output**

```text
[  ada  ]
[Ada]
```

<a name="c6-stripchars-removes-any-of-those-characters-from-both-ends"></a>

#### `strip(chars)` removes any of those characters from both ends

```python
line = ",this is some sample text"
print(line.strip(","))
print(line.strip(",t"))
```

**Output**

```text
this is some sample text
his is some sample tex
```

The second result loses the **final** `t` as well. `strip` works on both ends and treats its argument as a set of characters, not a word.

<a name="c6-comparing-strings"></a>

#### Comparing strings

```python
print("apple" < "banana", "Zebra" < "apple", "10" < "9", "a" == "A")
```

**Output**

```text
True True True False
```

Strings compare character by character using character codes. Uppercase letters come before lowercase ones, and `"10" < "9"` because `"1"` comes before `"9"`.

<a name="c6-booleans-and-conditions"></a>

### Booleans and conditions

<a name="c6-and-or-return-one-of-their-operands"></a>

#### `and` / `or` return one of their operands

```python
print(True and False, True or False, not True)
print(0 or "default", "" or "empty", 5 and 7, 0 and 7)
```

**Output**

```text
False True False
default empty 7 0
```

<a name="c6-the-or-trap"></a>

#### The `or` trap

```python
colour = "green"
if colour == "red" or "blue":
    print("matched?!")
print(bool("blue"))
```

**Output**

```text
matched?!
True
```

<a name="c6-truthy-and-falsy-values"></a>

#### Truthy and falsy values

```python
for value in [0, 1, -1, "", " ", "0", [], [0], {}, None]:
    print(repr(value), bool(value))
```

**Output**

```text
0 False
1 True
-1 True
'' False
' ' True
'0' True
[] False
[0] True
{} False
None False
```

<a name="c6-chained-comparisons"></a>

#### Chained comparisons

```python
x = 5
print(1 < x < 10, 1 < x > 3, 10 > x > 7)
```

**Output**

```text
True True False
```

<a name="c6-if-elif-stops-at-the-first-true-branch"></a>

#### `if` / `elif` stops at the first true branch

```python
age = 70
if age < 18:
    print("child")
elif age < 65:
    print("adult")
else:
    print("elderly")

# versus two separate ifs: both can run
if age > 10:
    print("over 10")
if age > 60:
    print("over 60")
```

**Output**

```text
elderly
over 10
over 60
```

<a name="c6-loops-and-range"></a>

### Loops and range

<a name="c6-range-excludes-the-stop-value"></a>

#### `range` excludes the stop value

```python
print(list(range(5)), list(range(2, 5)), list(range(10, 0, -3)), list(range(5, 2)))
```

**Output**

```text
[0, 1, 2, 3, 4] [2, 3, 4] [10, 7, 4, 1] []
```

`range(5, 2)` is **empty** because counting down needs a negative step.

<a name="c6-how-many-times-does-it-run"></a>

#### How many times does it run?

```python
count = 0
for i in range(3, 12, 3):
    count += 1
print(count, i)

n = 10
while n > 0:
    n -= 3
print(n)
```

**Output**

```text
3 9
-2
```

<a name="c6-the-loop-variable-keeps-its-last-value"></a>

#### The loop variable keeps its last value

```python
for i in range(4):
    pass
print(i)
```

**Output**

```text
3
```

<a name="c6-nested-loop-counts-multiply"></a>

#### Nested loop counts multiply

```python
total = 0
for a in range(3):
    for b in range(4):
        total += 1
print(total)
```

**Output**

```text
12
```

<a name="c6-break-only-exits-the-innermost-loop"></a>

#### `break` only exits the innermost loop

```python
for a in range(3):
    for b in range(3):
        if b == 1:
            break
        print(a, b)
```

**Output**

```text
0 0
1 0
2 0
```

<a name="c6-print-end"></a>

#### `print(..., end="")`

```python
for i in range(3):
    print(i, end=" ")
print("|")
for i in range(3):
    print(i, end="")
print()
```

**Output**

```text
0 1 2 |
012
```

<a name="c6-lists-tuples-sets-dicts"></a>

### Lists, tuples, sets, dicts

<a name="c6-two-names-one-list-aliasing"></a>

#### Two names, one list (aliasing)

```python
a = [1, 2]
b = a
b.append(3)
c = a.copy()
c.append(4)
print(a, b, c, a is b, a == b)
```

**Output**

```text
[1, 2, 3] [1, 2, 3] [1, 2, 3, 4] True True
```

<a name="c6-sort-returns-none"></a>

#### `sort()` returns None

```python
nums = [3, 1, 2]
result = nums.sort()
print(result, nums)
```

**Output**

```text
None [1, 2, 3]
```

<a name="c6-append-vs-extend-vs"></a>

#### `append` vs `extend` vs `+`

```python
a = [1, 2]
a.append([3, 4])
b = [1, 2]
b.extend([3, 4])
print(a, b, len(a), len(b), [1] + [2, 3])
```

**Output**

```text
[1, 2, [3, 4]] [1, 2, 3, 4] 3 4 [1, 2, 3]
```

<a name="c6-remove-takes-a-value-pop-and-del-take-an-index"></a>

#### `remove` takes a value, `pop` and `del` take an index

```python
x = [10, 20, 30, 20]
x.remove(20)        # first 20 only
print(x)
print(x.pop(0), x)
```

**Output**

```text
[10, 30, 20]
10 [30, 20]
```

<a name="c6-tuple-with-one-item"></a>

#### Tuple with one item

```python
print(type((5)), type((5,)), len(("ab",)), len(("ab")))
```

**Output**

```text
<class 'int'> <class 'tuple'> 1 2
```

<a name="c6-sets-drop-duplicates-and-have-no-order"></a>

#### Sets drop duplicates and have no order

```python
s = {3, 1, 3, 2, 1}
print(len(s), sorted(s), 3 in s)
print(type({}), type(set()))
```

**Output**

```text
3 [1, 2, 3] True
<class 'dict'> <class 'set'>
```

<a name="c6-dictionary-keys-are-unique"></a>

#### Dictionary keys are unique

```python
d = {"a": 1, "b": 2, "a": 3}
print(d, len(d))
d["c"] = d.get("c", 0) + 1
print(d)
```

**Output**

```text
{'a': 3, 'b': 2} 2
{'a': 3, 'b': 2, 'c': 1}
```

<a name="c6-looping-over-a-dict-gives-keys"></a>

#### Looping over a dict gives keys

```python
d = {"x": 10, "y": 20}
for k in d:
    print(k, end=" ")
print()
print(list(d.items()))
```

**Output**

```text
x y 
[('x', 10), ('y', 20)]
```

<a name="c6-in-on-a-dict-checks-keys-not-values"></a>

#### `in` on a dict checks keys, not values

```python
d = {"x": 10}
print("x" in d, 10 in d, 10 in d.values())
```

**Output**

```text
True False True
```

<a name="c6-functions"></a>

### Functions

<a name="c6-a-function-without-return-gives-none"></a>

#### A function without `return` gives `None`

```python
def greet(name):
    print("Hi", name)


result = greet("Ada")
print(result)
```

**Output**

```text
Hi Ada
None
```

<a name="c6-code-after-return-never-runs"></a>

#### Code after `return` never runs

```python
def f():
    return 1
    print("never")


print(f())
```

**Output**

```text
1
```

<a name="c6-local-variables-do-not-leak-out"></a>

#### Local variables do not leak out

```python
def set_total():
    total = 99


set_total()
print(total)
```

**Output (error)**

```text
Traceback (most recent call last):
  File "main.py", line 6, in <module>
    ...
NameError: name 'total' is not defined
```

<a name="c6-changing-a-list-inside-a-function-changes-the-callers-list"></a>

#### Changing a list inside a function changes the caller's list

```python
def add_item(items):
    items.append("new")


def replace(items):
    items = ["replaced"]          # rebinds the local name only


shopping = ["milk"]
add_item(shopping)
replace(shopping)
print(shopping)
```

**Output**

```text
['milk', 'new']
```

<a name="c6-default-arguments"></a>

#### Default arguments

```python
def power(base, exponent=2):
    return base ** exponent


print(power(3), power(3, 3), power(exponent=0, base=9))
```

**Output**

```text
9 27 1
```

<a name="c6-classes"></a>

### Classes

<a name="c6-class-attribute-vs-instance-attribute"></a>

#### Class attribute vs instance attribute

```python
class Counter:
    total = 0

    def __init__(self):
        Counter.total += 1
        self.id = Counter.total


a = Counter()
b = Counter()
print(a.id, b.id, Counter.total, a.total)
```

**Output**

```text
1 2 2 2
```

<a name="c6-printobj-without-str-"></a>

#### `print(obj)` without `__str__`

```python
class Plain:
    pass


text = str(Plain())
print(text.startswith("<__main__.Plain object at"))
```

**Output**

```text
True
```

<a name="c6-which-method-runs-overriding"></a>

#### Which method runs? (overriding)

```python
class Animal:
    def speak(self):
        return "..."

    def intro(self):
        return "I say " + self.speak()


class Dog(Animal):
    def speak(self):
        return "Woof"


print(Animal().intro(), Dog().intro())
```

**Output**

```text
I say ... I say Woof
```

`intro` is inherited, but `self.speak()` calls the **object's own** version. That is why a `Dog` says Woof.

<a name="c7-week-by-week-cheat-sheets"></a>

## Part 7: Week-by-week cheat sheets

One compact card per teaching week, matching the SOL topic names, so you can map a question back to what was taught.

<a name="c7-week-1-python-git-output-and-input"></a>

### Week 1: Python, Git, output and input

- **Profession:** follow PEP-8; know the Data Protection Act 2018, Computer Misuse Act 1990 and Freedom of Information Act 2000.
- **Tools:** Python, Git, PyCharm (also on Learning on Demand), GitHub (private repo).
- **Git cycle:** `git status` → `git add .` → `git commit -m "message"` → `git push`.
- **Output:** `print()`; comments with `#`; escape characters `\n \t \\ \" \'`; ASCII art.
- **Input:** `name = input()`. The value is **always a string**.
- **Types:** `str`, `int`, `float`; convert with `str()`, `int()`, `float()`.
- **f-strings:** `f"Hello {name}"`, `f"{bmi:.2f}"`.
- **String operators:** `+` joins, `*` repeats (`"♥" * lives`).

**Common mistake**

BMI = weight ÷ height². Write `weight / height ** 2`. `weight / height * 2` is wrong because `/` and `*` are evaluated left to right.

<a name="c7-week-2-decisions"></a>

### Week 2: Decisions

- `if` / `elif` / `else`, with a colon and an indented block.
- Comparisons: `== != < > <= >=`. Remember `=` assigns and `==` compares.
- Modulo `%` gives the remainder; `n % 2 == 0` tests for even.
- Nested decisions: an `if` inside an `if` when the second question depends on the first answer.
- Logical operators: `and` (both true), `or` (at least one true), `not` (flips one value).
- Mutually exclusive choices: use `elif`, not a chain of separate `if`s.

<a name="c7-week-3-loops"></a>

### Week 3: Loops

- `while condition:` repeats an unknown number of times. A control variable must change inside the loop or it never ends.
- `for x in range(start, stop, step):` repeats a known number of times. `stop` is **excluded**.
- Count down: `range(n, 0, -1)`.
- `len(s)` gives the length. Indexes run from `0` to `len(s) - 1`.
- `for ch in word:` visits each character. `in` / `not in` test membership.
- Nested loops: the inner loop runs completely for each pass of the outer loop.
- `print(x, end="")` stays on the same line.
- Patterns: **counter** (`count += 1`), **accumulator** (`total += n`), **sentinel** (loop until a stop word).

<a name="c7-week-4-functions-and-modules"></a>

### Week 4: Functions and modules

- Built-ins: `len`, `ord`, `chr`, `abs`, `int`, `float`, `str`, `range`, `min`, `max`, `sum`, `round`, `sorted`, `type`, `isinstance`.
- `def name(params):` defines a function; `name(args)` calls it. Defining it doesn't run it.
- **Parameters** are the names in the `def` line; **arguments** are the values you pass in the call.
- `return` sends a value back; without it the function returns `None`.
- Functions can call other functions; a `run()` function often controls the whole program.
- Modules: `import random`, `import random as rnd`, `from random import randrange`.
- Your own modules: `import tui` loads `tui.py` from the same folder.
- `if __name__ == "__main__":` runs code only when the file is run directly.

<a name="c7-week-5-ordered-data-structures"></a>

### Week 5: Ordered data structures

- **list** `[]`: ordered, mutable, allows duplicates and mixed types. Methods: `append`, `insert`, `remove`, `pop`, `sort`, `reverse`, `index`, `count`, `extend`.
- **tuple** `()`: ordered, **immutable**. Good for fixed records and returning several values.
- Index `[0]`, negative index `[-1]`, slice `[a:b]`.
- Iterate with `for item in items:` or `for i in range(len(items)):`.
- Nesting: a list of tuples such as `[("step 1", 50), ...]`. Read with `item[0]`, `item[1]`.
- `min`, `max`, `sum`, `len`, `in` all work on lists and tuples.

<a name="c7-week-6-files"></a>

### Week 6: Files

- Paths: absolute (from the root) vs relative (from the current working directory); `.` is this folder, `..` the parent.
- `import os`: `os.getcwd()`, `os.listdir(path)`.
- `open(path, mode)` with modes `r`, `w`, `a`, `x` (+ `b` for binary). Always close the file, or use `with` to close it automatically.
- Reading: `read()`, `read(n)`, `readline()`, `for line in file:`. Use `.strip()` to remove `\n`.
- Writing: `write(text)`, which adds no newline for you.
- CSV: `import csv`; `csv.reader(file)`; `next(reader)` reads the heading row; every value is a string.
- Exporting CSV: write comma-separated text, or use `csv.writer`.

<a name="c7-week-7-sets-dictionaries-json"></a>

### Week 7: Sets, dictionaries, JSON

- **set** `{}` / `set()`: unordered, unique items, no indexing. `add`, `remove`, `discard`, `|`, `&`, `-`. `sorted(s)` returns a list.
- **dict** `{key: value}`: unique keys. `d[k] = v`, `d[k]`, `d.get(k, default)`, `k in d`, `d.keys()`, `d.values()`, `d.items()`, `d.pop(k)`.
- Dictionaries keep insertion order (Python 3.7+).
- Nested dicts: `{"items": {"Cake": 1}, "people": {"guests": 30}}`.
- JSON: `json.load(file)` reads, `json.dump(data, file, indent=4)` writes, `json.loads` / `json.dumps` work with strings.
- Patterns: count with a dict; build a set of distinct values; group by key.

<a name="c7-week-8-third-party-libraries-matplotlib"></a>

### Week 8: Third-party libraries (matplotlib)

- `import matplotlib.pyplot as plt`.
- `plt.plot(x, y, "ro--")` draws a line or markers; `plt.bar(labels, values)`; `plt.pie(sizes, labels=labels)`; `plt.step(x, y)`.
- Labels: `plt.title`, `plt.xlabel`, `plt.ylabel`, `plt.legend` (needs `label=` in the plot call).
- `plt.show()` displays the chart. Nothing appears without it.
- `random.sample(range(n), k)` gives k different random values for test data.
- Famous visualisations from the reading: Minard (Napoleon's march), John Snow (cholera map), Florence Nightingale (rose diagram).

<a name="c7-week-9-object-oriented-programming"></a>

### Week 9: Object-oriented programming

- A **class** is a blueprint; an **object** (instance) is one thing built from it.
- `__init__(self, ...)` is the initialiser and sets attributes with `self.x = ...`.
- **Class attribute:** shared by all objects (`MAX_ENERGY = 100`). **Instance attribute:** one per object (`self.name`).
- **Instance method:** `def m(self):`. **Static method:** `@staticmethod`, no `self`. **Class method:** `@classmethod`, gets `cls`, often used to create objects.
- Magic methods: `__str__` (informal, used by `print`), `__repr__` (formal, used by `repr()` and in lists).
- Composition: a `Planet` holds a list of `Human`/`Robot` objects; a `Universe` holds planets.
- Objects can be stored in lists and dicts and plotted with matplotlib like any other data.

<a name="c7-week-10-inheritance-and-abstraction"></a>

### Week 10: Inheritance and abstraction

- **Class diagram:** each box shows name, attributes and methods. A solid arrow means *is / extends*; a dashed arrow means *has / uses*.
- Inheritance: `class Human(Inhabitant):`. Shared attributes and methods move up into the parent.
- `super().__init__(...)` runs the parent's initialiser.
- Overriding: a child defines a method with the same name as the parent's.
- `isinstance(obj, Human)` tells you which type an object is.
- Abstract class: `from abc import ABC, abstractmethod`; `class Tech(ABC):`. You cannot create an object of it directly.
- Abstract method: `@abstractmethod`, and every concrete subclass must implement it.

<a name="c7-week-11-case-studies"></a>

### Week 11: Case studies

- **Titanic:** load a CSV into a global list, show a numbered menu, then one function per option (names, survivors, per gender, per age group, survivors per age group).
- **Olympics:** three modules. `tui` handles input and output (`started`, `completed`, `error`, `menu`, display functions), `process` does the calculations (`list_years`, `tally_medals`, `tally_team_medals`), and `main` controls the flow (`read_data`, `run` loop).
- Lessons: separate the user interface from the processing; one function, one job; pass data in as parameters and get results back with `return`.

<a name="c7-week-12-assessment-support"></a>

### Week 12: Assessment support

No new teaching content. Use this week for questions and feedback on your coursework.

<a name="c8-lookup-tables"></a>

## Part 8: Lookup tables

<a name="c8-built-in-functions-you-are-likely-to-need"></a>

### Built-in functions you are likely to need

| Function                                             | Does                                  | Example → result                    |
|------------------------------------------------------|---------------------------------------|-------------------------------------|
| `print(*items, sep=" ", end="\n")`                   | show text                             |                                     |
| `input(prompt)`                                      | read a line as `str`                  |                                     |
| `len(x)`                                             | number of items or characters         | `len("abc")` → `3`                  |
| `int(x)`, `float(x)`, `str(x)`, `bool(x)`            | convert                               | `int("7")` → `7`                    |
| `list(x)`, `tuple(x)`, `set(x)`, `dict(pairs)`       | convert collections                   | `list("ab")` → `['a', 'b']`         |
| `range(start, stop, step)`                           | number sequence, stop excluded        | `list(range(3))` → `[0, 1, 2]`      |
| `sum(x)`, `min(x)`, `max(x)`                         | totals and extremes                   | `max([3, 9, 2])` → `9`              |
| `sorted(x, key=..., reverse=...)`                    | **new** sorted list                   | `sorted({3, 1})` → `[1, 3]`         |
| `reversed(x)`                                        | reversed iterator                     | `list(reversed([1, 2]))` → `[2, 1]` |
| `enumerate(x, start=0)`                              | (index, item) pairs                   |                                     |
| `zip(a, b)`                                          | pairs items from both                 |                                     |
| `abs(x)`, `round(x, n)`, `pow(a, b)`, `divmod(a, b)` | maths                                 | `divmod(7, 2)` → `(3, 1)`           |
| `ord(ch)`, `chr(n)`                                  | character ↔ code                      | `ord("a")` → `97`                   |
| `type(x)`, `isinstance(x, T)`                        | type checks                           | `isinstance(3, int)` → `True`       |
| `open(path, mode)`                                   | open a file                           |                                     |
| `repr(x)`                                            | formal text form (shows quotes, `\n`) | `repr("a\n")` → `'a\n'`             |
| `help(x)`, `dir(x)`                                  | documentation, list of methods        | `dir(str)`                          |

<a name="c8-string-methods"></a>

### String methods

All of them return a **new** value. The original string is never changed.

| Method                                                                              | Result for `s = " Hello World "` (or as stated)       |
|-------------------------------------------------------------------------------------|-------------------------------------------------------|
| `s.strip()` / `lstrip()` / `rstrip()`                                               | `"Hello World"` / `"Hello World "` / `" Hello World"` |
| `s.strip(chars)`                                                                    | removes any of `chars` from both ends                 |
| `s.lower()` / `upper()` / `title()` / `capitalize()` / `swapcase()`                 | case changes                                          |
| `s.split()`                                                                         | `['Hello', 'World']` (on any whitespace)              |
| `"a,b".split(",")`                                                                  | `['a', 'b']`                                          |
| `"-".join(["a", "b"])`                                                              | `"a-b"`                                               |
| `s.replace(old, new)`                                                               | every match replaced                                  |
| `s.find(sub)` / `s.index(sub)`                                                      | position, or `-1` / error if missing                  |
| `s.count(sub)`                                                                      | number of occurrences                                 |
| `s.startswith(x)` / `endswith(x)`                                                   | `True` / `False`                                      |
| `s.isdigit()` / `isalpha()` / `isalnum()` / `isspace()` / `isupper()` / `islower()` | content tests                                         |
| `s.splitlines()`                                                                    | lines without the `\n`                                |
| `s.center(n)` / `ljust(n)` / `rjust(n)` / `zfill(n)`                                | pad to width n                                        |

<a name="c8-list-methods"></a>

### List methods

| Method                         | Effect                                  | Returns          |
|--------------------------------|-----------------------------------------|------------------|
| `a.append(x)`                  | add `x` at the end                      | `None`           |
| `a.extend(seq)`                | add every item of `seq`                 | `None`           |
| `a.insert(i, x)`               | put `x` at index `i`                    | `None`           |
| `a.remove(x)`                  | delete the first `x` (error if missing) | `None`           |
| `a.pop()` / `a.pop(i)`         | delete the last item / the item at `i`  | the removed item |
| `a.clear()`                    | empty the list                          | `None`           |
| `a.index(x)`                   | position of the first `x`               | `int`            |
| `a.count(x)`                   | how many `x`                            | `int`            |
| `a.sort(key=..., reverse=...)` | sort **in place**                       | `None`           |
| `a.reverse()`                  | reverse **in place**                    | `None`           |
| `a.copy()`                     | shallow copy                            | new list         |
| `del a[i]`, `del a[i:j]`       | delete by index or slice                |                  |

<a name="c8-dictionary-methods"></a>

### Dictionary methods

| Method / syntax                               | Effect                                             |
|-----------------------------------------------|----------------------------------------------------|
| `d[k]`                                        | value for `k`; `KeyError` if missing               |
| `d.get(k)` / `d.get(k, default)`              | value, or `None` / `default` if missing            |
| `d[k] = v`                                    | add or replace                                     |
| `k in d`                                      | is `k` a **key**?                                  |
| `d.keys()`, `d.values()`, `d.items()`         | views to loop over; wrap in `list()` to get a list |
| `d.pop(k)`                                    | remove `k`, return its value                       |
| `d.popitem()`                                 | remove the last inserted pair                      |
| `d.update(other)`                             | merge in another dict                              |
| `d.setdefault(k, default)`                    | get `k`, inserting `default` first if missing      |
| `d.copy()`, `d.clear()`, `len(d)`, `del d[k]` |                                                    |

<a name="c8-set-methods"></a>

### Set methods

| Method                              | Operator            | Meaning                              |
|-------------------------------------|---------------------|--------------------------------------|
| `s.add(x)`                          |                     | add one item                         |
| `s.remove(x)` / `s.discard(x)`      |                     | delete (error / no error if missing) |
| `s.union(t)`                        | `s | t`             | everything in either                 |
| `s.intersection(t)`                 | `s & t`             | in both                              |
| `s.difference(t)`                   | `s - t`             | in `s` but not `t`                   |
| `s.symmetric_difference(t)`         | `s ^ t`             | in exactly one                       |
| `s.issubset(t)` / `s.issuperset(t)` | `s <= t` / `s >= t` | containment                          |

<a name="c8-f-string-format-specification"></a>

### f-string format specification

The pattern is `{value:[fill][align][width][,][.precision][type]}`.

| Spec                              | Value        | Output                                 |
|-----------------------------------|--------------|----------------------------------------|
| `{x:.2f}`                         | `3.14159`    | `3.14`                                 |
| `{x:8.2f}`                        | `3.14159`    | `3.14`                                 |
| `{x:,}`                           | `1234567`    | `1,234,567`                            |
| `{x:,.2f}`                        | `1234.5`     | `1,234.50`                             |
| `{x:.0%}`                         | `0.25`       | `25%`                                  |
| `{x:<10}` / `{x:>10}` / `{x:^10}` | `"hi"`       | left / right / centre in 10 characters |
| `{x:*^10}`                        | `"hi"`       | `****hi****`                           |
| `{x:03}` / `{x:05.1f}`            | `7` / `3.14` | `007` / `003.1`                        |
| `{x!r}`                           | `"hi"`       | `'hi'` (repr)                          |
| `{x:e}`                           | `12345.678`  | `1.234568e+04`                         |

`format(3.14159, ".2f")` and `"{:.2f}".format(x)` use the same specification language.

<a name="c8-printable-ascii-codes-32126"></a>

### Printable ASCII codes (32–126)

| Range   | Characters                      |
|---------|---------------------------------|
| 32      | space                           |
| 33–47   | `! " # $ % & ' ( ) * + , - . /` |
| 48–57   | `0`–`9`                         |
| 58–64   | `: ; < = > ? @`                 |
| 65–90   | `A`–`Z`                         |
| 91–96   | `` [ \ ] ^ _ ` ``               |
| 97–122  | `a`–`z`                         |
| 123–126 | `{ | } ~`                       |

Useful facts: `ord("A")` is 65 and `ord("a")` is 97, so a letter's lowercase code is its uppercase code + 32. `ord("0")` is 48.

<a name="c8-python-keywords"></a>

### Python keywords

`False None True and as assert break class continue def del elif else except finally for from global if import in is lambda nonlocal not or pass raise return try while with yield`

You cannot use these as variable names. Built-in names like `list`, `sum`, `max`, `input` and `type` *can* be reassigned, but doing so breaks the built-in for the rest of the program.

<a name="c8-comparison-of-collection-types"></a>

### Comparison of collection types

|              | list              | tuple                                | set                       | dict                                |
|--------------|-------------------|--------------------------------------|---------------------------|-------------------------------------|
| Brackets     | `[1, 2]`          | `(1, 2)`                             | `{1, 2}`                  | `{"a": 1}`                          |
| Empty        | `[]`              | `()`                                 | `set()`                   | `{}`                                |
| Ordered      | yes               | yes                                  | no                        | yes (insertion)                     |
| Changeable   | yes               | **no**                               | yes                       | yes                                 |
| Duplicates   | yes               | yes                                  | **no**                    | keys no, values yes                 |
| Index access | `x[0]`            | `x[0]`                               | no                        | `x[key]`                            |
| Typical use  | sequence of items | fixed record / several return values | unique values, membership | look up by name, counting, grouping |

<a name="c9-corrections-to-the-course-materials"></a>

## Part 9: Corrections to the course materials

The SOL pages contain a few mistakes. If an exam question is written the same way, the correct Python behaviour below is what actually happens when you run it.

<a name="c9-week-13"></a>

### Week 1–3

| Where                                         | What the page says                                                                   | What is actually true                                                                                   |
|-----------------------------------------------|--------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------|
| Week 2, *Multiple Conditions*                 | "In the case of the not operator only one of the expressions must evaluate to True." | `not` takes **one** value and flips it: `not True` is `False`. It does not combine two expressions.     |
| Week 3, *For Loops*, Activity 4 sample output | `index 4: 0`                                                                         | It should be the letter `o` (from `"Hello"`).                                                           |
| Week 3, *Nested Loops*                        | First single-loop example "repeated 3 times"                                         | A single loop prints `0 |1 |…|9 |` **once**. The repetition only happens after the outer loop is added. |

<a name="c9-week-45"></a>

### Week 4–5

| Where                                           | What the page says                                             | What is actually true                                                                                                                                          |
|-------------------------------------------------|----------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Week 4, *Built-in Functions*, Activity 2 sample | "The character represented by the ASCII code **155** is: m"    | `chr(109)` is `m`. The sample's input is 109, so the 155 is a typo. 155 is outside the printable range.                                                        |
| Week 4, Activity 2 text                         | "Otherwise, if the number is within the range…"                | It should read "**not** within the range" for the error branch.                                                                                                |
| Week 5, list table                              | `cmp(list1, list2)`                                            | `cmp` **does not exist in Python 3**. Compare with `==`, `<`, etc.                                                                                             |
| Week 5, list table                              | `list.pop(el)` "removes the last occurrence of the element el" | `pop(i)` takes an **index** and removes and returns the item at that position. To remove by value use `remove(value)`, which removes the **first** occurrence. |
| Week 5, list table                              | `list.sort(key = lambda x)` "using a lambda function named x"  | The lambda needs a body: `key=lambda x: x[1]`. Here `x` is the parameter name, not the function's name.                                                        |
| Week 5, *Tuples*                                | `min(temperature)`                                             | The variable is called `temperatures`, so as written this is a `NameError`.                                                                                    |

<a name="c9-week-6"></a>

### Week 6

| Where                         | What the page says                                                          | What is actually true                                                                                                   |
|-------------------------------|-----------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------|
| *Data Files*, paths           | "The absolute path to the root folder is `data`" and `data/staff/prins.txt` | An absolute path starts at the file-system root: `/data/staff/prins.txt`. Without the leading `/` it is relative.       |
| *Text Files*, `strip` example | `",this is some sample text".strip(",t")` gives `"his is some sample text"` | It gives `"his is some sample tex"`. `strip` removes matching characters from **both** ends, so the final `t` goes too. |
| *CSV Files*, Activity 3       | write `"{item_id},{item_name},{item_colour}"` in append mode                | Without a `"\n"` the new rows run together on one line. Also make sure the existing file ends with a newline.           |

```python
print(",this is some sample text".strip(",t"))
```

**Output**

```text
his is some sample tex
```

<a name="c9-week-78"></a>

### Week 7–8

| Where                        | What the page says                                         | What is actually true                                                                                                   |
|------------------------------|------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------|
| *Sets*, table                | `s.issubeset(t)`                                           | Spelt `issubset`.                                                                                                       |
| *Dictionaries* intro         | "A dictionary is a dynamic, unordered…"                    | Since Python 3.7 dictionaries **keep insertion order** (the page notes this just above).                                |
| *Dictionaries*               | `keys()` "returns a list"                                  | It returns a *view*; use `list(d.keys())` if you need a real list.                                                      |
| *JSON Files*, Activity 2     | "provide the method dump with the file path"               | `json.dump(data, file_object)` takes an **open file object**, not a path.                                               |
| Week 8, *Data Visualisation* | "`plt.bar` – This function is used to create a histogram." | `plt.bar` draws a **bar chart** of values you supply. A histogram (bins counting how often values occur) is `plt.hist`. |
| Week 8, Activity 2           | "blue solid line with pentagon markers"                    | The pentagon marker code is `p`, so the format string is `"bp-"`.                                                       |

<a name="c9-week-910"></a>

### Week 9–10

| Where                         | What the page says                                       | What is actually true                                                                                                                                                  |
|-------------------------------|----------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Week 9, *Objects and Classes* | Class methods "require an instance of the class"         | A class method receives the **class** (`cls`) and is usually called on the class itself: `Robot.assemble()`. Static methods receive neither the class nor an instance. |
| Week 9                        | "A class is stored in its own file … lowercase filename" | That's a convention, not a rule. Python allows several classes per file.                                                                                               |
| Week 10, Activity 4           | `class Tech:` with `@abstractmethod def activate():`     | Must be `class Tech(ABC):` for the abstract rule to be enforced, and methods need `self`.                                                                              |

<a name="c9-week-11-case-studies"></a>

### Week 11 case studies

| Where                                | What the page says                                               | What is actually true                                                                                                                                        |
|--------------------------------------|------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Titanic, Activity 6                  | `if age < 18 … if age < 65 … otherwise elderly`                  | The second test must be `elif`. With two separate `if`s a child is counted as a child **and** an adult. The expected output (113 / 590 / 11) assumes `elif`. |
| Titanic, Activity 6                  | "retrieve the value corresponding to the age"                    | Ages include decimals such as `0.42` and `14.5`. Convert with `float()`. `int("0.42")` crashes.                                                              |
| Titanic, Activity 1                  | read "the first line… for each remaining line"                   | Passenger names contain commas (`"Braund, Mr. Owen Harris"`). Use `csv.reader`, never `line.split(",")`.                                                     |
| Titanic, Activity 3 sample           | prints "You have selected option: 1" **before** the user's input | The real order is the menu, then the user's input, then the confirmation.                                                                                    |
| Olympics, `display_team_medal_tally` | heading shows `def display_medal_tally(team_tally):`             | The function's name is `display_team_medal_tally`.                                                                                                           |
| Olympics                             | `{"United Kingdom", {"Gold": 10, ...}}`                          | The comma makes this a **set**. A dict needs a colon: `{"United Kingdom": {"Gold": 10, ...}}`.                                                               |
| Olympics, data                       | Medal column contains `"NA"`                                     | Only count `"Gold"`, `"Silver"` and `"Bronze"`; skip `"NA"`.                                                                                                 |
| Olympics                             | athletes appear once per event                                   | A team medal won by 5 people appears as 5 rows, which is why the medal totals look large.                                                                    |

<a name="c10-git-pycharm-and-pep-8-quick-reference"></a>

## Part 10: Git, PyCharm and PEP-8 quick reference

<a name="c10-git-commands"></a>

### Git commands

| Command                                 | Does                                                                   |
|-----------------------------------------|------------------------------------------------------------------------|
| `git clone <url>`                       | copy a GitHub repository to your machine (once)                        |
| `git status`                            | what changed / what is staged                                          |
| `git add .`                             | stage every change in this folder                                      |
| `git add file.py`                       | stage one file                                                         |
| `git commit -m "Add menu loop to main"` | save a snapshot with a message                                         |
| `git push`                              | send your commits to GitHub                                            |
| `git pull`                              | fetch and merge changes from GitHub (e.g. after working on another PC) |
| `git log --oneline`                     | list commits, newest first                                             |
| `git diff`                              | show unstaged changes line by line                                     |
| `git restore file.py`                   | throw away uncommitted changes to a file                               |

**The cycle:** edit → run and test → `git add .` → `git commit -m "..."` → `git push` (at least at the end of each session).

**Good commit messages** say *what* changed and why, in the imperative mood: `Add function to count passengers by gender`, `Fix off-by-one in countdown loop`. Avoid `update`, `stuff`, `final2`.

`.gitignore` lists what Git should skip. Add `.idea/` (PyCharm settings) and `__pycache__/`.

**Private repository**

The module requires your GitHub repository to be **private**. Check this under *Settings → General → Danger Zone → Change visibility*.

<a name="c10-pycharm"></a>

### PyCharm

| Action                           | Windows / Linux                    | macOS           |
|----------------------------------|------------------------------------|-----------------|
| Run current file                 | `Shift+F10` (or right-click → Run) | `Ctrl+R`        |
| Debug                            | `Shift+F9`                         | `Ctrl+D`        |
| Step over / into (debugger)      | `F8` / `F7`                        | `F8` / `F7`     |
| Reformat code (fixes most PEP-8) | `Ctrl+Alt+L`                       | `Cmd+Opt+L`     |
| Comment / uncomment lines        | `Ctrl+/`                           | `Cmd+/`         |
| Search everywhere                | `Shift` `Shift`                    | `Shift` `Shift` |
| Rename a variable everywhere     | `Shift+F6`                         | `Shift+F6`      |
| Show problems (PEP-8 and errors) | `Alt+6`                            | `Cmd+6`         |
| Open the terminal                | `Alt+F12`                          | `Opt+F12`       |
| Duplicate line                   | `Ctrl+D`                           | `Cmd+D`         |

The **Problems** tool window and the coloured marks in the right-hand gutter show PEP-8 warnings. A green tick in the top-right of the editor means no issues in that file.

<a name="c10-pep-8-essentials"></a>

### PEP-8 essentials

| Rule                                                 | Good                             | Bad                         |
|------------------------------------------------------|----------------------------------|-----------------------------|
| Indent 4 spaces                                      | `····print(x)`                   | tabs, 2 spaces              |
| Variable / function names: `snake_case`              | `total_score`, `load_data()`     | `TotalScore`, `loaddata()`  |
| Class names: `CapWords`                              | `class Inhabitant:`              | `class inhabitant:`         |
| Constants: `UPPER_CASE`                              | `MAX_ENERGY = 100`               | `maxEnergy = 100`           |
| Spaces around operators                              | `x = a + b`                      | `x=a+b`                     |
| No spaces inside brackets                            | `print(x)`                       | `print( x )`                |
| Space after a comma                                  | `f(a, b)`                        | `f(a,b)`                    |
| No spaces around `=` for keyword arguments           | `f(sep="-")`                     | `f(sep = "-")`              |
| 2 blank lines around top-level functions and classes |                                  |                             |
| 1 blank line between methods inside a class          |                                  |                             |
| Imports at the top, one per line                     | `import csv` then `import json`  | `import csv, json` mid-file |
| Line length ≤ 79 characters (PyCharm default 120)    | split long lines inside brackets |                             |
| Comments: `#` then a space, explain *why*            | `# skip the header row`          | `#skip`                     |
| Compare to `None` with `is`                          | `if x is None:`                  | `if x == None:`             |
| Don't compare booleans to `True`                     | `if found:`                      | `if found == True:`         |
| End the file with one newline                        |                                  |                             |

<a name="c10-professional-issues-lsep-to-mention-in-reports"></a>

### Professional issues (LSEP) to mention in reports

| Issue                                  | What it means for a small data program                                                                                                                                     |
|----------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Data Protection Act 2018 / UK GDPR** | personal data must be processed lawfully, kept to the minimum needed, stored securely, and not kept longer than necessary. Even public datasets can contain personal data. |
| **Computer Misuse Act 1990**           | an offence to access or modify computer material without authorisation. Only use systems and data you are permitted to use.                                                |
| **Freedom of Information Act 2000**    | the public's right to request information held by public bodies. It is one route by which public datasets come into existence.                                             |
| **Copyright and licences**             | datasets and code have licences (e.g. GPL-3.0, MIT, CC BY). Respect them and credit sources.                                                                               |
| **Ethics / bias**                      | review data is self-selected and may not represent everyone. Present findings with that caveat.                                                                            |
| **Professional practice**              | version control, readable PEP-8 code, comments, testing, honest reporting of what does not work.                                                                           |

QHO444 Open-Book Reference · personal study notes for QHO444 (2026/27). Written in my own words from the module materials; all code was executed with Python before inclusion.
