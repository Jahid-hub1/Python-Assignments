> **GitHub edition:** Use the contents links or browser Ctrl+F to search. The original HTML search shortcuts, colour themes and interactive controls are not available here. Solutions are expanded; typed input is marked with ↵.

Problem Solving Through Programming

# Learn Python with QHO444

The whole module, Weeks 1–12, taught from zero: explanations, what happens under the hood, the lab exercises with solutions, and a track to follow.

Study at home, in order. Type every example, attempt every exercise before opening its solution.

Python 3.9 compatible · every example executed · no AE2 solutions.

## Contents

1.  [Start here: how this book works and your track](#c0-start-here-how-this-book-works-and-your-track)
    - [How each chapter is built](#c0-how-each-chapter-is-built)
    - [The only study method that works for programming](#c0-the-only-study-method-that-works-for-programming)
    - [Your track](#c0-your-track)
2.  [Chapter 1: Your tools and the profession](#c1-your-tools-and-the-profession)
    - [What a program is](#c1-what-a-program-is)
    - [The tools](#c1-the-tools)
    - [Version control with Git and GitHub](#c1-version-control-with-git-and-github)
    - [Professionalism](#c1-professionalism)
3.  [Chapter 2: Output, input, variables and types](#c2-output-input-variables-and-types)
    - [Printing](#c2-printing)
    - [Escape characters](#c2-escape-characters)
    - [Variables](#c2-variables)
    - [Reading input](#c2-reading-input)
    - [Data types](#c2-data-types)
    - [Arithmetic](#c2-arithmetic)
    - [Operators on strings](#c2-operators-on-strings)
    - [Summary](#c2-summary)
4.  [Chapter 3: Decisions](#c3-decisions)
    - [Booleans and comparisons](#c3-booleans-and-comparisons)
    - [if](#c3-if)
    - [if … else](#c3-if-else)
    - [if … elif … else](#c3-if-elif-else)
    - [The modulo operator](#c3-the-modulo-operator)
    - [Nested decisions](#c3-nested-decisions)
    - [Combining conditions: and, or, not](#c3-combining-conditions-and-or-not)
    - [Summary](#c3-summary)
5.  [Chapter 4: Loops](#c4-loops)
    - [Why loops](#c4-why-loops)
    - [while loops](#c4-while-loops)
    - [len()](#c4-len)
    - [for loops and range()](#c4-for-loops-and-range)
    - [Looping over strings](#c4-looping-over-strings)
    - [Nested loops](#c4-nested-loops)
    - [break and continue](#c4-break-and-continue)
    - [Summary](#c4-summary)
6.  [Chapter 5: Functions and modules](#c5-functions-and-modules)
    - [Why functions](#c5-why-functions)
    - [Built-in functions](#c5-built-in-functions)
    - [Defining a function](#c5-defining-a-function)
    - [Parameters and arguments](#c5-parameters-and-arguments)
    - [return: getting a result back](#c5-return-getting-a-result-back)
    - [Scope: where a variable exists](#c5-scope-where-a-variable-exists)
    - [Docstrings](#c5-docstrings)
    - [Modules](#c5-modules)
    - [Putting it together: a menu program](#c5-putting-it-together-a-menu-program)
    - [Summary](#c5-summary)
7.  [Chapter 6: Lists and tuples](#c6-lists-and-tuples)
    - [Data structures](#c6-data-structures)
    - [Lists](#c6-lists)
    - [Tuples](#c6-tuples)
    - [Nested lists](#c6-nested-lists)
    - [Summary](#c6-summary)
8.  [Chapter 7: Files: text and CSV](#c7-files-text-and-csv)
    - [Files, folders and paths](#c7-files-folders-and-paths)
    - [File formats you will meet](#c7-file-formats-you-will-meet)
    - [Opening and closing](#c7-opening-and-closing)
    - [Reading text](#c7-reading-text)
    - [Writing and appending](#c7-writing-and-appending)
    - [CSV files](#c7-csv-files)
    - [When the file isn't there: try / except](#c7-when-the-file-isnt-there-try-except)
    - [Summary](#c7-summary)
9.  [Chapter 8: Sets, dictionaries and JSON](#c8-sets-dictionaries-and-json)
    - [Unordered data structures](#c8-unordered-data-structures)
    - [Sets](#c8-sets)
    - [Dictionaries](#c8-dictionaries)
    - [Three patterns you will use constantly](#c8-three-patterns-you-will-use-constantly)
    - [Nested dictionaries](#c8-nested-dictionaries)
    - [JSON](#c8-json)
    - [Summary](#c8-summary)
10. [Chapter 9: Visualising data with matplotlib](#c9-visualising-data-with-matplotlib)
    - [Why visualise](#c9-why-visualise)
    - [Third-party libraries](#c9-third-party-libraries)
    - [Line charts](#c9-line-charts)
    - [Bar charts](#c9-bar-charts)
    - [Pie charts](#c9-pie-charts)
    - [Step plots](#c9-step-plots)
    - [Plotting from data structures](#c9-plotting-from-data-structures)
    - [A good chart checklist](#c9-a-good-chart-checklist)
    - [Summary](#c9-summary)
11. [Chapter 10: Object-oriented programming](#c10-object-oriented-programming)
    - [From procedures to objects](#c10-from-procedures-to-objects)
    - [A first class](#c10-a-first-class)
    - [Class attributes vs instance attributes](#c10-class-attributes-vs-instance-attributes)
    - [Static methods and class methods](#c10-static-methods-and-class-methods)
    - [Magic methods: \_\_str\_\_ and \_\_repr\_\_](#c10-magic-methods-str-and-repr-)
    - [Methods that change state](#c10-methods-that-change-state)
    - [Objects inside objects (composition)](#c10-objects-inside-objects-composition)
    - [Plotting data held in objects](#c10-plotting-data-held-in-objects)
    - [Summary](#c10-summary)
12. [Chapter 11: Inheritance and abstraction](#c11-inheritance-and-abstraction)
    - [The problem: duplicated classes](#c11-the-problem-duplicated-classes)
    - [Class diagrams](#c11-class-diagrams)
    - [Inheritance in code](#c11-inheritance-in-code)
    - [isinstance: what kind of object is this?](#c11-isinstance-what-kind-of-object-is-this)
    - [Abstract classes](#c11-abstract-classes)
    - [Why bother? Polymorphism](#c11-why-bother-polymorphism)
    - [Summary](#c11-summary)
13. [Chapter 12: Case studies: Titanic and Olympics](#c12-case-studies-titanic-and-olympics)
    - [How to attack a specification](#c12-how-to-attack-a-specification)
    - [Case study 1: Titanic](#c12-case-study-1-titanic)
    - [Case study 2: Olympics, three modules](#c12-case-study-2-olympics-three-modules)
14. [Chapter 13: Problem solving, testing, debugging and professional practice](#c13-problem-solving-testing-debugging-and-professional-practice)
    - [A problem-solving process](#c13-a-problem-solving-process)
    - [Testing](#c13-testing)
    - [Debugging](#c13-debugging)
    - [Writing professional code: PEP-8](#c13-writing-professional-code-pep-8)
    - [Code quality beyond style](#c13-code-quality-beyond-style)
    - [Legal, social, ethical and professional issues](#c13-legal-social-ethical-and-professional-issues)
    - [Documenting your work](#c13-documenting-your-work)
15. [Appendix: Glossary](#c14-glossary)

<a name="c0-start-here-how-this-book-works-and-your-track"></a>

## Start here: how this book works and your track

This book teaches the whole of QHO444 from zero, in the same order as the module's weeks. It assumes you have never written a program before. By the end you will be able to read a written specification, break it into functions, build it across several files, read and write data files, draw charts, and use classes and inheritance. Those are the skills AE1 tests directly and AE2 asks you to apply on your own.

<a name="c0-how-each-chapter-is-built"></a>

### How each chapter is built

| Part of a chapter             | What it is for                                                                                             |
|-------------------------------|------------------------------------------------------------------------------------------------------------|
| **Goals**                     | what you will be able to do by the end                                                                     |
| **Explanations and examples** | every example was run, and the output under it is real. Amber text followed by `↵` is what a user typed.   |
| Under the hood                | how Python actually does it: memory, types, why errors happen. Optional on first read, valuable on second. |
| Common mistake                | the error almost everyone makes at this point                                                              |
| Exercise                      | the module's lab activities, rewritten so you can do them here, each with a hidden solution                |
| Checkpoint                    | "predict the output" questions; answer before you reveal                                                   |

<a name="c0-the-only-study-method-that-works-for-programming"></a>

### The only study method that works for programming

1.  **Type the examples yourself.** Do not paste them. Typing forces you to notice every colon, bracket and indent, and those are what break your code.
2.  **Run, then change one thing, then run again.** Predict what the change will do *before* you press Run. When the result surprises you, you have found the gap in your understanding.
3.  **Attempt every exercise before opening the solution.** Fifteen minutes stuck is normal and is where the learning happens. If you are still stuck after that, open the solution, close it, and write it again from memory the next day.
4.  **Commit after every exercise** (`git add .`, `git commit -m "..."`). It builds the habit AE2 marks you on, and your history becomes a record of your progress.
5.  **Explain it out loud.** If you can't explain what a line does in plain English, you don't know it yet.

<a name="c0-your-track"></a>

### Your track

Work through the stages in order. Each stage ends with a checklist; tick an item only when you can do it **without looking anything up**. In the HTML version your ticks are saved in this browser.

<a name="c0-stage-1-talk-to-the-computer-chapters-12"></a>

#### Stage 1: Talk to the computer (Chapters 1–2)

- Create a project in PyCharm, run a file, and commit it to a private GitHub repository
- Print text, blank lines, tabs and quotes; draw an ASCII picture
- Read input, convert it to int or float, and print a sentence with an f-string
- Explain why "3" + "4" gives "34"

<a name="c0-stage-2-make-choices-and-repeat-chapters-34"></a>

#### Stage 2: Make choices and repeat (Chapters 3–4)

- Write if / elif / else with and, or, not, and say which branch runs for a given value
- Test even/odd with %
- Write a while loop that counts, and a while True loop that stops on a quit word
- Write a for loop with range(start, stop, step), including counting down
- Loop over the characters of a string, with and without indexes
- Draw a grid with nested loops

<a name="c0-stage-3-organise-your-code-chapter-5"></a>

#### Stage 3: Organise your code (Chapter 5)

- Write a function with parameters that RETURNS a value, and explain return vs print
- Split a program into a run() function that calls smaller functions
- Import from the standard library and from your own module
- Use if \_\_name\_\_ == "\_\_main\_\_": and explain why it exists
- Build a repeating text menu that ends when the user chooses quit

<a name="c0-stage-4-work-with-data-chapters-68"></a>

#### Stage 4: Work with data (Chapters 6–8)

- Create, index, slice, change and loop over a list; build one inside a loop
- Return two values from a function as a tuple and unpack them
- Read a text file line by line, and write and append to one
- Read a CSV with csv.reader, skip the header, convert columns to numbers
- Use a set to find distinct values and sort them
- Count things with a dictionary; build a dictionary of lists; build a nested dictionary
- Load and save JSON

<a name="c0-stage-5-show-the-data-chapter-9"></a>

#### Stage 5: Show the data (Chapter 9)

- Draw labelled line, bar and pie charts from lists and dictionaries
- Control colour, marker and line style; add a title and a legend

<a name="c0-stage-6-objects-chapters-1011"></a>

#### Stage 6: Objects (Chapters 10–11)

- Write a class with \_\_init\_\_, attributes, methods, \_\_str\_\_ and \_\_repr\_\_
- Explain class vs instance attributes, and static vs class methods
- Store objects inside another object (a Planet holding Humans)
- Write a child class that inherits and calls super().\_\_init\_\_()
- Make an abstract class with an abstract method and a concrete subclass
- Draw a simple class diagram

<a name="c0-stage-7-put-it-together-chapters-1213"></a>

#### Stage 7: Put it together (Chapters 12–13)

- Build the Titanic program from its written spec without looking at the solution
- Build the Olympics program as three modules (tui, process, main)
- Turn a written spec into a function list before writing any code
- Debug with tracebacks, print(repr(...)) and the PyCharm debugger
- Explain the legal, social, ethical and professional issues in a small data program

<a name="c0-before-ae1"></a>

#### Before AE1

- Every Checkpoint in this book answered correctly without running the code
- Practised with the AE1 practice quiz on SOL
- The Open-Book Reference open, searchable and tested on the machine you will use

**AE2 and AI**

The AE2 brief only allows generative AI for improving your report writing. It must not be used to produce any part of the solution. This book teaches the skills; it does not contain, and will not be extended with, AE2 solutions. Build AE2 yourself, from what you can do after finishing this book.

<a name="c1-your-tools-and-the-profession"></a>

## Chapter 1: Your tools and the profession

**Goals:** understand what a program is; set up Python, PyCharm, Git and GitHub; run your first file; commit and push it; know the standards a computing professional follows.

<a name="c1-what-a-program-is"></a>

### What a program is

A program is a list of instructions that the computer carries out **in order, one line at a time, top to bottom**, unless you tell it otherwise. Python reads your file, turns each line into actions, and stops at the end of the file or at the first error.

Programming is mostly problem solving: taking a vague human problem ("tell me how many passengers survived") and breaking it into steps so small and exact that a machine can follow them. Writing the Python is the last part. The module is called *Problem Solving Through Programming* for that reason.

**What actually runs your code**

Python is an *interpreted* language. When you press Run, a program called the Python interpreter (`python.exe` on Windows) reads your `.py` file, checks the whole file for **syntax** errors (grammar mistakes like a missing colon), compiles it to an internal form called bytecode, and then executes it line by line. That's why a syntax error anywhere stops the program before anything prints, while a *runtime* error, like dividing by zero, only appears when that line is reached.

<a name="c1-the-tools"></a>

### The tools

| Tool                         | What it is                                          | Why you need it                                                                                 |
|------------------------------|-----------------------------------------------------|-------------------------------------------------------------------------------------------------|
| **Python**                   | the interpreter that runs your code                 | nothing runs without it. The module guide specifies 3.9; anything newer also works.             |
| **PyCharm**                  | an IDE (Integrated Development Environment)         | an editor, a Run button, error highlighting, a debugger and a terminal in one window            |
| **Git**                      | version-control software on your computer           | records snapshots (commits) of your project so you can see and undo changes                     |
| **GitHub**                   | a website that hosts Git repositories               | an off-site backup, and evidence of your work. AE2 requires screenshots of your commit history. |
| **Learning on Demand (LoD)** | QA's virtual machines with everything pre-installed | use this if you can't install the tools on your own computer                                    |

<a name="c1-installing-on-your-own-windows-pc"></a>

#### Installing (on your own Windows PC)

1.  **Python**: download from python.org. On the first installer screen, tick **"Add Python to PATH"**.
2.  **Git**: download from git-scm.com and accept the defaults. When asked about PATH, choose "Git from the command line and also from 3rd-party software".
3.  **PyCharm**: download the free edition from jetbrains.com (or apply for the free student licence to get Professional).

Order matters a little: install Python and Git **before** PyCharm so PyCharm finds them automatically.

<a name="c1-version-control-with-git-and-github"></a>

### Version control with Git and GitHub

Imagine writing an essay and saving `essay_v1.docx`, `essay_v2_final.docx`, `essay_v2_final_REAL.docx`. Git does this properly. Each **commit** is a named snapshot of the whole project, and you can see exactly what changed between any two of them.

```text
 your files ──git add──▶ staging area ──git commit──▶ local repository ──git push──▶ GitHub
  (edit)                  (chosen changes)              (history on your PC)          (history online)
```

| Command                           | Meaning                                                               |
|-----------------------------------|-----------------------------------------------------------------------|
| `git status`                      | what has changed since the last commit                                |
| `git add .`                       | stage every change (the `.` means "this folder and everything below") |
| `git commit -m "Add ASCII robot"` | save the staged changes as a snapshot with a message                  |
| `git push`                        | upload your commits to GitHub                                         |

<a name="c1-first-time-setup"></a>

#### First-time setup

1.  Create a GitHub account (the module asks you to use your university email).
2.  Create a new repository. Set it to **Private**, tick *Add a README*, choose the *Python* `.gitignore` template, and pick a licence (e.g. GPL-3.0).
3.  In PyCharm: **Get from VCS → GitHub → authorise → choose the repository → Clone**.
4.  Open the `.gitignore` file and add a line `.idea/` so PyCharm's private settings are never committed.
5.  If GitHub keeps asking for a password when you push, set up an SSH key (GitHub Docs: *Generating a new SSH key* and *Adding a new SSH key to your account*).

**Exercise 1.1: First commit**

Create a file `week1/repo_test.py` containing one line that prints `This is a test.`. Run it. Then, in PyCharm's Terminal tab, stage, commit with the message `Testing PyCharm with GitHub`, and push. Refresh the repository page on GitHub to confirm the file arrived.

**Show solution**

```python
print("This is a test.")
```

```terminal
git add .
git commit -m "Testing PyCharm with GitHub"
git push
```

**Commit messages that look professional**

Write what the commit *does*, in the imperative: `Add function to read user input`, `Fix crash when file is missing`. A marker scrolling your history should be able to follow the story of your project from the messages alone.

<a name="c1-professionalism"></a>

### Professionalism

Being a professional means having skills and training **and** following the standards of your field. For this module, that means three things.

**1. Code style: PEP-8.** PEP-8 is Python's official style guide: 4-space indents, `snake_case` names for variables and functions, `CapWords` for classes, spaces around operators, two blank lines between functions, and so on. Consistent style makes code readable by anyone. AE2 asks for evidence (a PyCharm screenshot) that you followed it. Chapter 13 has the full checklist.

**2. Law.** Three UK Acts matter most to programmers:

| Act                                         | In one sentence                                                                         | Why a programmer cares                                                                  |
|---------------------------------------------|-----------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------|
| **Data Protection Act 2018** (with UK GDPR) | personal data must be handled lawfully, fairly, securely, and only as much as is needed | any program that stores names, emails, locations or reviews is processing personal data |
| **Computer Misuse Act 1990**                | it is a crime to access or modify computer material without permission                  | "testing" someone else's system without authorisation is illegal, whatever the intent   |
| **Freedom of Information Act 2000**         | people can request information held by public authorities                               | it is one source of public datasets, and public bodies' software must support it        |

**3. Skills beyond code:** problem solving, collaboration, and networking (the module encourages a LinkedIn profile and attending professional events).

**Exercise 1.2: Legislation notes**

In your own words, write two or three sentences for each Act above, describing a situation in which a programmer could break it. Save them as `week1/notes.md` and commit.

<a name="c2-output-input-variables-and-types"></a>

## Chapter 2: Output, input, variables and types

**Goals:** display text with `print`; control layout with escape characters; store values in variables; read what the user types; tell `str`, `int` and `float` apart and convert between them; build sentences with f-strings.

<a name="c2-printing"></a>

### Printing

`print` is a **built-in function**, a ready-made piece of code that ships with Python. You call it by writing its name followed by round brackets, and you put what it should display inside the brackets. That value is called an **argument**.

```python
# Display a message to the screen
print("Welcome to QHO444!")
print("In week 1 we will learn...")
print()                       # an empty print gives a blank line
print("...How to use Git and GitHub")
```

**Output**

```text
Welcome to QHO444!
In week 1 we will learn...

...How to use Git and GitHub
```

- Text inside quotes is a **string**. Double `"..."` and single `'...'` quotes both work. Pick one style and be consistent.
- A line starting with `#` is a **comment**. Python ignores it. Comments explain *why* the code does something, for the next human reader (often you, three weeks later).
- Each `print` ends by moving to a new line.

`print` accepts several arguments separated by commas and puts a space between them:

```python
print("Lives:", 3, "Energy:", 9.5)
print("2026", "11", "17", sep="/")     # change the separator
print("Same ", end="")                 # change the line ending
print("line")
```

**Output**

```text
Lives: 3 Energy: 9.5
2026/11/17
Same line
```

`sep` and `end` are **keyword arguments**: named settings you can override. By default `sep=" "` and `end="\n"`.

<a name="c2-escape-characters"></a>

### Escape characters

Inside a string, a backslash `\` starts an **escape sequence**, a code for a character you can't type directly.

```python
print("\n Starts with a new line")
print("\t Starts with a tab")
print("A backslash: \\")
print("A double quote: \" and a single quote: \'")
print('It\'s easier to switch quote style: "like this"')
```

**Output**

```text
 Starts with a new line
     Starts with a tab
A backslash: \
A double quote: " and a single quote: '
It's easier to switch quote style: "like this"
```

| Sequence    | Produces                            |
|-------------|-------------------------------------|
| `\n`        | new line                            |
| `\t`        | tab                                 |
| `\\`        | one backslash                       |
| `\"` / `\'` | a quote that doesn't end the string |

**Exercise 2.1: Escape characters**

Write **one** `print` call that produces a blank line and then a tabbed-in `"I am programming!"`, quotes included.

**Show solution**

```python
print("\n\t\"I am programming!\"")
```

**Output**

```text
    "I am programming!"
```

<a name="c2-multi-line-strings-and-ascii-art"></a>

#### Multi-line strings and ASCII art

Three quotes in a row start a string that can span several lines:

```python
print("""##########
#  o  o  #
#   ..   #
#  ----  #
##########""")
```

**Output**

```text
##########
#  o  o  #
#   ..   #
#  ----  #
##########
```

**Exercise 2.2: ASCII robot**

Draw a robot with a head, eyes, a mouth and a body using `print`. Be creative, and remember that a backslash in your drawing must be written as `\\`.

**Show solution**

```python
print("   _____")
print("  | o o |")
print("  |  -  |")
print("  |_____|")
print("  /|   |\\")
print(" / |___| \\")
print("   |   |")
print("  _|   |_")
```

**Output**

```text
   _____
  | o o |
  |  -  |
  |_____|
  /|   |\
 / |___| \
   |   |
  _|   |_
```

<a name="c2-variables"></a>

### Variables

A **variable** is a name that refers to a value, so you can use the value later. You create one with `=`, the **assignment operator**:

```python
name = "Link"
lives = 3
print(name, "has", lives, "lives")
lives = lives - 1           # read the old value, subtract 1, store the result
print(name, "has", lives, "lives")
```

**Output**

```text
Link has 3 lives
Link has 2 lives
```

Read `=` as "**becomes**", not "equals". `lives = lives - 1` is nonsense in maths but perfectly sensible in Python: the right-hand side is worked out first, then the name is pointed at the result.

**Naming rules:** letters, digits and underscores only; you can't start with a digit; names are case-sensitive (`Name` and `name` are different). PEP-8 style is `lower_case_with_underscores`. Choose names that describe the contents: `user_age`, not `x`.

**Variables are labels, not boxes**

In many languages a variable is a box that holds a value. In Python a variable is a **label attached to an object** in memory. `lives = 3` creates an integer object `3` and ties the label `lives` to it. `lives = lives - 1` creates a *new* object `2` and moves the label. This matters later: when two labels point at the same *list*, changing the list through one label changes what you see through the other (Chapter 6).

<a name="c2-reading-input"></a>

### Reading input

`input()` pauses the program, waits for the user to type something and press Enter, and **returns** what they typed as a string. You normally store it in a variable:

```python
# Ask the user to enter their name
print("What is your name?")
name = input()
print(f"It is nice to meet you {name}")
```

**Output**

```text
What is your name?
Link ↵
It is nice to meet you Link
```

You can pass the prompt straight to `input`, as in `name = input("What is your name? ")`. The module's labs usually print the question on its own line and then call `input()` with nothing in the brackets. Either is fine, but when a question shows the expected output, match the layout it shows exactly.

<a name="c2-f-strings"></a>

#### f-strings

An **f-string** has an `f` before the opening quote. Anything inside `{curly brackets}` is worked out and inserted:

```python
name = "Link"
age = 37
print(f"{name} is {age} years old. Next year {name} will be {age + 1}.")
```

**Output**

```text
Link is 37 years old. Next year Link will be 38.
```

**Exercise 2.3: Robot eyes**

Ask the user for a character, then draw a robot face that uses that character for both eyes.

**Show solution**

```python
print("Please enter a character for the eye")
eye = input()
print("The robots expression is now as follows:")
print("##########")
print(f"#  {eye}  {eye}  #")
print("#  ----  #")
print("##########")
```

**Output**

```text
Please enter a character for the eye
o ↵
The robots expression is now as follows:
##########
#  o  o  #
#  ----  #
##########
```

<a name="c2-data-types"></a>

### Data types

Every value has a **type**, which decides what you can do with it.

| Type    | Holds           | Examples                | Convert with |
|---------|-----------------|-------------------------|--------------|
| `str`   | text            | `"hello"`, `"42"`, `""` | `str()`      |
| `int`   | whole numbers   | `42`, `-7`, `0`         | `int()`      |
| `float` | decimal numbers | `3.14`, `2.0`, `-0.5`   | `float()`    |
| `bool`  | true/false      | `True`, `False`         | `bool()`     |

```python
print(type("42"), type(42), type(42.0), type(True))
```

**Output**

```text
<class 'str'> <class 'int'> <class 'float'> <class 'bool'>
```

<a name="c2-input-always-returns-a-string"></a>

#### `input()` always returns a string

This is the most important sentence in this chapter. If the user types `12`, you get the **text** `"12"`, not the number 12.

```python
a = input("First number: ")
b = input("Second number: ")
print(a + b)                 # joins two strings
print(int(a) + int(b))       # adds two numbers
```

**Output**

```text
First number: 12 ↵
Second number: 3 ↵
123
15
```

So convert as soon as you read a number:

```python
whole_number = int(input())
decimal_number = float(input())
```

**int() is fussy**

`int("12")` works. `int("12.5")`, `int("twelve")` and `int("")` all crash with `ValueError`. If the value might have a decimal point, use `float()`.

<a name="c2-arithmetic"></a>

### Arithmetic

| Operator | Meaning             | Example  | Result                 |
|----------|---------------------|----------|------------------------|
| `+`      | add                 | `7 + 2`  | `9`                    |
| `-`      | subtract            | `7 - 2`  | `5`                    |
| `*`      | multiply            | `7 * 2`  | `14`                   |
| `/`      | divide              | `7 / 2`  | `3.5` (always a float) |
| `//`     | whole-number divide | `7 // 2` | `3`                    |
| `%`      | remainder           | `7 % 2`  | `1`                    |
| `**`     | power               | `7 ** 2` | `49`                   |

Python follows the usual maths order: brackets, then `**`, then `* / // %`, then `+ -`. When in doubt, add brackets. They cost nothing and make your intent obvious.

<a name="c2-formatting-numbers"></a>

#### Formatting numbers

`:.2f` inside the braces of an f-string means "as a decimal with 2 places":

```python
bmi = 70 / 1.80 ** 2
print(bmi)
print(f"{bmi:.2f}")
print(f"{bmi:.1f}")
print(format(bmi, ".2f"))     # the format() function does the same
```

**Output**

```text
21.604938271604937
21.60
21.6
21.60
```

**Exercise 2.4: BMI calculator**

Ask for the user's name, age (years), height (metres) and weight (kg). Calculate BMI as weight ÷ height² and print, for example, `Link you are 37 years old and your bmi is 21.60.`. Show the BMI to 2 decimal places.

**Show solution**

```python
# Read the user's details, converting the numbers straight away
print("What is your name?")
name = input()
print("How old are you (in years)?")
age = int(input())
print("How tall are you (in meters)?")
height = float(input())
print("How much do you weigh (in kilograms)?")
weight = float(input())

# BMI = weight divided by height squared
bmi = weight / height ** 2
print(f"{name} you are {age} years old and your bmi is {bmi:.2f}.")
```

**Output**

```text
What is your name?
Link ↵
How old are you (in years)?
37 ↵
How tall are you (in meters)?
1.80 ↵
How much do you weigh (in kilograms)?
70 ↵
Link you are 37 years old and your bmi is 21.60.
```

<a name="c2-operators-on-strings"></a>

### Operators on strings

`+` **joins** (concatenates) two strings, and `*` **repeats** a string a whole number of times:

```python
print("ab" + "cd")
print("ab" * 3)
print("-" * 20)
```

**Output**

```text
abcd
ababab
--------------------
```

You can't `+` a string and a number. Python refuses to guess what you meant:

```python
lives = 3
print("Lives: " + lives)
```

**Output (error)**

```text
Traceback (most recent call last):
  File "main.py", line 2, in <module>
    ...
TypeError: can only concatenate str (not "int") to str
```

Fix it with `str(lives)` or, more simply, an f-string: `f"Lives: {lives}"`.

**Exercise 2.5: Game status**

Ask for the number of lives, the energy level and the shield level (all whole numbers). Then print a status display using `♥` for lives and `♦` for energy and shield, like this:

```text
Lives: ♥♥♥
Energy: ♦♦♦♦♦♦♦♦♦♦
Shield: ♦♦♦♦♦♦♦
```

**Show solution**

```python
print("Please enter the number of lives.")
lives = int(input())
print("Please enter the energy level.")
energy = int(input())
print("Please enter the shield level.")
shield = int(input())

print("Health has been set.")
print("Lives: " + "♥" * lives)
print("Energy: " + "♦" * energy)
print("Shield: " + "♦" * shield)
```

**Output**

```text
Please enter the number of lives.
3 ↵
Please enter the energy level.
10 ↵
Please enter the shield level.
7 ↵
Health has been set.
Lives: ♥♥♥
Energy: ♦♦♦♦♦♦♦♦♦♦
Shield: ♦♦♦♦♦♦♦
```

**Checkpoint 2**

Predict each output **before** you reveal the answers.

1.  `print("5" + "5")`
2.  `print(5 + 5)`
3.  `print("5" * 3)`
4.  `print(10 / 5)`
5.  `print(type(input()))` when the user types `7`
6.  `x = 4` then `x = x * 2 + 1`. What is `x`?

**Answers**

1.  `55` (string joining)
2.  `10`
3.  `555`
4.  `2.0`, because `/` always produces a float
5.  `<class 'str'>`, because input is always text
6.  `9`, because `*` happens before `+`

<a name="c2-summary"></a>

### Summary

- `print()` displays text; `sep=` and `end=` change the spacing; `\n`, `\t`, `\\` and `\"` are escapes.
- `name = value` makes a variable. Read `=` as "becomes".
- `input()` returns a **string**. Convert with `int()` or `float()` before doing maths.
- f-strings, `f"...{expression}..."`, are the clean way to build output; `{x:.2f}` gives 2 decimal places.
- `+` and `*` behave differently on strings (join, repeat) and numbers (add, multiply).

<a name="c3-decisions"></a>

## Chapter 3: Decisions

**Goals:** make your program choose between paths with `if`, `elif` and `else`; compare values; use the modulo operator; nest decisions; combine conditions with `and`, `or` and `not`.

<a name="c3-booleans-and-comparisons"></a>

### Booleans and comparisons

A decision needs a question with a yes/no answer. In Python the answer is a **boolean**: `True` or `False`. Comparison operators produce booleans:

| Operator    | Means                            | `5 ? 3`          |
|-------------|----------------------------------|------------------|
| `==`        | equal to                         | `False`          |
| `!=`        | not equal to                     | `True`           |
| `>` / `<`   | greater / less than              | `True` / `False` |
| `>=` / `<=` | greater or equal / less or equal | `True` / `False` |

```python
print(5 > 3, 5 == 3, "adventure" == "adventure", "A" == "a")
```

**Output**

```text
True False True False
```

**\`=\` versus \`==\`**

`=` **assigns** (`x = 5` makes x refer to 5). `==` **compares** (`x == 5` asks whether x equals 5). Writing `if x = 5:` is a syntax error.

<a name="c3-if"></a>

### if

```text
        ┌────────────────────┐
        │ first > second ?   │
        └─────────┬──────────┘
            True  │   False
        ┌─────────▼───┐   │
        │ print(...)  │   │
        └─────────┬───┘   │
                  ▼◀──────┘
            print("Done!")
```

```python
first_number = 9
second_number = 4
if first_number > second_number:
    print("First is bigger!")
print("Done!")
```

**Output**

```text
First is bigger!
Done!
```

The line ending in a colon is the **header**. The indented lines under it form a **block**, and they only run when the condition is `True`. Indentation is not decoration in Python: it *is* the structure. Use 4 spaces. PyCharm inserts them when you press Tab.

**Exercise 3.1: Book type**

Ask what type of book it is. If the answer is `adventure`, print `I like adventure books!`. Whatever the answer, finish with `Finished reading book.`

**Show solution**

```python
print("What type of book is this?")
book_type = input()
if book_type == "adventure":
    print("I like adventure books!")
print("Finished reading book.")
```

**Output**

```text
What type of book is this?
adventure ↵
I like adventure books!
Finished reading book.
```

<a name="c3-if-else"></a>

### if … else

`else` gives the path to take when the condition is false. It has no condition of its own, and there can be at most one per `if`.

```python
print("Please enter the activity to be performed.")
activity = input()
if activity == "calculate":
    print("Performing calculations...")
else:
    print("Performing activity...")
print("Activity completed!")
```

**Output**

```text
Please enter the activity to be performed.
paint ↵
Performing activity...
Activity completed!
```

<a name="c3-if-elif-else"></a>

### if … elif … else

For more than two paths, add `elif` ("else if") branches. Python tests the conditions **top to bottom** and runs **only the first** block whose condition is true. The rest are skipped, even if they would also be true.

```python
entity = "Robot"
if entity == "Human":
    print("You are a human!")
elif entity == "Robot":
    print("You are a robot!")
elif entity == "Animal":
    print("You are an animal!")
else:
    print("I do not know what you are!")
print("Analysis complete.")
```

**Output**

```text
You are a robot!
Analysis complete.
```

**Why the order of elif branches matters**

Look at a grading rule written in the wrong order:

```python
score = 85
if score >= 40:
    print("Pass")
elif score >= 70:
    print("Distinction")
```

**Output**

```text
Pass
```

It prints `Pass`, because `85 >= 40` is true and Python stops there. Put the **most specific** (strictest) condition first. That is also the bug in the Titanic case study's age groups (Chapter 12).

**Exercise 3.2: Robot directions**

Ask which way the robot should move (`up`, `down`, `left`, `right`) and print a matching message, e.g. `I am moving in an upward direction!`. Anything else should print a sensible error.

**Show solution**

```python
print("Towards which direction should I go (up, down, left or right)?")
direction = input()
if direction == "up":
    print("I am moving in an upward direction!")
elif direction == "down":
    print("I am moving in a downward direction!")
elif direction == "left":
    print("I am moving to the left!")
elif direction == "right":
    print("I am moving to the right!")
else:
    print("I do not know that direction.")
```

**Output**

```text
Towards which direction should I go (up, down, left or right)?
left ↵
I am moving to the left!
```

<a name="c3-the-modulo-operator"></a>

### The modulo operator

`%` gives the **remainder** after division. `10 % 3` is `1` because 10 = 3 × 3 + 1. Its classic use is testing divisibility: a number is even exactly when `n % 2 == 0`.

```python
for n in [10, 7, 0]:
    print(n, n % 2, n % 3)
```

**Output**

```text
10 0 1
7 1 1
0 0 0
```

**Exercise 3.3: Even or odd**

Ask for a whole number and say whether it is even or odd: `The number 5 is an odd number.`

**Show solution**

```python
print("Please enter a whole number.")
number = int(input())
if number % 2 == 0:
    print(f"The number {number} is an even number.")
else:
    print(f"The number {number} is an odd number.")
```

**Output**

```text
Please enter a whole number.
5 ↵
The number 5 is an odd number.
```

**Exercise 3.4: Smallest of two**

Ask for two numbers and print which is smallest, or `Both are equal!`.

**Show solution**

```python
print("Please enter the first number.")
first = float(input())
print("Please enter the second number.")
second = float(input())
if first < second:
    print("The first number is the smallest!")
elif second < first:
    print("The second number is the smallest!")
else:
    print("Both are equal!")
```

**Output**

```text
Please enter the first number.
7 ↵
Please enter the second number.
3 ↵
The second number is the smallest!
```

**Exercise 3.5: Counting evens and odds (no loops yet)**

Ask for three whole numbers, one at a time, and report `There were 2 even and 1 odd numbers.`

**Show solution**

```python
evens = 0
odds = 0

print("Please enter the first whole number.")
if int(input()) % 2 == 0:
    evens += 1
else:
    odds += 1

print("Please enter the second whole number.")
if int(input()) % 2 == 0:
    evens += 1
else:
    odds += 1

print("Please enter the third whole number.")
if int(input()) % 2 == 0:
    evens += 1
else:
    odds += 1

print(f"There were {evens} even and {odds} odd numbers.")
```

**Output**

```text
Please enter the first whole number.
2 ↵
Please enter the second whole number.
4 ↵
Please enter the third whole number.
5 ↵
There were 2 even and 1 odd numbers.
```

Notice the same four lines appear three times. Repeated code is a sign you need a **loop** (next chapter) or a **function** (Chapter 5).

`evens += 1` is shorthand for `evens = evens + 1`. The same pattern works with `-=`, `*=` and `/=`.

<a name="c3-nested-decisions"></a>

### Nested decisions

A decision inside a decision is used when the second question only makes sense after a particular answer to the first.

```python
print("What should I do (recover/study)?")
activity = input()
if activity == "recover":
    print("How would you like to recover (sleep/socialise)?")
    recover_by = input()
    if recover_by == "sleep":
        print("zzzZZZzzz")
    else:
        print("I will text my friends!")
else:
    print("I will study")
```

**Output**

```text
What should I do (recover/study)?
recover ↵
How would you like to recover (sleep/socialise)?
socialise ↵
I will text my friends!
```

The inner `if` is indented **twice** and only runs inside the first branch.

**Exercise 3.6: Book covers**

Ask for the cover type (`hard` or `soft`). For `soft`, ask whether it is perfect-bound. If yes, print `Soft cover, perfect bound books are very popular!`; otherwise print `Soft covers with coils or stitches are great for short books`. For `hard`, print `Books with hard covers can be more expensive!`.

**Show solution**

```python
print("What type of cover does the book have?")
cover = input()
if cover == "soft":
    print("Is the book perfect-bound?")
    perfect_bound = input()
    if perfect_bound == "yes":
        print("Soft cover, perfect bound books are very popular!")
    else:
        print("Soft covers with coils or stitches are great for short books")
elif cover == "hard":
    print("Books with hard covers can be more expensive!")
```

**Output**

```text
What type of cover does the book have?
soft ↵
Is the book perfect-bound?
yes ↵
Soft cover, perfect bound books are very popular!
```

**Exercise 3.7: Where is my phone?**

Ask where to look: `in the bedroom`, `in the bathroom` or `in the living room`. Each answer asks a follow-up question:

- bedroom: `under the bed` → `Found some shoes but no phone`; anything else → `Found some mess but no phone.`
- bathroom: `in the bathtub` → `Found a rubber duck but no phone`; anything else → `Found bathroom stuff but no phone.`
- living room: `on the table` → `Yes! I found my phone!`; anything else → `Found some stuff but no phone.`

Any other first answer prints `I do not know where that is but I will keep looking.`

**Show solution**

```python
print("Where should I look?")
place = input()
if place == "in the bedroom":
    print("Where in the bedroom should I look?")
    spot = input()
    if spot == "under the bed":
        print("Found some shoes but no phone")
    else:
        print("Found some mess but no phone.")
elif place == "in the bathroom":
    print("Where in the bathroom should I look?")
    spot = input()
    if spot == "in the bathtub":
        print("Found a rubber duck but no phone")
    else:
        print("Found bathroom stuff but no phone.")
elif place == "in the living room":
    print("Where in the living room should I look?")
    spot = input()
    if spot == "on the table":
        print("Yes! I found my phone!")
    else:
        print("Found some stuff but no phone.")
else:
    print("I do not know where that is but I will keep looking.")
```

**Output**

```text
Where should I look?
in the living room ↵
Where in the living room should I look?
on the table ↵
Yes! I found my phone!
```

<a name="c3-combining-conditions-and-or-not"></a>

### Combining conditions: and, or, not

| Operator  | True when                             | Example                                     |
|-----------|---------------------------------------|---------------------------------------------|
| `a and b` | **both** are true                     | `size == "big" and weight == "heavy"`       |
| `a or b`  | **at least one** is true              | `shape == "square" or shape == "rectangle"` |
| `not a`   | `a` is false (it flips **one** value) | `not finished`                              |

| a     | b     | a and b | a or b | not a |
|-------|-------|---------|--------|-------|
| True  | True  | True    | True   | False |
| True  | False | False   | True   | False |
| False | True  | False   | True   | True  |
| False | False | False   | False  | True  |

```python
print("What size is the parcel?")
size = input()
print("What is the weight of the parcel?")
weight = input()
if size == "big" and weight == "heavy":
    print("This parcel will be expensive to deliver.")
else:
    print("This parcel will be inexpensive to deliver.")
```

**Output**

```text
What size is the parcel?
big ↵
What is the weight of the parcel?
heavy ↵
This parcel will be expensive to deliver.
```

**Each side of \`or\` must be a complete comparison**

`if shape == "square" or "rectangle":` is **always true**, because Python reads it as `(shape == "square") or ("rectangle")` and a non-empty string counts as true. Write `shape == "square" or shape == "rectangle"`, or better: `shape in ("square", "rectangle")`.

**Short-circuiting and truthiness**

Python stops evaluating `and` as soon as one side is false, and `or` as soon as one side is true. So `count > 0 and total / count > 5` never divides by zero. Every value also has a truth value: `0`, `0.0`, `""`, `[]`, `{}` and `None` count as false, and almost everything else counts as true. That's why `if name:` means "if name is not empty".

**Exercise 3.8: Adventure routes**

Ask for the type of adventure. `scary` or `short` → `Entering the dark forest!`; `safe` or `long` → `Taking the safe route!`; anything else → `Not sure which route to take.`

Then ask `What did I hear?` and `What did I see?`. If the answers are `grrr` **and** `two red eyes`, print `There is a scary creature. I should get out of here!`; otherwise print `I am a little scared but I will continue.`

**Show solution**

```python
print("What type of adventure should I have?")
adventure = input()
if adventure == "scary" or adventure == "short":
    print("Entering the dark forest!")
elif adventure == "safe" or adventure == "long":
    print("Taking the safe route!")
else:
    print("Not sure which route to take.")

print("What did I hear?")
heard = input()
print("What did I see?")
saw = input()
if heard == "grrr" and saw == "two red eyes":
    print("There is a scary creature. I should get out of here!")
else:
    print("I am a little scared but I will continue.")
```

**Output**

```text
What type of adventure should I have?
short ↵
Entering the dark forest!
What did I hear?
grrr ↵
What did I see?
two red eyes ↵
There is a scary creature. I should get out of here!
```

**Exercise 3.9: Review**

Write your own short adventure (`week2/review.py`) that uses at least one `if/elif/else`, one nested decision, and each of `and`, `or` and `not`. There is no single right answer. Test every path through it.

**Checkpoint 3**

1.  `x = 15`. Which lines print? `if x > 10: print("A")` / `elif x > 5: print("B")` / `else: print("C")`
2.  Same `x`, but written as two separate `if`s: `if x > 10: print("A")` then `if x > 5: print("B")`.
3.  What does `print(7 % 4, 8 % 4)` show?
4.  `name = ""`. Does `if name:` run its block?
5.  Is `not (3 > 2 and 2 > 3)` True or False?

**Answers**

1.  Only `A`. Python stops at the first true branch.
2.  `A` and then `B`, because separate `if`s are each checked.
3.  `3 0`
4.  No. An empty string counts as false.
5.  `True`. The inner part is `True and False`, which is `False`, and `not False` is `True`.

<a name="c3-summary"></a>

### Summary

- `if condition:` followed by an indented block. Add `elif` for more options and `else` for "everything else".
- Only the first true branch of an `if/elif/else` chain runs, so put the strictest test first.
- `%` gives the remainder; `n % 2 == 0` tests for even.
- Nest an `if` inside another when the second question depends on the first answer.
- `and` needs both sides true, `or` needs one, `not` flips one value. Each side must be a full comparison.

<a name="c4-loops"></a>

## Chapter 4: Loops

**Goals:** repeat code with `while` and `for`; use counters and running totals; generate number sequences with `range`; walk through strings character by character; nest loops; stop early with `break`.

<a name="c4-why-loops"></a>

### Why loops

Exercise 3.5 repeated the same four lines three times. What if it had been 300 numbers? A **loop** runs a block of code repeatedly, so you write the code once.

Python has two loops:

| Loop                    | Use when                                                                            | Example                                             |
|-------------------------|-------------------------------------------------------------------------------------|-----------------------------------------------------|
| `while condition:`      | you **don't know** in advance how many repeats (keep going until something happens) | keep asking until the user types `quit`             |
| `for item in sequence:` | you **do know**: a fixed count, or every item in a collection                       | do something 10 times; check every letter in a word |

Either can do the other's job, but picking the right one makes your intent obvious.

<a name="c4-while-loops"></a>

### while loops

A `while` loop is an `if` that goes back to the top: while the condition is true, run the block, then check again.

```python
iterations = 0                     # control variable
print("Starting iterations...")
while iterations < 3:
    iterations = iterations + 1    # change it, or the loop never ends
    print(f"Iteration {iterations}")
print(f"Completed {iterations}!")
```

**Output**

```text
Starting iterations...
Iteration 1
Iteration 2
Iteration 3
Completed 3!
```

Trace it by hand: `0 < 3` true → becomes 1; `1 < 3` true → 2; `2 < 3` true → 3; `3 < 3` **false** → leave the loop.

**Infinite loops**

If nothing inside the loop ever makes the condition false, the loop runs forever. In PyCharm, press the red **Stop** square. The usual cause is forgetting to update the control variable.

**Exercise 4.1: Removing apples**

Ask `How many apples should I remove?` and print `Removed apple.` that many times using a `while` loop.

**Show solution**

```python
print("How many apples should I remove?")
apples = int(input())
removed = 0
while removed < apples:
    print("Removed apple.")
    removed += 1
```

**Output**

```text
How many apples should I remove?
3 ↵
Removed apple.
Removed apple.
Removed apple.
```

**Exercise 4.2: Avoiding obstacles**

Ask how many obstacles to avoid. For each one, print `Avoiding...` and then, **on the same line**, `Done! n obstacles avoided.`. Finish with `All obstacles have been avoided.`

Hint: `print("Avoiding...", end="")` stays on the same line.

**Show solution**

```python
print("How many obstacles should I avoid?")
total = int(input())
avoided = 0
while avoided < total:
    print("Avoiding...", end="")
    avoided += 1
    print(f"Done! {avoided} obstacles avoided.")
print("All obstacles have been avoided.")
```

**Output**

```text
How many obstacles should I avoid?
3 ↵
Avoiding...Done! 1 obstacles avoided.
Avoiding...Done! 2 obstacles avoided.
Avoiding...Done! 3 obstacles avoided.
All obstacles have been avoided.
```

**Exercise 4.3: Charging bars**

Ask how many bars to charge. Show the battery filling up one bar per line (`Charging: █`, `Charging: █ █`, …), then `The battery is fully charged.`

**Show solution**

```python
print("How many bars should be charged?")
bars = int(input())
charged = 0
while charged < bars:
    charged += 1
    print("Charging: " + "█ " * charged)
print("The battery is fully charged.")
```

**Output**

```text
How many bars should be charged?
4 ↵
Charging: █ 
Charging: █ █ 
Charging: █ █ █ 
Charging: █ █ █ █ 
The battery is fully charged.
```

<a name="c4-counters-and-accumulators"></a>

#### Counters and accumulators

Two patterns appear in almost every loop:

- a **counter** goes up by 1 each time something happens: `count += 1`
- an **accumulator** builds up a running total: `total += value`

Both must start at `0` **before** the loop.

**Exercise 4.4: Sum of 1 to 100**

Use a `while` loop to add up the numbers 1 to 100 inclusive and print `...Done! The answer is 5050.`

**Show solution**

```python
print("Calculating the sum of the first 100 numbers...")
total = 0
number = 1
while number <= 100:
    total += number
    number += 1
print(f"...Done! The answer is {total}.")
```

**Output**

```text
Calculating the sum of the first 100 numbers...
...Done! The answer is 5050.
```

**Exercise 4.5: Summing user numbers**

Ask how many numbers to add. Then ask for each one (`Please enter number 1 of 4:`) and print the total.

**Show solution**

```python
print("How many numbers should I sum up?")
how_many = int(input())
total = 0
count = 0
while count < how_many:
    count += 1
    print(f"Please enter number {count} of {how_many}:")
    total += int(input())
print(f"The answer is {total}.")
```

**Output**

```text
How many numbers should I sum up?
4 ↵
Please enter number 1 of 4:
11 ↵
Please enter number 2 of 4:
6 ↵
Please enter number 3 of 4:
22 ↵
Please enter number 4 of 4:
12 ↵
The answer is 51.
```

<a name="c4-loops-that-stop-on-a-condition-while-true-and-break"></a>

#### Loops that stop on a condition: `while True` and `break`

When the stopping condition is easiest to check in the middle of the loop, use `while True:` and leave with `break`:

```python
while True:
    word = input("Say something (quit to stop): ")
    if word == "quit":
        break                      # jump out of the loop immediately
    print(f"You said {word}")
print("Bye")
```

**Output**

```text
Say something (quit to stop): hello ↵
You said hello
Say something (quit to stop): world ↵
You said world
Say something (quit to stop): quit ↵
Bye
```

This is the shape of every menu-driven program in the module: show the menu, read a choice, act on it, and repeat until the user picks exit.

<a name="c4-len"></a>

### len()

`len()` returns the number of items in something. For a string, that is the number of characters, spaces included:

```python
print("Please enter a phrase:")
phrase = input()
count = 0
while count < len(phrase):
    print("Hi", end=" ")
    count += 1
print()
```

**Output**

```text
Please enter a phrase:
Hello Friend ↵
Hi Hi Hi Hi Hi Hi Hi Hi Hi Hi Hi Hi 
```

<a name="c4-for-loops-and-range"></a>

### for loops and range()

`range(n)` produces the numbers `0, 1, …, n-1`. A `for` loop takes each one in turn:

```python
for count in range(3):
    print("Face number", count)
```

**Output**

```text
Face number 0
Face number 1
Face number 2
```

`range` accepts up to three arguments: `range(start, stop, step)`.

| Call              | Numbers   |
|-------------------|-----------|
| `range(5)`        | 0 1 2 3 4 |
| `range(1, 6)`     | 1 2 3 4 5 |
| `range(1, 10, 2)` | 1 3 5 7 9 |
| `range(0, 10, 2)` | 0 2 4 6 8 |
| `range(5, 0, -1)` | 5 4 3 2 1 |

The **stop value is never included**. To count to 10 inclusive, stop at 11.

**What \`for\` really does**

`for x in thing:` asks `thing` for its items one at a time and binds the name `x` to each in turn. `range` doesn't build a list of numbers in memory; it generates each number when asked, so `range(1_000_000_000)` costs almost nothing. Because `for` works with anything that can hand out items one at a time (an *iterable*), the same loop shape works for strings, lists, files, dictionaries and sets.

**Exercise 4.6: Mountains**

Ask how many ASCII mountains to display and draw that many using a `for` loop, between `Displaying...` and `Done!`.

**Show solution**

```python
print("How many mountains should I display?")
mountains = int(input())
print("Displaying...")
for count in range(mountains):
    print("      __")
    print("     /  \\_")
    print("    /^    \\")
    print("   / ^     \\_")
    print(" _/ ^  ^  ^  \\")
    print("/  ^     ^    \\")
print("Done!")
```

**Output**

```text
How many mountains should I display?
2 ↵
Displaying...
      __
     /  \_
    /^    \
   / ^     \_
 _/ ^  ^  ^  \
/  ^     ^    \
      __
     /  \_
    /^    \
   / ^     \_
 _/ ^  ^  ^  \
/  ^     ^    \
Done!
```

**Exercise 4.7: Countdown**

Ask how far away the target is. Count down `7 steps remaining`, `6 steps remaining`, … `1 steps remaining`, then print `Target achieved!`.

**Show solution**

```python
print("How far are we from the target?")
steps = int(input())
for remaining in range(steps, 0, -1):
    print(f"{remaining} steps remaining")
print("Target achieved!")
```

**Output**

```text
How far are we from the target?
4 ↵
4 steps remaining
3 steps remaining
2 steps remaining
1 steps remaining
Target achieved!
```

**Exercise 4.8: Brightness**

Ask for an even brightness level. Using `range(2, level + 1, 2)`, print `Brightness level: **`, `****`, … up to the level.

**Show solution**

```python
print("What level of brightness is required?")
level = int(input())
print("Adjusting brightness...")
for brightness in range(2, level + 1, 2):
    print("Brightness level: " + "*" * brightness)
print("Complete!")
```

**Output**

```text
What level of brightness is required?
6 ↵
Adjusting brightness...
Brightness level: **
Brightness level: ****
Brightness level: ******
Complete!
```

<a name="c4-looping-over-strings"></a>

### Looping over strings

A string is an ordered sequence of characters, each with a numbered **index** starting at **0**:

```text
 "H  e  l  l  o"
  0  1  2  3  4      index
 -5 -4 -3 -2 -1      negative index (from the end)
```

```python
word = "Hello"
print(word[0], word[1], word[-1], len(word))
```

**Output**

```text
H e o 5
```

You can loop by index, or directly over the characters:

```python
word = "Hello"
for position in range(len(word)):
    print(f"index {position}: {word[position]}")
for letter in word:
    print(letter, end=" ")
print()
```

**Output**

```text
index 0: H
index 1: e
index 2: l
index 3: l
index 4: o
H e l l o 
```

Use the index version when you need the position. When you only need the characters, `for letter in word` is simpler.

<a name="c4-membership-in-and-not-in"></a>

#### Membership: in and not in

```python
print("ell" in "Hello", "z" not in "Hello")
vowels = 0
for letter in "programming":
    if letter in "aeiou":
        vowels += 1
print(vowels, "vowels")
```

**Output**

```text
True True
3 vowels
```

**Exercise 4.9: Reverse a phrase**

Ask for a phrase and print it reversed using a `for` loop that counts **down** through the indexes: `sucoP sucoH` becomes `Hocus Pocus`.

**Show solution**

```python
print("What phrase do you want to see in reverse?")
phrase = input()
reversed_phrase = ""
for index in range(len(phrase) - 1, -1, -1):
    reversed_phrase += phrase[index]
print("Reversing...")
print(f"The phrase is: {reversed_phrase}")
```

**Output**

```text
What phrase do you want to see in reverse?
sucoP sucoH ↵
Reversing...
The phrase is: Hocus Pocus
```

The last index is `len(phrase) - 1`, and the stop value `-1` makes `0` the last index visited. (The shortcut `phrase[::-1]` does the same thing, but the lab wants the loop.)

<a name="c4-nested-loops"></a>

### Nested loops

A loop inside a loop: **for each** pass of the outer loop, the inner loop runs **all** of its passes.

```python
for row in range(3):
    for number in range(10):
        print(f"{number} |", end="")
    print()           # end the row: runs once per outer pass
```

**Output**

```text
0 |1 |2 |3 |4 |5 |6 |7 |8 |9 |
0 |1 |2 |3 |4 |5 |6 |7 |8 |9 |
0 |1 |2 |3 |4 |5 |6 |7 |8 |9 |
```

The inner `print(..., end="")` keeps the digits on one line. The final `print()` is indented to the **outer** loop's level, so it runs after each completed row.

**Exercise 4.10: Emoji grid**

Ask for a number of rows and columns and print a grid of `:-)`.

**Show solution**

```python
print("How many rows should I have?")
rows = int(input())
print("How many columns should I have?")
cols = int(input())
print("Here I go:")
for row in range(rows):
    for col in range(cols):
        print(":-)", end=" ")
    print()
print("Done!")
```

**Output**

```text
How many rows should I have?
2 ↵
How many columns should I have?
3 ↵
Here I go:
:-) :-) :-) 
:-) :-) :-) 
Done!
```

**Exercise 4.11: Distance between markers**

Ask for a sequence like `--x---x--` and the marker character `x`. Print how many characters lie between the two markers (here `3`).

**Show solution**

```python
print("Please enter a sequence")
sequence = input()
print("Please enter the character for the marker")
marker = input()

positions = []
for index in range(len(sequence)):
    if sequence[index] == marker:
        positions.append(index)        # remember where each marker is

distance = positions[1] - positions[0] - 1
print(f"The distance between the markers is {distance}.")
```

**Output**

```text
Please enter a sequence
--x---x-- ↵
Please enter the character for the marker
x ↵
The distance between the markers is 3.
```

`positions` is a **list**, which Chapter 6 covers properly. Here it just collects the two indexes. Another approach is a counter that starts counting after the first marker and stops at the second.

<a name="c4-break-and-continue"></a>

### break and continue

- `break` leaves the loop it is in, immediately.
- `continue` skips the rest of this pass and goes on to the next one.

```python
for n in range(1, 10):
    if n % 2 == 0:
        continue          # skip even numbers
    if n > 7:
        break             # stop completely
    print(n, end=" ")
print()
```

**Output**

```text
1 3 5 7 
```

**Checkpoint 4**

1.  How many times does `for i in range(2, 11, 2):` run, and what is `i` on the last pass?
2.  What does `list(range(3, 0, -1))` give?
3.  What is printed? `total = 0`, then `for n in range(4): total += n`, then `print(total)`
4.  Inner loop 3 passes, outer loop 4 passes. How many times does the inner body run?
5.  `n = 1` then `while n < 20: n = n * 3`. Final value of `n`?

**Answers**

1.  5 times (2, 4, 6, 8, 10); the last `i` is `10`.
2.  `[3, 2, 1]`
3.  `6` (0 + 1 + 2 + 3)
4.  12
5.  `27` (1 → 3 → 9 → 27; the check `27 < 20` fails, so the loop ends)

<a name="c4-summary"></a>

### Summary

- `while condition:` repeats while the condition holds; change the control variable inside, or use `while True:` with `break`.
- `for x in range(start, stop, step):` repeats a known number of times; `stop` is excluded; a negative step counts down.
- `for ch in text:` visits every character; `text[i]` reads one by index from `0` to `len(text) - 1`.
- Counters (`+= 1`) and accumulators (`+= value`) start at zero before the loop.
- Nested loops multiply: the inner loop completes fully for each outer pass.

<a name="c5-functions-and-modules"></a>

## Chapter 5: Functions and modules

**Goals:** use built-in functions; define your own with `def`; pass information in with parameters; get results back with `return`; understand scope; split a program into modules and import them; protect code with `if __name__ == "__main__":`.

<a name="c5-why-functions"></a>

### Why functions

A **function** is a named, reusable block of code that does one job. Functions give you:

- **reuse:** write once, call as many times as you like;
- **abstraction:** you can call `print` without knowing how it draws text on the screen, and once your own functions work, you can use them without re-reading their insides;
- **structure:** a 300-line program becomes ten readable 30-line pieces, each testable on its own.

The AE2 marking criteria explicitly reward "logically breaking code into reusable functions" with "very good use of parameters and return values". This chapter is the foundation for that.

<a name="c5-built-in-functions"></a>

### Built-in functions

You already use built-ins: `print`, `input`, `int`, `float`, `str`, `len`, `range`. Python has about 70. A few more you will need:

```python
print(abs(-7), round(3.14159, 2), min(4, 9, 2), max(4, 9, 2))
print(ord("a"), chr(97))           # character <-> code number
print(type(3.0), isinstance(3, int))
```

**Output**

```text
7 3.14 2 9
97 a
<class 'float'> True
```

**ASCII** (American Standard Code for Information Interchange) gives each character a number: `A` is 65, `a` is 97, a space is 32. The printable characters run from 32 to 126. `ord` converts a character to its code and `chr` converts a code back.

**Exercise 5.1: ASCII code of a character**

Print `Program Started!`, ask for a single character, and if exactly one character was entered (check with `len`), print `The ASCII code for t is 116.`. Otherwise print an error. Finish with `Program Ended!`.

**Show solution**

```python
print("Program Started!")
print("Please enter a standard character:")
letter = input()
if len(letter) == 1:
    print(f"The ASCII code for {letter} is {ord(letter)}.")
else:
    print("Error! Please enter exactly one character.")
print("Program Ended!")
```

**Output**

```text
Program Started!
Please enter a standard character:
t ↵
The ASCII code for t is 116.
Program Ended!
```

**Exercise 5.2: Character from an ASCII code**

Ask for a code, make it positive with `abs()`, and if it is in `range(32, 127)` print the character it represents. Otherwise print an error.

**Show solution**

```python
print("Program Started!")
print("Please enter an ASCII code:")
code = abs(int(input()))
if code in range(32, 127):
    print(f"The character represented by the ASCII code {code} is {chr(code)}.")
else:
    print("Error! That code is not a printable character.")
print("Program Ended!")
```

**Output**

```text
Program Started!
Please enter an ASCII code:
109 ↵
The character represented by the ASCII code 109 is m.
Program Ended!
```

<a name="c5-defining-a-function"></a>

### Defining a function

```python
# The function definition: nothing happens yet
def greet_user():
    print("Please enter your name")
    name = input()
    print("Hello", name)


# The call: now it runs
greet_user()
```

**Output**

```text
Please enter your name
Ada ↵
Hello Ada
```

- `def` starts a definition, followed by the function's name, brackets and a colon.
- The indented block is the **body**.
- **Defining a function does not run it.** Code inside runs only when the function is **called** by its name with brackets. Forgetting the call, or writing `greet_user` without `()`, is the most common reason "nothing happens".
- PEP-8: two blank lines before and after each top-level function; function names in `snake_case`.

**Exercise 5.3: Cave sounds**

Define `listen()`, which asks `What sound did you hear?` and replies `That was a loud rumble!` (using the word typed). Then define `identify()`, which asks `What lies before us?` and prints `It's time to run!` if the answer is `a large boulder`, otherwise `We will be fine.`. Call both.

**Show solution**

```python
def listen():
    print("What sound did you hear?")
    sound = input()
    print(f"That was a loud {sound}!")


def identify():
    print("What lies before us?")
    thing = input()
    if thing == "a large boulder":
        print("It's time to run!")
    else:
        print("We will be fine.")


listen()
identify()
```

**Output**

```text
What sound did you hear?
rumble ↵
That was a loud rumble!
What lies before us?
a large boulder ↵
It's time to run!
```

<a name="c5-parameters-and-arguments"></a>

### Parameters and arguments

A **parameter** is a variable named in the `def` line. It receives a value when the function is called. The value you pass in the call is the **argument**.

```python
def escape_by(plan):                      # plan is a PARAMETER
    if plan == "jumping over":
        print("We cannot escape that way! The boulder is too big!")
    elif plan == "running around":
        print("We cannot escape that way! The boulder is moving too fast!")
    elif plan == "cross bridge ahead":
        print("That might just work! Let's go!")
    else:
        print("We cannot escape that way! The boulder is in the way!")


escape_by("jumping over")                 # "jumping over" is an ARGUMENT
escape_by("running around")
escape_by("cross bridge ahead")
```

**Output**

```text
We cannot escape that way! The boulder is too big!
We cannot escape that way! The boulder is moving too fast!
That might just work! Let's go!
```

With several parameters, arguments are matched **by position**, or **by name** if you write `name=value`:

```python
def climb_ladder(remaining, crossed):
    if remaining > crossed:
        print("Still some way to go!")
    else:
        print("We are almost there!")


climb_ladder(5, 2)
climb_ladder(crossed=5, remaining=2)
```

**Output**

```text
Still some way to go!
We are almost there!
```

**Exercise 5.4: Crossing the bridge**

Define `cross_bridge(steps)`, which prints `Crossed step.` once per step and then, if `steps` is more than 5, `The bridge is collapsing!`, otherwise `We must keep going!`. Call it with 3 and with 6.

**Show solution**

```python
def cross_bridge(steps):
    for step in range(steps):
        print("Crossed step.")
    if steps > 5:
        print("The bridge is collapsing!")
    else:
        print("We must keep going!")


cross_bridge(3)
cross_bridge(6)
```

**Output**

```text
Crossed step.
Crossed step.
Crossed step.
We must keep going!
Crossed step.
Crossed step.
Crossed step.
Crossed step.
Crossed step.
Crossed step.
The bridge is collapsing!
```

<a name="c5-default-values"></a>

#### Default values

A parameter can have a default, which is used when the caller leaves that argument out. Parameters with defaults must come **after** those without.

```python
def started(msg=""):
    print("-" * 40)
    print(f"Operation started: {msg}...")


started("Reading data from file.csv")
started()
```

**Output**

```text
----------------------------------------
Operation started: Reading data from file.csv...
----------------------------------------
Operation started: ...
```

<a name="c5-return-getting-a-result-back"></a>

### return: getting a result back

`print` shows a value to the **user**. `return` gives a value back to the **code that called the function**, which can store it, test it, or pass it on. When `return` runs, the function ends immediately.

```python
def get_name():
    print("Please enter your name")
    name = input()
    return name


user = get_name()                 # the call is replaced by the returned value
print("Retrieved name:", user.upper())
```

**Output**

```text
Please enter your name
Ada ↵
Retrieved name: ADA
```

**return vs print, in memory**

A function that only prints still returns something: the special value `None`. Look at this:

```python
def add_print(a, b):
    print(a + b)


def add_return(a, b):
    return a + b


x = add_print(2, 3)
y = add_return(2, 3)
print("x is", x, "and y is", y)
```

**Output**

```text
5
x is None and y is 5
```

`x` is `None` because `add_print` never handed anything back. If a task says "the function should **return** the list", printing inside it gets no marks and breaks any code that relies on the returned value. Functions that compute should usually *return*, and only the code that talks to the user should *print*. AE2 is structured exactly that way: `tui.py` handles input and output, `process.py` computes and returns.

```python
def sum_weights(person, inventory):
    return person + inventory


def calc_avg_weight(person, inventory):
    total = sum_weights(person, inventory)      # one function using another
    return total / 2


print(sum_weights(12, 6), calc_avg_weight(12, 6))
```

**Output**

```text
18 9.0
```

**Exercise 5.5: Weights**

Write `sum_weights(person, inventory)` and `calc_avg_weight(person, inventory)` as above, and a third function `run()` that asks for the two weights, then asks `sum` or `average`, and prints `The sum of weights is 18.` or the average. Call `run()` at the bottom.

**Show solution**

```python
def sum_weights(person, inventory):
    return person + inventory


def calc_avg_weight(person, inventory):
    return sum_weights(person, inventory) / 2


def run():
    print("What is the weight of the person?")
    person = float(input())
    print("What is the weight of their inventory?")
    inventory = float(input())
    print("What would you like to calculate (sum or average)?")
    choice = input()
    if choice == "sum":
        print(f"The sum of weights is {sum_weights(person, inventory):g}.")
    elif choice == "average":
        print(f"The average weight is {calc_avg_weight(person, inventory):g}.")
    else:
        print("Unknown option.")


# Run the program
run()
```

**Output**

```text
What is the weight of the person?
12 ↵
What is the weight of their inventory?
6 ↵
What would you like to calculate (sum or average)?
sum ↵
The sum of weights is 18.
```

`:g` prints a number without a pointless `.0`.

<a name="c5-functions-calling-functions"></a>

#### Functions calling functions

```python
def display_box(name):
    message = f"* Hello {name} *"
    print("*" * len(message))
    print(message)
    print("*" * len(message))


def greet_user():
    print("Please enter your name")
    name = input()
    display_box(name)


greet_user()
```

**Output**

```text
Please enter your name
Ada ↵
*************
* Hello Ada *
*************
```

When `greet_user` calls `display_box`, Python pauses `greet_user`, runs `display_box` to the end, then carries on in `greet_user` right after the call. This is the **call stack**. The free online *Python Tutor* visualiser animates it, and the module recommends it.

**Exercise 5.6: Ladder**

Write `display_ladder(steps)`, which draws an ASCII ladder with that many steps, and `create_ladder()`, which asks `How many steps remain?` and calls `display_ladder`. Call `create_ladder()`.

**Show solution**

```python
def display_ladder(steps):
    for step in range(steps):
        print("| |")
        print("***")
    print("| |")


def create_ladder():
    print("How many steps remain?")
    steps = int(input())
    display_ladder(steps)


create_ladder()
```

**Output**

```text
How many steps remain?
3 ↵
| |
***
| |
***
| |
***
| |
```

**Exercise 5.7: Word manipulation (six functions)**

Ask for a word and then an option 1–5:

1.  display it in an ASCII box;
2.  lower-case;
3.  upper-case;
4.  mirrored (`Hello | olleH`);
5.  ask how many times to repeat it, then print it that many times alternating upper and lower case.

Write one function per option plus `run()`.

**Show solution**

```python
def display_in_box(word):
    print("*" * (len(word) + 4))
    print(f"* {word} *")
    print("*" * (len(word) + 4))


def display_lower(word):
    print(word.lower())


def display_upper(word):
    print(word.upper())


def display_mirrored(word):
    print(f"{word} | {word[::-1]}")


def repeat(word):
    print("How many times?")
    times = int(input())
    for i in range(times):
        if i % 2 == 0:
            print(word.upper())
        else:
            print(word.lower())


def run():
    print("Please enter a word:")
    word = input()
    print("1) Display in a Box  2) Lower-case  3) Upper-case  4) Mirrored  5) Repeat")
    option = int(input())
    if option == 1:
        display_in_box(word)
    elif option == 2:
        display_lower(word)
    elif option == 3:
        display_upper(word)
    elif option == 4:
        display_mirrored(word)
    elif option == 5:
        repeat(word)
    else:
        print("Unknown option.")


run()
```

**Output**

```text
Please enter a word:
Hello ↵
1) Display in a Box  2) Lower-case  3) Upper-case  4) Mirrored  5) Repeat
5 ↵
How many times?
4 ↵
HELLO
hello
HELLO
hello
```

<a name="c5-scope-where-a-variable-exists"></a>

### Scope: where a variable exists

A variable created **inside** a function is **local**: it exists only while that function runs and is invisible outside it.

```python
def make_total():
    total = 99


make_total()
print(total)
```

**Output (error)**

```text
Traceback (most recent call last):
  File "main.py", line 6, in <module>
    ...
NameError: name 'total' is not defined
```

A variable created at the top level of the file is **global**. Functions can *read* globals, and can *change the contents* of a global list or dictionary, but to *reassign* a global name you must declare it with `global`:

```python
count = 0            # global


def increase():
    global count     # without this line: UnboundLocalError
    count += 1


increase()
increase()
print(count)
```

**Output**

```text
2
```

**Prefer parameters and return values**

Globals make functions depend on hidden state, which makes them harder to test and reuse. The cleaner design passes data **in** as parameters and gets results **out** with `return`. The Titanic case study (Chapter 12) uses globals because the spec asks for them, but the Olympics study shows the better style.

<a name="c5-docstrings"></a>

### Docstrings

A string on the first line of a function body documents what the function does. PyCharm shows it when you hover over a call.

```python
def area(width, height):
    """Return the area of a width x height rectangle."""
    return width * height


print(area(3, 4))
print(area.__doc__)
```

**Output**

```text
12
Return the area of a width x height rectangle.
```

<a name="c5-modules"></a>

### Modules

A **module** is simply a `.py` file. Python ships with a large **standard library** of modules. You load one with `import`:

```python
import random                       # whole module; use random.name
import random as rnd                # same module, shorter name
from random import randrange        # just one function, used without a prefix

print(random.randint(1, 6), rnd.randint(1, 6), randrange(1, 7))
```

**Output**

```text
3 2 4
```

`random.randint(a, b)` includes **both** ends. `randrange(a, b)` excludes `b`, just like `range`.

**Exercise 5.8: Guess the number**

Ask for a minimum and maximum, pick a random number between them, and repeatedly read guesses, saying `Your guess is too low.` / `Your guess is too high.` and `Try again:` until the guess is right, then print `Congratulations! You guessed my number!`. When it works, wrap it in a function `play_guess_the_number()`.

**Show solution**

```python
import random


def play_guess_the_number():
    print("Please enter the minimum value:")
    minimum = int(input())
    print("Please enter the maximum value:")
    maximum = int(input())
    secret = random.randint(minimum, maximum)
    print(f"I am thinking of a number between {minimum} and {maximum}. Can you guess what it is?")
    guess = int(input())
    while guess != secret:
        if guess < secret:
            print("Your guess is too low.")
        else:
            print("Your guess is too high.")
        print("Try again:")
        guess = int(input())
    print("Congratulations! You guessed my number!")


play_guess_the_number()
```

**Output**

```text
Please enter the minimum value:
1 ↵
Please enter the maximum value:
10 ↵
I am thinking of a number between 1 and 10. Can you guess what it is?
2 ↵
Your guess is too low.
Try again:
9 ↵
Your guess is too high.
Try again:
6 ↵
Congratulations! You guessed my number!
```

<a name="c5-your-own-modules"></a>

#### Your own modules

Any `.py` file in the same folder can be imported by its name without the `.py`. Here are two files that work together:

File: greetings.py

```python
"""Functions for greeting the user."""


def simple_message():
    print("Welcome to QHO444!")


def farewell(name):
    return f"Goodbye, {name}!"


# Only runs when greetings.py itself is run, not when it is imported
if __name__ == "__main__":
    simple_message()
```

File: main.py

```python
import greetings

greetings.simple_message()
print(greetings.farewell("Ada"))
```

**Output**

```text
Welcome to QHO444!
Goodbye, Ada!
```

**What \`if \_\_name\_\_ == "\_\_main\_\_":\` does**

Every module has a hidden variable `__name__`. When you **run** a file, Python sets its `__name__` to `"__main__"`. When a file is **imported**, its `__name__` is the module's name (`"greetings"`). Importing a file runs all of its top-level code. So without this guard, `import greetings` would also execute whatever test calls you left at the bottom of `greetings.py`. With the guard, each file can contain its own quick tests and still be imported cleanly.

Modules can live in sub-folders (packages). `import week1.output_tasks as wk1_output` loads `week1/output_tasks.py` when you run from the project root.

<a name="c5-putting-it-together-a-menu-program"></a>

### Putting it together: a menu program

This is the shape the Olympics case study and AE2 both use: a loop that shows a menu, reads a choice, calls the matching function, and stops on exit.

File: menu_demo.py

```python
def show_menu():
    print("What would you like to do?")
    print("[a] Say hello")
    print("[q] Quit")
    return input()


def say_hello():
    print("Hello!")


def run():
    while True:
        response = show_menu()
        if response == "a":
            say_hello()
        elif response == "q":
            break
        else:
            print("Invalid option! Please try again.")


if __name__ == "__main__":
    run()
```

**Output**

```text
What would you like to do?
[a] Say hello
[q] Quit
a ↵
Hello!
What would you like to do?
[a] Say hello
[q] Quit
z ↵
Invalid option! Please try again.
What would you like to do?
[a] Say hello
[q] Quit
q ↵
```

**Exercise 5.9: Run any earlier program from a menu**

Wrap a few earlier exercises in functions inside a module (e.g. `week1/output_tasks.py` gets `simple_message()`, `ascii_robot()`), add the `__main__` guard to each file, and write a `main.py` at the project root with a menu like the one above that imports and runs them.

**Checkpoint 5**

1.  What does this print? `def f(x): x = x * 2` then `y = f(4)` then `print(y)`
2.  True or false: defining a function runs its body once.
3.  `def g(a, b=10): return a - b`. What are `g(15)` and `g(15, 5)` and `g(b=1, a=3)`?
4.  Which line makes this work: `n = 0` / `def bump(): n += 1`?
5.  What is `__name__` inside a file that has been imported as `import tools`?

**Answers**

1.  `None`. There is no `return`.
2.  False. Only calling it runs the body.
3.  `5`, `10`, `2`
4.  Add `global n` as the first line inside `bump` (or, better, rewrite it to take `n` and return `n + 1`).
5.  `"tools"`

<a name="c5-summary"></a>

### Summary

- `def name(params):` defines; `name(args)` calls. Nothing runs until it is called.
- Parameters receive arguments by position or by name; defaults go last.
- `return value` hands a result back and ends the function; without it the function returns `None`.
- Variables made inside a function are local; reassigning a global needs `global` (avoid it where you can).
- A module is a `.py` file. `import x`, `import x as y` and `from x import f` all load one. `if __name__ == "__main__":` keeps test code from running on import.

<a name="c6-lists-and-tuples"></a>

## Chapter 6: Lists and tuples

**Goals:** understand what a data structure is; create, read, change and loop over lists; build lists inside loops; use tuples for fixed records and for returning several values; nest lists and tuples; sort.

<a name="c6-data-structures"></a>

### Data structures

So far each variable has held one value. A **data structure** holds many values organised in a particular way, and comes with operations for working on them. Python's four built-in ones:

| Structure | Brackets | Ordered?        | Changeable? | Duplicates? | Chapter  |
|-----------|----------|-----------------|-------------|-------------|----------|
| list      | `[ ]`    | yes             | yes         | yes         | this one |
| tuple     | `( )`    | yes             | **no**      | yes         | this one |
| set       | `{ }`    | no              | yes         | **no**      | 8        |
| dict      | `{k: v}` | yes (insertion) | yes         | keys no     | 8        |

"Ordered" means items keep their position, so you can ask for the first or third one. This chapter covers the ordered pair.

<a name="c6-lists"></a>

### Lists

```python
fruits = []                                 # an empty list
fruits = ["apple", "banana", "cherry"]      # a list with three items
mixed = ["apple", 5, 2.5, True]             # any types, mixed (heterogeneous)
print(fruits, len(fruits), mixed)
```

**Output**

```text
['apple', 'banana', 'cherry'] 3 ['apple', 5, 2.5, True]
```

<a name="c6-indexing-and-slicing"></a>

#### Indexing and slicing

Lists are indexed from 0, exactly like strings:

```python
fruits = ["apple", "banana", "cherry", "date"]
print(fruits[0])           # first
print(fruits[-1])          # last
print(fruits[1:3])         # slice: index 1 up to (not including) 3
print(fruits[:2], fruits[2:])
```

**Output**

```text
apple
date
['banana', 'cherry']
['apple', 'banana'] ['cherry', 'date']
```

Unlike strings, lists are **mutable**: you can change them in place.

```python
fruits = ["apple", "banana", "cherry"]
fruits[1] = "berry"          # replace an item
fruits.append("dragon fruit")  # add to the end
fruits.insert(0, "kiwi")     # add at a position
fruits.remove("cherry")      # remove the first matching VALUE
del fruits[0]                # remove by INDEX
last = fruits.pop()          # remove the last item and give it back
print(fruits, last)
```

**Output**

```text
['apple', 'berry'] dragon fruit
```

**Exercise 6.1: Directions**

Write `directions()`, which creates a list `steps` containing `"Move Forward"`, `"Move Backward"`, `"Turn Left"` and `"Turn Right"` and **returns** it. Write `run_task1()`, which calls it and prints the list. Use the `__main__` guard.

**Show solution**

```python
def directions():
    steps = ["Move Forward", "Move Backward", "Turn Left", "Turn Right"]
    return steps


def run_task1():
    print(directions())


if __name__ == "__main__":
    run_task1()
```

**Output**

```text
['Move Forward', 'Move Backward', 'Turn Left', 'Turn Right']
```

**Exercise 6.2: Movements**

`movements()` returns the list `["Move Forward", 10, "Move Backward", 5, "Move Left", 3, "Move Right", 1]`. `run_task2()` prints `Moving...` and then `Move Forward for 10 steps` and so on, reading the items in pairs.

**Show solution**

```python
def movements():
    path = ["Move Forward", 10, "Move Backward", 5, "Move Left", 3, "Move Right", 1]
    return path


def run_task2():
    print("Moving...")
    path = movements()
    for index in range(0, len(path), 2):          # 0, 2, 4, 6
        print(f"{path[index]} for {path[index + 1]} steps")


run_task2()
```

**Output**

```text
Moving...
Move Forward for 10 steps
Move Backward for 5 steps
Move Left for 3 steps
Move Right for 1 steps
```

Storing pairs side by side in one flat list is awkward. A list of **tuples** (later in this chapter) is the cleaner design.

<a name="c6-looping-over-a-list"></a>

#### Looping over a list

```python
fruits = ["apple", "banana", "cherry"]
for fruit in fruits:                          # when you only need items
    print(fruit)
for index in range(len(fruits)):              # when you need positions too
    print(f"{fruits[index]} is at index {index}.")
for index, fruit in enumerate(fruits):        # both, neatly
    print(index, fruit)
```

**Output**

```text
apple
banana
cherry
apple is at index 0.
banana is at index 1.
cherry is at index 2.
0 apple
1 banana
2 cherry
```

<a name="c6-building-a-list-in-a-loop"></a>

#### Building a list in a loop

Start empty, `append` inside the loop. This is one of the most common patterns in the module.

```python
def directions():
    return ["Move Forward", "Move Backward", "Turn Left", "Turn Right"]


def menu_and_input():
    print("Please select a direction:")
    options = directions()
    for index in range(len(options)):
        print(f"{index}: {options[index]}")
    choice = int(input())
    return options[choice]


def run_task4():
    route = []
    print("Working out escape route...")
    for step in range(5):
        route.append(menu_and_input())
    print(f"Escape route: {route}")


run_task4()
```

**Output**

```text
Working out escape route...
Please select a direction:
0: Move Forward
1: Move Backward
2: Turn Left
3: Turn Right
0 ↵
Please select a direction:
0: Move Forward
1: Move Backward
2: Turn Left
3: Turn Right
0 ↵
Please select a direction:
0: Move Forward
1: Move Backward
2: Turn Left
3: Turn Right
2 ↵
Please select a direction:
0: Move Forward
1: Move Backward
2: Turn Left
3: Turn Right
0 ↵
Please select a direction:
0: Move Forward
1: Move Backward
2: Turn Left
3: Turn Right
3 ↵
Escape route: ['Move Forward', 'Move Forward', 'Turn Left', 'Move Forward', 'Turn Right']
```

This is Exercise 6.3/6.4 from the module, solved above as a worked example. Type it out and then extend it: reject numbers outside 0–3 instead of crashing.

<a name="c6-useful-list-operations"></a>

#### Useful list operations

```python
nums = [5, 3, 8, 3, 1]
print(len(nums), sum(nums), min(nums), max(nums))
print(8 in nums, nums.count(3), nums.index(8))
print(sorted(nums))                   # a NEW sorted list
print(sorted(nums, reverse=True))
nums.sort()                           # sorts nums itself, returns None
print(nums)
```

**Output**

```text
5 20 1 8
True 2 2
[1, 3, 3, 5, 8]
[8, 5, 3, 3, 1]
[1, 3, 3, 5, 8]
```

**\`x = x.sort()\` destroys your list**

`sort()` changes the list in place and returns `None`, so `nums = nums.sort()` leaves you holding `None`. Use either `nums.sort()` on its own line, or `nums = sorted(nums)`.

**Mutability and aliasing**

Assigning a list to another name does **not** copy it. Both names label the *same* list object:

```python
a = [1, 2, 3]
b = a              # b is another label on the same list
b.append(4)
print(a)           # a "changed" too: it is the same list
c = a.copy()       # a genuine second list
c.append(5)
print(a, c)
print(a is b, a is c)
```

**Output**

```text
[1, 2, 3, 4]
[1, 2, 3, 4] [1, 2, 3, 4, 5]
True False
```

This is also why a function can change a list you pass to it: the parameter is just another label on your list. Strings, numbers and tuples are **immutable**, so this surprise can't happen with them. Any "change" makes a new object.

<a name="c6-tuples"></a>

### Tuples

A tuple is an ordered collection that **cannot be changed** after it is made. Create one with round brackets:

```python
person = ("Bob", 40, "Lecturer")
print(person[0], len(person))
temperatures = (19, 23, 21, 21, 20, 18, 22)
print(temperatures + (20, 21))        # concatenation makes a NEW tuple
print(min(temperatures), max(temperatures), 20 in temperatures)
```

**Output**

```text
Bob 3
(19, 23, 21, 21, 20, 18, 22, 20, 21)
18 23 True
```

```python
person = ("Bob", 40, "Lecturer")
person[1] = 41
```

**Output (error)**

```text
Traceback (most recent call last):
  File "main.py", line 2, in <module>
    ...
TypeError: 'tuple' object does not support item assignment
```

**Why use something that can't change?** Because a fixed record (a coordinate, a date, a name-and-score pair) *shouldn't* change by accident. Immutable data is easier to reason about. Tuples can also be used where lists can't, such as dictionary keys and set members.

<a name="c6-unpacking-and-returning-several-values"></a>

#### Unpacking and returning several values

```python
point = (3, 5)
x, y = point                       # unpacking
print(x, y)


def likelihood_min_max():
    likelihoods = (50, 38, 27, 99, 4)
    return min(likelihoods), max(likelihoods)      # returns ONE tuple


low, high = likelihood_min_max()
print(f"Minimum likelihood of falling: {low}%")
print(f"Maximum likelihood of falling: {high}%")
```

**Output**

```text
3 5
Minimum likelihood of falling: 4%
Maximum likelihood of falling: 99%
```

<a name="c6-lists-of-tuples"></a>

#### Lists of tuples

A list of small tuples is the natural shape for a table of records:

```python
def steps():
    return [("step 1", 50), ("step 2", 38), ("step 3", 27), ("step 4", 99), ("step 5", 4)]


def run_task3():
    good_steps = []
    bad_steps = []
    for step in steps():
        name, chance = step                 # unpack each record
        if chance >= 50:
            bad_steps.append(step)
        else:
            good_steps.append(step)
    print(f"Good steps: {len(good_steps)}, Bad steps: {len(bad_steps)}")


run_task3()
```

**Output**

```text
Good steps: 3, Bad steps: 2
```

You can unpack directly in the loop header: `for name, chance in steps():`.

<a name="c6-sorting-records-with-a-key"></a>

#### Sorting records with a key

`sorted` can sort by any part of each item if you give it a **key function**. A `lambda` is a tiny unnamed function written inline:

```python
records = [("step 1", 50), ("step 2", 38), ("step 5", 4)]
print(sorted(records, key=lambda record: record[1]))           # by chance
print(sorted(records, key=lambda record: record[1], reverse=True))
```

**Output**

```text
[('step 5', 4), ('step 2', 38), ('step 1', 50)]
[('step 1', 50), ('step 2', 38), ('step 5', 4)]
```

`lambda record: record[1]` means "given a record, use its second item". It is the same as `def by_chance(record): return record[1]` written in one line.

<a name="c6-nested-lists"></a>

### Nested lists

A list can contain lists, which is how rows from a CSV file arrive (Chapter 7):

```python
table = [
    ["id", "name", "colour"],
    ["1", "Shirt", "Mercury"],
    ["2", "Coat", "Boulder"],
]
print(table[1])          # a whole row
print(table[1][1])       # row 1, column 1
for row in table[1:]:    # skip the heading row
    print(row[1])
```

**Output**

```text
['1', 'Shirt', 'Mercury']
Shirt
Shirt
Coat
```

**Exercise 6.3: Shopping list**

Write `get_items(count)`, which asks for `count` items and returns them as a list; `show(items)`, which prints them numbered from 1; and `run()`, which gets 3 items, removes one the user names (if present), and shows the result sorted.

**Show solution**

```python
def get_items(count):
    items = []
    for i in range(count):
        print(f"Item {i + 1}:")
        items.append(input())
    return items


def show(items):
    for number, item in enumerate(items, start=1):
        print(f"{number}. {item}")


def run():
    items = get_items(3)
    print("Which item should I remove?")
    unwanted = input()
    if unwanted in items:
        items.remove(unwanted)
    else:
        print(f"{unwanted} is not on the list.")
    show(sorted(items))


run()
```

**Output**

```text
Item 1:
milk ↵
Item 2:
eggs ↵
Item 3:
bread ↵
Which item should I remove?
eggs ↵
1. bread
2. milk
```

**Checkpoint 6**

1.  `a = [10, 20, 30]`. What is `a[-1] + a[0]`?
2.  `a = [1, 2]`, `b = a`, `b.append(3)`. What is `len(a)`?
3.  What is printed by `print([3, 1, 2].sort())`?
4.  `t = (5,)` and `u = (5)`. What are `type(t)` and `type(u)`?
5.  `nums = [4, 7, 1]`. What is `sorted(nums, reverse=True)[0]`?
6.  `pairs = [("a", 3), ("b", 1)]`. What does `sorted(pairs, key=lambda p: p[1])[0][0]` give?

**Answers**

1.  `40`
2.  `3`. `a` and `b` are the same list.
3.  `None`
4.  `tuple` and `int`. The comma makes the tuple.
5.  `7`
6.  `"b"`

<a name="c6-summary"></a>

### Summary

- Lists `[]` are ordered and mutable: index, slice, `append`, `insert`, `remove`, `pop`, `del`, `sort`.
- Build a list by starting with `[]` and appending inside a loop.
- `sorted()` returns a new list; `.sort()` changes the list and returns `None`.
- Assigning a list to a second name doesn't copy it; use `.copy()`.
- Tuples `()` are ordered and immutable; use them for fixed records and for returning several values (`return a, b` → `x, y = f()`).
- A list of tuples is a simple table; sort it with `key=lambda item: item[i]`.

<a name="c7-files-text-and-csv"></a>

## Chapter 7: Files: text and CSV

**Goals:** understand files, folders and paths; find the current working directory; read text files whole, in pieces and line by line; write and append; read CSV files with the `csv` module; convert CSV values to numbers; handle files that might not exist.

<a name="c7-files-folders-and-paths"></a>

### Files, folders and paths

Variables disappear when a program ends. **Files** keep data after the program finishes. Files live in **folders** (directories) arranged as a tree:

```text
data                     <- a folder
├── staff                <- a sub-folder
│   ├── prins.txt
│   └── prins.png
└── students
    └── attendance.csv
```

A **path** says where a file is.

- An **absolute path** starts at the top of the file system: `/home/ada/data/staff/prins.txt` on Linux or macOS, `C:/Users/ada/data/staff/prins.txt` on Windows.
- A **relative path** starts from the program's **current working directory** (cwd). If the cwd is `data/staff`, then `prins.txt` (or `./prins.txt`) is that file, and `../students/attendance.csv` goes up one level and then into `students`.

| Symbol | Meaning                                               |
|--------|-------------------------------------------------------|
| `.`    | the current folder                                    |
| `..`   | the parent folder                                     |
| `/`    | separator between folder names (works on Windows too) |

```python
import os

path = os.getcwd()
print(f"The current working directory is {path}")
print("The directory contains the following files:")
for name in os.listdir(path):
    print(name)
```

**"FileNotFoundError" but the file is right there**

Relative paths are resolved from the **cwd**, which is not necessarily the folder your script is in. Print `os.getcwd()` to see where Python is looking. In PyCharm, the cwd is set in *Run → Edit Configurations → Working directory*. It usually matches the script's folder, but not always.

<a name="c7-file-formats-you-will-meet"></a>

### File formats you will meet

| Format        | What it looks like                                                        | Read with                     |
|---------------|---------------------------------------------------------------------------|-------------------------------|
| **TXT**       | plain lines of text                                                       | `open()`                      |
| **CSV**       | comma-separated values, one record per line, usually a heading line first | the `csv` module              |
| **JSON**      | nested `{key: value}` and `[lists]`                                       | the `json` module (Chapter 8) |
| images, audio | binary data, not text                                                     | `open(path, "rb")`            |

<a name="c7-opening-and-closing"></a>

### Opening and closing

`open(path, mode)` returns a **file object**. The mode says what you want to do:

| Mode      | Meaning                                                |
|-----------|--------------------------------------------------------|
| `"r"`     | read (the default). The file must exist.               |
| `"w"`     | write. Creates the file, or **wipes** an existing one. |
| `"a"`     | append. Creates the file, or adds to the end.          |
| `"x"`     | create. Fails if the file already exists.              |
| add `"b"` | binary, e.g. `"rb"`, `"wb"`                            |

A file must be **closed** when you are done, to release it and make sure written data is saved. The `with` statement closes it for you, even if an error happens:

```python
file = open("library.txt")       # manual way
print(file.readline())
file.close()

with open("library.txt") as file:    # preferred: closes automatically
    print(file.readline())
```

**Output**

```text
The Law Section

The Law Section
```

<a name="c7-reading-text"></a>

### Reading text

```python
with open("library.txt") as file:
    first_five = file.read(5)          # a number of characters
print(repr(first_five))

with open("library.txt") as file:
    first_line = file.readline()       # one line, INCLUDING its \n
print(repr(first_line), repr(first_line.strip()))

with open("library.txt") as file:
    everything = file.read()           # the whole file as one string
print(everything.split("\n"))
```

**Output**

```text
'The L'
'The Law Section\n' 'The Law Section'
['The Law Section', 'The Art Section', 'The Technology Section', 'The History Section', '']
```

`repr()` shows the hidden characters. Every line read from a file ends in `\n`, so `.strip()` removes it (along with any spaces at either end).

<a name="c7-line-by-line"></a>

#### Line by line

A file object is iterable, so a `for` loop gives you one line at a time. This is the normal way to process a file:

```python
print("Searching...")
with open("library.txt") as file:
    for line in file:
        print(f"Looked in {line.strip()}")
print("...Done!")
```

**Output**

```text
Searching...
Looked in The Law Section
Looked in The Art Section
Looked in The Technology Section
Looked in The History Section
...Done!
```

**Why line-by-line is better for big files**

`file.read()` loads the entire file into memory. A `for line in file:` loop reads one line, hands it to you, then reads the next. A 10-gigabyte log file processes fine that way. The file object keeps track of a **position**, so after one `read()` or full loop, a second `read()` returns `""` because you are already at the end. Re-open the file, or call `file.seek(0)`, to start again.

**Exercise 7.1: Library sections**

Create `library.txt` with four lines (`The Law Section`, `The Art Section`, `The Technology Section`, `The History Section`). Write `display_chars(path, n)`, `display_line(path)` and `display_text(path)`, which show the first n characters, the first line, and all the text. Then write `run_task2()` to call all three.

**Show solution**

```python
def display_chars(file_path, count):
    with open(file_path) as file:
        print(f"The first {count} characters are:")
        print(file.read(count))


def display_line(file_path):
    with open(file_path) as file:
        print("The first line is:")
        print(file.readline().strip())


def display_text(file_path):
    with open(file_path) as file:
        print("The full text is:")
        print(file.read())


def run_task2():
    display_chars("library.txt", 5)
    display_line("library.txt")
    display_text("library.txt")


if __name__ == "__main__":
    run_task2()
```

**Output**

```text
The first 5 characters are:
The L
The first line is:
The Law Section
The full text is:
The Law Section
The Art Section
The Technology Section
The History Section
```

<a name="c7-writing-and-appending"></a>

### Writing and appending

```python
with open("output.txt", "w") as file:
    file.write("first line\n")
    file.write("second line\n")

with open("output.txt", "a") as file:
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

`write()` writes exactly what you give it: no automatic newline, and only strings (use `str()` or an f-string for numbers).

**Exercise 7.2: Sorting books into sections**

`books.txt` has lines that are either section headings (starting `Section:`) or book titles. Write `search_books(path)`, which builds two strings (all the sections, and `"Books:\n"` followed by all the books) and returns `f"{sections}\n\n{books}"`. Write `save(path, data)` to write a string to a file, and `run_task4()`, which saves the result to `section-books.txt`.

**Show solution**

```python
def search_books(file_path):
    print("Searching...", end="")
    sections = ""
    books = "Books:\n"
    with open(file_path) as file:
        for line in file:
            line = line.strip()
            if line.startswith("Section"):
                sections += line + "\n"
            else:
                books += line + "\n"
    print("Done!")
    return f"{sections}\n\n{books}"


def save(file_path, data):
    print("Saving...", end="")
    with open(file_path, "w") as file:
        file.write(data)
    print("Done!")


def run_task4():
    data = search_books("books.txt")
    save("section-books.txt", data)
    with open("section-books.txt") as file:      # check the result
        print(file.read())


run_task4()
```

**Output**

```text
Searching...Done!
Saving...Done!
Section: The Law Section
Section: The Technology Section
Section: The History Section


Books:
The Magna Carta
How to build a robot
How to build a flying car
The history of everything
```

<a name="c7-csv-files"></a>

### CSV files

A CSV file is a table stored as text. Each line is a row and commas separate the columns:

```text
id,name,colour
1,Shirt,Mercury
2,Coat,Boulder
3,Trousers,Black
```

You *could* split each line on commas yourself, but real data contains values like `"Smith, Ann"` that have commas inside quotes. The `csv` module handles that correctly, so always use it.

```python
import csv

with open("clothing.csv") as file:
    reader = csv.reader(file)
    headings = next(reader)          # take ONE row: the headings
    print("Headings:")
    print(headings)
    print("Values:")
    for values in reader:            # every remaining row, as a list of strings
        print(values)
```

**Output**

```text
Headings:
['id', 'name', 'colour']
Values:
['1', 'Shirt', 'Mercury']
['2', 'Coat', 'Boulder']
['3', 'Trousers', 'Black']
```

`csv.reader` gives each row as a **list of strings**. `next(reader)` takes just the next row, which is how you read (or skip) the heading line before looping over the data.

**Exercise 7.3: Extract names**

Write `extract(path)`, which skips the headings, collects every item name (column 1) into a string, one per line, and prints them after `Extracting...Done!`.

**Show solution**

```python
import csv


def extract(file_path):
    print("Extracting...", end="")
    names = ""
    with open(file_path) as file:
        reader = csv.reader(file)
        next(reader)                       # ignore headings
        for values in reader:
            names += values[1] + "\n"
    print("Done! The extracted items are as follows:")
    print(names, end="")


def run_task2():
    extract("clothing.csv")


run_task2()
```

**Output**

```text
Extracting...Done! The extracted items are as follows:
Shirt
Coat
Trousers
```

<a name="c7-loading-a-whole-csv-into-a-list"></a>

#### Loading a whole CSV into a list

Most data programs start by loading every row into a list once, and then work on the list:

```python
import csv


def load_data(file_path):
    """Return every data row of a CSV file as a list of lists."""
    records = []
    with open(file_path) as file:
        reader = csv.reader(file)
        next(reader)
        for row in reader:
            records.append(row)
    return records


records = load_data("titanic.csv")
print(f"Successfully loaded {len(records)} records.")
print(records[0])
print(records[0][3])        # the Name column
```

**Output**

```text
Successfully loaded 15 records.
['1', '0', '3', 'Braund, Mr. Owen Harris', 'male', '22', '1', '0', 'A/5 21171', '7.25', '', 'S']
Braund, Mr. Owen Harris
```

<a name="c7-every-csv-value-is-a-string"></a>

#### Every CSV value is a string

To do maths with a column, convert it. Watch out for empty cells:

```python
import csv

survived = 0
ages = []
with open("titanic.csv") as file:
    reader = csv.reader(file)
    next(reader)
    for row in reader:
        if int(row[1]) == 1:
            survived += 1
        if row[5] != "":                  # some ages are missing
            ages.append(float(row[5]))    # and some are like 0.42
print(survived, "survived")
print(f"Average known age: {sum(ages) / len(ages):.1f} from {len(ages)} passengers")
```

**Output**

```text
8 survived
Average known age: 29.0 from 14 passengers
```

**Three CSV traps**

1.  **Numbers arrive as text.** `"38" > "4"` is `False`, because strings compare character by character. Convert first.
2.  **Empty cells** are `""`, and `int("")` crashes. Test before converting.
3.  **Decimal values in a "whole number" column** (ages like `0.42`) crash `int()`. Use `float()`.

<a name="c7-writing-csv"></a>

#### Writing CSV

```python
import csv

rows = [["id", "name", "colour"], [4, "Skirt", "Cyan"], [5, "Hat", "Red"]]
with open("exported_items.csv", "w", newline="") as file:
    writer = csv.writer(file)
    for row in rows:
        writer.writerow(row)          # numbers are converted for you

with open("exported_items.csv") as file:
    print(file.read())
```

**Output**

```text
id,name,colour
4,Skirt,Cyan
5,Hat,Red
```

`newline=""` prevents blank lines between rows on Windows. You can also write CSV by hand with `file.write(f"{a},{b},{c}\n")`, but then values that contain commas will break.

**Exercise 7.4: Export items**

Write `export(path, count)`, which opens a CSV in **append** mode and, `count` times, asks for an id, a name and a colour and writes them as a new row. Call it to add 2 items to `clothing.csv`, then print the file.

**Show solution**

```python
import csv


def export(file_path, count):
    print("Exporting...")
    with open(file_path, "a", newline="") as file:
        writer = csv.writer(file)
        for i in range(count):
            print("Please enter the item id:")
            item_id = input()
            print("Please enter the item name:")
            item_name = input()
            print("Please enter the item colour:")
            item_colour = input()
            writer.writerow([item_id, item_name, item_colour])
    print("Done!")


def run():
    export("clothing.csv", 2)
    with open("clothing.csv") as file:
        print(file.read())


run()
```

**Output**

```text
Exporting...
Please enter the item id:
4 ↵
Please enter the item name:
Skirt ↵
Please enter the item colour:
Cyan ↵
Please enter the item id:
5 ↵
Please enter the item name:
Hat ↵
Please enter the item colour:
Red ↵
Done!
id,name,colour
1,Shirt,Mercury
2,Coat,Boulder
3,Trousers,Black
4,Skirt,Cyan
5,Hat,Red
```

<a name="c7-when-the-file-isnt-there-try-except"></a>

### When the file isn't there: try / except

`try` runs some code, and `except` catches a specific error if one happens, so the program can respond instead of crashing:

```python
def read_lines(file_path):
    try:
        with open(file_path) as file:
            return file.read().splitlines()
    except FileNotFoundError:
        print(f"Error! Could not find {file_path}")
        return []


print(read_lines("library.txt"))
print(read_lines("nope.txt"))
```

**Output**

```text
['The Law Section', 'The Art Section', 'The Technology Section', 'The History Section']
Error! Could not find nope.txt
[]
```

The same pattern catches bad user input: `except ValueError:` around `int(input())`.

**Checkpoint 7**

1.  Which mode empties a file before writing?
2.  `line = "Shirt\n"`. What are `len(line)` and `len(line.strip())`?
3.  A file has 3 lines. After `file.read()`, what does a second `file.read()` return?
4.  Why is `line.split(",")` dangerous for CSV files?
5.  What type is `row[2]` when `row` came from `csv.reader`?

**Answers**

1.  `"w"`
2.  `6` and `5`
3.  `""` (an empty string). You are already at the end of the file.
4.  Values can contain commas inside quotes (`"Smith, Ann"`); `csv.reader` handles that and `split` doesn't.
5.  `str`, always

<a name="c7-summary"></a>

### Summary

- Relative paths start from the cwd (`os.getcwd()`); `.` is here, `..` is up one level.
- `with open(path, mode) as file:` opens a file and closes it automatically. The modes are `r`, `w` (wipes), `a` and `x`.
- Use `read()`, `read(n)` or `readline()`, or `for line in file:` with `.strip()`.
- `write()` adds no newline for you.
- CSV: `csv.reader(file)`, `next(reader)` for headings, rows are lists of strings. Convert with `int()`/`float()` and check for `""`.
- `try`/`except FileNotFoundError` (or `ValueError`) handles predictable errors gracefully.

<a name="c8-sets-dictionaries-and-json"></a>

## Chapter 8: Sets, dictionaries and JSON

**Goals:** use sets for unique values and membership; use dictionaries to look things up by name; count, group and tally with dictionaries; nest dictionaries; read and write JSON files.

<a name="c8-unordered-data-structures"></a>

### Unordered data structures

Lists and tuples find items by **position**. Sets and dictionaries find items by **value**, using a technique called *hashing*. That makes membership tests and look-ups very fast, even with millions of items.

**Hashing in one paragraph**

To store an item, Python computes a number from it (its *hash*) and uses that number to decide where in memory the item goes. To check whether something is present, it computes the same hash and looks in that one place, instead of scanning every item as a list must. Two consequences: items in a set (and keys in a dict) must be **immutable** (strings, numbers and tuples are fine; lists aren't), because a value that changed would have a different hash; and a set has no meaningful order of its own.

<a name="c8-sets"></a>

### Sets

A set is a collection of **distinct** items. Duplicates disappear automatically.

```python
web_browsers = set()                               # empty set (NOT {})
web_browsers = {"Chrome", "Firefox", "Edge", "Chrome"}
print(len(web_browsers), "Edge" in web_browsers)
web_browsers.add("Opera")
web_browsers.discard("Safari")                     # no error if missing
web_browsers.remove("Edge")                        # KeyError if missing
print(sorted(web_browsers))
```

**Output**

```text
3 True
['Chrome', 'Firefox', 'Opera']
```

`{}` makes an empty **dictionary**, not a set. Use `set()` for an empty set.

A set has no index (`s[0]` is an error), and printing one shows its items in an arbitrary order. When order matters, `sorted(s)` returns a sorted **list**.

<a name="c8-the-classic-use-distinct-values"></a>

#### The classic use: distinct values

```python
import csv

classes = set()
with open("titanic.csv") as file:
    reader = csv.reader(file)
    next(reader)
    for row in reader:
        classes.add(int(row[2]))          # Pclass column
print(classes)
print(sorted(classes, reverse=True))
```

**Output**

```text
{1, 2, 3}
[3, 2, 1]
```

<a name="c8-set-operations"></a>

#### Set operations

```python
module_a = {"Ada", "Ben", "Cara", "Dev"}
module_b = {"Cara", "Dev", "Eli"}
print(module_a | module_b)      # union: in either
print(module_a & module_b)      # intersection: in both
print(module_a - module_b)      # difference: in A but not B
print(module_a ^ module_b)      # symmetric difference: in exactly one
```

**Output**

```text
{'Eli', 'Ben', 'Dev', 'Cara', 'Ada'}
{'Dev', 'Cara'}
{'Ben', 'Ada'}
{'Eli', 'Ben', 'Ada'}
```

**Exercise 8.1: Observations**

Write `observed()`, which returns a set built from `"Car", "Sky Scraper", "Sky Scraper", "Bike", "House", "House"`, and print it. Then write a version that reads 7 observations from the user into a **list** and, for each distinct value, prints how many times it was seen (use `list.count`), e.g. `Neon Sign observed 5 times.`

**Show solution**

```python
def observed():
    observations = {"Car", "Sky Scraper", "Sky Scraper", "Bike", "House", "House"}
    return observations


def observed_items():
    observations = []
    for i in range(7):
        print("Please enter an observation:")
        observations.append(input())
    return observations


def run_task2():
    print(sorted(observed()))
    print("Counting observations...")
    data = observed_items()
    counted = set()
    for item in data:
        counted.add((item, data.count(item)))     # tuples can go in sets
    for item, times in sorted(counted):
        print(f"{item} observed {times} times.")


run_task2()
```

**Output**

```text
['Bike', 'Car', 'House', 'Sky Scraper']
Counting observations...
Please enter an observation:
Skyscraper ↵
Please enter an observation:
Skyscraper ↵
Please enter an observation:
Neon Sign ↵
Please enter an observation:
Neon Sign ↵
Please enter an observation:
Neon Sign ↵
Please enter an observation:
Neon Sign ↵
Please enter an observation:
Neon Sign ↵
Neon Sign observed 5 times.
Skyscraper observed 2 times.
```

<a name="c8-dictionaries"></a>

### Dictionaries

A dictionary stores **key → value** pairs. You look values up by key, like a word in a real dictionary.

```python
wedding = {"Cake": 1, "Car": 1, "Ribbons": 100}
print(wedding["Ribbons"])          # look up by key
wedding["Guests"] = 30             # add a new pair
wedding["Cake"] = 2                # change an existing value
del wedding["Car"]                 # remove a pair
print(wedding, len(wedding))
print("Cake" in wedding, 100 in wedding)    # 'in' checks KEYS
```

**Output**

```text
100
{'Cake': 2, 'Ribbons': 100, 'Guests': 30} 3
True False
```

- Keys are unique. Assigning to an existing key replaces its value.
- Keys must be immutable (strings and numbers are usual); values can be anything, including lists and other dictionaries.
- Since Python 3.7, dictionaries remember the order in which keys were inserted.

<a name="c8-reading-safely"></a>

#### Reading safely

```python
wedding = {"Cake": 1}
print(wedding["Balloons"])
```

**Output (error)**

```text
Traceback (most recent call last):
  File "main.py", line 2, in <module>
    ...
KeyError: 'Balloons'
```

```python
wedding = {"Cake": 1}
print(wedding.get("Balloons"))         # None instead of a crash
print(wedding.get("Balloons", 0))      # or a default of your choice
```

**Output**

```text
None
0
```

<a name="c8-looping"></a>

#### Looping

```python
sequences = {"Short Sequence": 3, "Medium Sequence": 2, "Long Sequence": 1}

print("Keys:")
for key in sequences:                       # same as sequences.keys()
    print(key)
print("Values:")
for value in sequences.values():
    print(value)
print("Pairs:")
for key, value in sequences.items():        # unpack each (key, value) tuple
    print(f"{key}: {value}")
```

**Output**

```text
Keys:
Short Sequence
Medium Sequence
Long Sequence
Values:
3
2
1
Pairs:
Short Sequence: 3
Medium Sequence: 2
Long Sequence: 1
```

**Exercise 8.2: Display a dictionary three ways**

Write `pattern()`, which returns the dictionary above; `display_keys(data)`, `display_values(data)` and `display_items(data)`; and `run()`, which calls them all after printing the whole dictionary.

**Show solution**

```python
def pattern():
    sequences = {"Short Sequence": 3, "Medium Sequence": 2, "Long Sequence": 1}
    return sequences


def display_keys(data):
    for key in data.keys():
        print(key)


def display_values(data):
    for value in data.values():
        print(value)


def display_items(data):
    for key, value in data.items():
        print(f"{key}: {value}")


def run():
    data = pattern()
    print("Dictionary:")
    print(data)
    print("Keys:")
    display_keys(data)
    print("Values:")
    display_values(data)
    print("Pairs:")
    display_items(data)


run()
```

**Output**

```text
Dictionary:
{'Short Sequence': 3, 'Medium Sequence': 2, 'Long Sequence': 1}
Keys:
Short Sequence
Medium Sequence
Long Sequence
Values:
3
2
1
Pairs:
Short Sequence: 3
Medium Sequence: 2
Long Sequence: 1
```

<a name="c8-three-patterns-you-will-use-constantly"></a>

### Three patterns you will use constantly

<a name="c8-1-counting"></a>

#### 1. Counting

```python
import csv

counts = {}
with open("titanic.csv") as file:
    reader = csv.reader(file)
    next(reader)
    for row in reader:
        sex = row[4]
        if sex in counts:
            counts[sex] += 1          # seen before: add one
        else:
            counts[sex] = 1           # first time: start at one
print(counts)
```

**Output**

```text
{'male': 8, 'female': 7}
```

The four lines of `if/else` can be shortened to `counts[sex] = counts.get(sex, 0) + 1`.

<a name="c8-2-tallying-fixed-categories"></a>

#### 2. Tallying fixed categories

When you know the categories in advance, start them all at zero. Then every category appears in the result, even with a count of 0, and unexpected values are easy to ignore:

```python
import csv

tally = {"Gold": 0, "Silver": 0, "Bronze": 0}
with open("athlete_events.csv") as file:
    reader = csv.reader(file)
    next(reader)
    for row in reader:
        medal = row[14]
        if medal in tally:            # skips "NA"
            tally[medal] += 1
print(tally)
```

**Output**

```text
{'Gold': 3, 'Silver': 2, 'Bronze': 2}
```

<a name="c8-3-grouping-a-dictionary-of-lists"></a>

#### 3. Grouping (a dictionary of lists)

Collect every value that belongs to the same key, then compute something per group:

```python
import csv

ages_by_class = {}
with open("titanic.csv") as file:
    reader = csv.reader(file)
    next(reader)
    for row in reader:
        passenger_class = row[2]
        if row[5] == "":
            continue                                  # skip unknown ages
        if passenger_class not in ages_by_class:
            ages_by_class[passenger_class] = []
        ages_by_class[passenger_class].append(float(row[5]))

for passenger_class in sorted(ages_by_class):
    ages = ages_by_class[passenger_class]
    print(f"Class {passenger_class}: {len(ages)} passengers, average age {sum(ages) / len(ages):.1f}")
```

**Output**

```text
Class 1: 5 passengers, average age 51.2
Class 2: 1 passengers, average age 14.0
Class 3: 8 passengers, average age 17.1
```

<a name="c8-sorting-a-dictionary-by-its-values"></a>

#### Sorting a dictionary by its values

`sorted(d)` sorts the **keys**. To rank by value, sort the `(key, value)` pairs with a key function:

```python
counts = {"Finland": 4, "Norway": 3, "Tonga": 1, "Denmark/Sweden": 1}
ranked = sorted(counts.items(), key=lambda pair: pair[1], reverse=True)
print(ranked)
for team, n in ranked[:2]:            # top two
    print(team, n)
```

**Output**

```text
[('Finland', 4), ('Norway', 3), ('Tonga', 1), ('Denmark/Sweden', 1)]
Finland 4
Norway 3
```

<a name="c8-nested-dictionaries"></a>

### Nested dictionaries

A value can itself be a dictionary, which gives you a two-level look-up:

```python
wedding = {
    "items": {"Cake": 1, "Car": 1, "Ribbons": 100},
    "people": {"guests": 30},
}
print(wedding["items"]["Ribbons"])
for key, value in wedding.items():
    print(f"{key}: {value}")
```

**Output**

```text
100
items: {'Cake': 1, 'Car': 1, 'Ribbons': 100}
people: {'guests': 30}
```

Counting per group per category produces a nested dictionary:

```python
import csv

team_tally = {}
with open("athlete_events.csv") as file:
    reader = csv.reader(file)
    next(reader)
    for row in reader:
        team, medal = row[6], row[14]
        if medal == "NA":
            continue
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
  Gold:0, Silver:1, Bronze:1
Denmark/Sweden
  Gold:1, Silver:0, Bronze:0
Tonga
  Gold:0, Silver:1, Bronze:0
```

**Exercise 8.3: Patterns of patterns**

Write `short_pattern()`, `medium_pattern()` and `long_pattern()`, each returning a dictionary with keys `"sequence"` and `"occurrences"` (`"101"`/5, `"111000"`/25, `"1100110011001100"`/50). `run_task3()` prints `Analysing patterns...`, builds a dictionary that maps `"short sequence"`, `"medium sequence"` and `"long sequence"` to those three results, and prints every pair.

**Show solution**

```python
def short_pattern():
    return {"sequence": "101", "occurrences": 5}


def medium_pattern():
    return {"sequence": "111000", "occurrences": 25}


def long_pattern():
    return {"sequence": "1100110011001100", "occurrences": 50}


def run_task3():
    print("Analysing patterns...")
    patterns = {
        "short sequence": short_pattern(),
        "medium sequence": medium_pattern(),
        "long sequence": long_pattern(),
    }
    for key, value in patterns.items():
        print(f"{key}: {value}")


run_task3()
```

**Output**

```text
Analysing patterns...
short sequence: {'sequence': '101', 'occurrences': 5}
medium sequence: {'sequence': '111000', 'occurrences': 25}
long sequence: {'sequence': '1100110011001100', 'occurrences': 50}
```

<a name="c8-json"></a>

### JSON

**JSON** (JavaScript Object Notation) is a text format for structured data, used everywhere on the web. It maps almost one-to-one onto Python:

| JSON                      | Python                    |
|---------------------------|---------------------------|
| `{"key": value}` (object) | `dict`                    |
| `[1, 2, 3]` (array)       | `list`                    |
| `"text"`                  | `str`                     |
| `42`, `3.5`               | `int`, `float`            |
| `true` / `false` / `null` | `True` / `False` / `None` |

```text
{
    "location": "Earth",
    "population": 1000000,
    "bots": [
        {"id": 1, "name": "Bolt", "stats": {"speed": 5, "strength": 8}},
        {"id": 2, "name": "Cog", "stats": {"speed": 3, "strength": 10}}
    ]
}
```

<a name="c8-reading-json"></a>

#### Reading JSON

```python
import json


def read(file_path):
    with open(file_path) as file:
        data = json.load(file)            # file -> Python dict
    print(f"Place Name: {data['location']}")
    print(f"Population Size: {data['population']}")
    for bot in data["bots"]:
        stats = bot["stats"]
        print(f"{bot['name']} has a strength level of {stats['strength']} and a speed level of {stats['speed']}.")


read("robots.json")
```

**Output**

```text
Place Name: Earth
Population Size: 1000000
Bolt has a strength level of 8 and a speed level of 5.
Cog has a strength level of 10 and a speed level of 3.
Spark has a strength level of 5 and a speed level of 10.
```

Navigate a nested structure one step at a time: `data["bots"]` is a list, each item in it is a dict, and `bot["stats"]` is another dict.

<a name="c8-writing-json"></a>

#### Writing JSON

```python
import json


def read_json(file_path):
    print("Reading...", end="")
    with open(file_path) as file:
        data = json.load(file)
    print("Done!")
    return data


def save(file_path, data):
    print("Exporting...", end="")
    with open(file_path, "w") as file:
        json.dump(data, file, indent=4)   # indent makes it human-readable
    print("Done!")


json_data = read_json("robots.json")
json_data["population"] += 1
save("exported.json", json_data)
with open("exported.json") as file:
    print(file.read()[:120], "...")
```

**Output**

```text
Reading...Done!
Exporting...Done!
{
    "location": "Earth",
    "population": 1000001,
    "bots": [
        {
            "id": 1,
            "name": " ...
```

`json.load` / `json.dump` work with **files**. `json.loads` / `json.dumps` (with an *s* for *string*) work with strings.

**Checkpoint 8**

1.  `len({1, 2, 2, 3, 3, 3})`?
2.  `type({})`?
3.  `d = {"a": 1}`. What do `"a" in d`, `1 in d` and `d.get("b", 5)` give?
4.  `d = {"x": 1, "x": 2}`. What is `d`?
5.  Why can't a list be a dictionary key?
6.  `json.load` turns a JSON array into which Python type?

**Answers**

1.  `3`
2.  `<class 'dict'>`
3.  `True`, `False` (`in` checks keys), `5`
4.  `{'x': 2}`. The later value wins.
5.  Lists are mutable, so their hash could change; keys must be immutable (a tuple works).
6.  `list`

<a name="c8-summary"></a>

### Summary

- **Set**: unique items, fast `in`, no index; `add`, `discard`, `remove`, `| & - ^`; `sorted(s)` returns a list.
- **Dict**: `d[key] = value`, `d[key]`, `d.get(key, default)`, `key in d`, `.keys()`, `.values()`, `.items()`.
- Counting: `d[k] = d.get(k, 0) + 1`. Tallying: start fixed keys at 0. Grouping: `d.setdefault(k, []).append(v)`, or the `if k not in d` version.
- Rank by value: `sorted(d.items(), key=lambda pair: pair[1], reverse=True)`.
- JSON ↔ dict/list with `json.load(file)` and `json.dump(data, file, indent=4)`.

<a name="c9-visualising-data-with-matplotlib"></a>

## Chapter 9: Visualising data with matplotlib

**Goals:** know why visualisation matters; install and import a third-party library; draw line, marker, bar, pie and step charts; label everything; style lines and markers; plot data from lists, dictionaries and user input.

<a name="c9-why-visualise"></a>

### Why visualise

A chart shows patterns, trends and outliers that a table of numbers hides. The module's reading gives three historic examples worth being able to describe in a report:

- **Charles Minard (1869)**: Napoleon's 1812 march on Moscow. A single band shows the army shrinking from over 400,000 men to about 10,000, with the temperature on the retreat underneath. It is often called the best statistical graphic ever drawn.
- **John Snow (1854)**: a dot map of cholera deaths in Soho clustered around the Broad Street water pump. It was evidence that cholera spreads through water, not "bad air".
- **Florence Nightingale (1858)**: "rose" diagrams showing that far more soldiers in the Crimean War died of preventable disease than of wounds. The diagrams persuaded the army to improve sanitation.

In each case the picture changed a decision. That is the standard to aim for: every chart should answer a question.

<a name="c9-third-party-libraries"></a>

### Third-party libraries

Python's standard library doesn't draw charts. **matplotlib** is a *third-party* library: someone else's code that you install. In PyCharm: *Settings → Project → Python Interpreter → +* → search for `matplotlib` → Install. From a terminal: `pip install matplotlib`. It is the only third-party library AE2 allows.

```python
import matplotlib.pyplot as plt     # the conventional alias
```

`pyplot` is matplotlib's simple charting module. Every chart follows the same steps:

1.  **draw** something (`plt.plot`, `plt.bar`, `plt.pie`, …);
2.  **label** it (`plt.title`, `plt.xlabel`, `plt.ylabel`, `plt.legend`);
3.  **show** it (`plt.show()`), which opens a window and pauses the program until you close it.

<a name="c9-line-charts"></a>

### Line charts

`plt.plot(x_values, y_values)` draws a point for each (x, y) pair and joins the points with straight lines. Both lists must be the same length.

```python
import matplotlib.pyplot as plt


def display_line(x_values, y_values):
    plt.plot(x_values, y_values)
    plt.title("Square numbers")
    plt.xlabel("x")
    plt.ylabel("x squared")
    plt.show()


def run_task1():
    x_values = [1, 2, 3, 4, 5]
    y_values = [1, 4, 9, 16, 25]
    display_line(x_values, y_values)


run_task1()
```

**Output**

![matplotlib output](images/QHO444_Learn_Python/figure-01.png) <a name="c9-styling-the-format-string"></a>

#### Styling: the format string

A short string after x and y sets the colour, marker and line style, in any order:

| Colour                                                                                | Marker                                                                                | Line                                              |
|---------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------|---------------------------------------------------|
| `r` red, `g` green, `b` blue, `c` cyan, `m` magenta, `y` yellow, `k` black, `w` white | `o` circle, `s` square, `^` `v` triangles, `p` pentagon, `*` star, `x` cross, `.` dot | `-` solid, `--` dashed, `-.` dash-dot, `:` dotted |

```python
import matplotlib.pyplot as plt

x = [1, 2, 3, 4]
plt.plot(x, [1, 2, 3, 4], "ro--", label="'ro--' red circles, dashed")
plt.plot(x, [2, 3, 4, 5], "gs:", label="'gs:' green squares, dotted")
plt.plot(x, [3, 4, 5, 6], "bp-", label="'bp-' blue pentagons, solid")
plt.plot(x, [4, 5, 6, 7], "k^", label="'k^' black triangles, no line")
plt.legend()
plt.title("Format strings")
plt.show()
```

**Output**

![matplotlib output](images/QHO444_Learn_Python/figure-02.png)

`label=` names each line, and `plt.legend()` displays the names. Calling `plt.plot` several times before `plt.show()` draws all the lines on one chart.

**Exercise 9.1: Nested squares**

Write `small()`, `medium()` and `large()`, each drawing a square with `plt.plot` (five points, ending where it started): small is a red dotted line with circle markers, medium a green dashed line with square markers around it, and large a blue solid line with pentagon markers around both. Show them on one chart.

**Show solution**

```python
import matplotlib.pyplot as plt


def small():
    plt.plot([2, 3, 3, 2, 2], [2, 2, 3, 3, 2], "r:o")


def medium():
    plt.plot([1, 4, 4, 1, 1], [1, 1, 4, 4, 1], "g--s")


def large():
    plt.plot([0, 5, 5, 0, 0], [0, 0, 5, 5, 0], "b-p")


small()
medium()
large()
plt.title("Squares")
plt.axis("equal")         # same scale on both axes, so squares look square
plt.show()
```

**Output**

![matplotlib output](images/QHO444_Learn_Python/figure-03.png)

**Exercise 9.2: Path from user input**

Write `coordinate()`, which asks for an x and a y value and returns them as a tuple; `path()`, which calls it 4 times and returns `[x_values, y_values]`; and `run_task3()`, which plots the path as a red dashed line with circle markers and labelled axes.

**Show solution**

```python
import matplotlib.pyplot as plt


def coordinate():
    print("Please enter an x value:")
    x = float(input())
    print("Please enter a y value:")
    y = float(input())
    return (x, y)


def path():
    print("Retrieving path...")
    x_values = []
    y_values = []
    for i in range(4):
        data = coordinate()
        x_values.append(data[0])
        y_values.append(data[1])
    return [x_values, y_values]


def run_task3():
    values = path()
    plt.plot(values[0], values[1], "ro--")
    plt.xlabel("x")
    plt.ylabel("y")
    plt.title("Path")
    plt.show()


run_task3()
```

**Output**

```text
Retrieving path...
Please enter an x value:
1 ↵
Please enter a y value:
5 ↵
Please enter an x value:
1 ↵
Please enter a y value:
10 ↵
Please enter an x value:
5 ↵
Please enter a y value:
5 ↵
Please enter an x value:
5 ↵
Please enter a y value:
10 ↵
```

![matplotlib output](images/QHO444_Learn_Python/figure-04.png) <a name="c9-bar-charts"></a>

### Bar charts

`plt.bar(labels, heights)` draws one bar per category. It is the right chart for **comparing amounts across categories**.

```python
import matplotlib.pyplot as plt

tally = {"Gold": 13372, "Silver": 13116, "Bronze": 13295}
plt.bar(list(tally.keys()), list(tally.values()), color=["gold", "silver", "peru"])
plt.title("Olympic medals awarded, 1896-2016")
plt.xlabel("Medal")
plt.ylabel("Number awarded")
plt.show()
```

**Output**

![matplotlib output](images/QHO444_Learn_Python/figure-05.png)

When the labels are long, rotate them, or use `plt.barh` for horizontal bars:

```python
import matplotlib.pyplot as plt

teams = ["Finland", "Norway", "Denmark/Sweden", "Tonga"]
medals = [4, 3, 1, 1]
plt.figure(figsize=(7, 3.5))
plt.barh(teams, medals, color="tab:blue")
plt.title("Medals per team (sample data)")
plt.xlabel("Medals")
plt.tight_layout()
plt.show()
```

**Output**

![matplotlib output](images/QHO444_Learn_Python/figure-06.png)

**Course material error**

The Week 8 reading says `plt.bar` "is used to create a histogram". It draws a **bar chart** from values you supply. A histogram, which counts how many values fall into each range ("bin"), is `plt.hist`:

```python
import matplotlib.pyplot as plt

ages = [22, 38, 26, 35, 35, 54, 2, 27, 14, 4, 58, 20, 0.42, 71]
plt.hist(ages, bins=[0, 10, 20, 30, 40, 50, 60, 70, 80], edgecolor="black")
plt.title("Age distribution (sample passengers)")
plt.xlabel("Age")
plt.ylabel("Passengers")
plt.show()
```

**Output**

![matplotlib output](images/QHO444_Learn_Python/figure-07.png) <a name="c9-pie-charts"></a>

### Pie charts

`plt.pie(sizes, labels=labels)` shows **parts of a whole**. Use it only when the slices add up to something meaningful, and only with a few categories.

```python
import matplotlib.pyplot as plt

labels = ("A", "B", "C", "D")
sizes = [15, 30, 45, 10]
plt.pie(sizes, labels=labels, autopct="%1.1f%%", startangle=90)
plt.title("Share by category")
plt.axis("equal")         # keep it circular
plt.show()
```

**Output**

![matplotlib output](images/QHO444_Learn_Python/figure-08.png)

`autopct="%1.1f%%"` writes each slice's percentage to one decimal place.

<a name="c9-step-plots"></a>

### Step plots

`plt.step` draws a staircase instead of diagonal lines. It suits values that jump and then hold, like a price that stays fixed until it changes.

```python
import matplotlib.pyplot as plt

x = [0, 2, 4, 6, 8, 10]
y = [0, 20, 40, 60, 80, 100]
plt.step(x, y, where="post")
plt.title("Step plot")
plt.xlabel("x values")
plt.ylabel("y values")
plt.show()
```

**Output**

![matplotlib output](images/QHO444_Learn_Python/figure-09.png) <a name="c9-plotting-from-data-structures"></a>

### Plotting from data structures

Most chart code is really **data preparation**: turning your records into one list of labels and one list of numbers.

```python
import csv
import matplotlib.pyplot as plt

survivors = {"1": 0, "2": 0, "3": 0}
totals = {"1": 0, "2": 0, "3": 0}
with open("titanic.csv") as file:
    reader = csv.reader(file)
    next(reader)
    for row in reader:
        passenger_class = row[2]
        totals[passenger_class] += 1
        if row[1] == "1":
            survivors[passenger_class] += 1

labels = [f"Class {c}" for c in totals]
rates = [100 * survivors[c] / totals[c] for c in totals]
plt.bar(labels, rates, color=["tab:green", "tab:orange", "tab:red"])
plt.title("Survival rate by class (15-passenger sample)")
plt.ylabel("Survived (%)")
plt.ylim(0, 100)
plt.show()
```

**Output**

![matplotlib output](images/QHO444_Learn_Python/figure-10.png)

**Exercise 9.3: Lines chosen by the user**

Write `data()`, which asks for a line style (`:`, `--`, `-`), a colour (`r`, `g`, `b`) and a marker (`o`, `s`, `^`) and returns them in a dictionary. Write `generate()`, which asks how many lines to draw and, for each, calls `data()` and plots `random.sample(range(10), 5)` against `range(5)` using those settings. Write `run()`, which prints `Running....`, calls `generate()`, shows the chart, and prints `Done!`.

**Show solution**

```python
import random
import matplotlib.pyplot as plt


def data():
    paths = {}
    print("What type of line would you like (:, -- or -)?")
    paths["line"] = input()
    print("What colour would you like (r, g or b)?")
    paths["colour"] = input()
    print("What style of marker would you like (o, s or ^)?")
    paths["marker"] = input()
    return paths


def generate():
    print("How many lines would you like to display?")
    lines = int(input())
    for i in range(lines):
        values = data()
        style = values["colour"] + values["marker"] + values["line"]
        plt.plot(range(5), random.sample(range(10), 5), style, label=f"line {i + 1}")
    plt.legend()
    plt.title("User-styled lines")


def run():
    print("Running....")
    generate()
    plt.show()
    print("Done!")


run()
```

**Output**

```text
Running....
How many lines would you like to display?
2 ↵
What type of line would you like (:, -- or -)?
-- ↵
What colour would you like (r, g or b)?
r ↵
What style of marker would you like (o, s or ^)?
o ↵
What type of line would you like (:, -- or -)?
: ↵
What colour would you like (r, g or b)?
b ↵
What style of marker would you like (o, s or ^)?
^ ↵
```

![matplotlib output](images/QHO444_Learn_Python/figure-11.png)

```text
Done!
```

<a name="c9-a-good-chart-checklist"></a>

### A good chart checklist

- A **title** that says what the chart shows
- **Axis labels**, with units (`Weight (kg)`, `Reviews`, `%`)
- A **legend** if there is more than one series
- The right **type**: line for change over an ordered x (such as time), bar for comparing categories, pie for parts of a whole with few slices, histogram for a distribution
- Labels **readable** (rotated or horizontal bars if they are long; `plt.tight_layout()`)
- Categories in a **meaningful order** (time order, or sorted by value), not random
- A **sensible axis range**: a bar chart's y axis should start at 0, or the bars mislead

**Checkpoint 9**

1.  What does `"g^:"` draw?
2.  You call `plt.plot` twice and then `plt.show()` once. How many charts appear?
3.  Which chart type would you use to compare the number of students in 5 courses?
4.  What is wrong with `plt.plot([1, 2, 3], [4, 5])`?
5.  Nothing appears when the program runs. What is the first thing to check?

**Answers**

1.  Green triangle markers joined by a dotted line.
2.  One chart containing both lines.
3.  A bar chart.
4.  The lists have different lengths, so matplotlib raises a `ValueError`.
5.  That `plt.show()` is called.

<a name="c9-summary"></a>

### Summary

- `import matplotlib.pyplot as plt`, then draw, label and `plt.show()`.
- `plt.plot(x, y, "colour marker line")` for lines; `plt.bar` for categories; `plt.pie` for parts of a whole; `plt.hist` for distributions; `plt.step` for staircase data.
- `title`, `xlabel`, `ylabel` and `legend` (with `label=`) make a chart readable.
- Turn dictionaries into chart input with `list(d.keys())` and `list(d.values())`.

<a name="c10-object-oriented-programming"></a>

## Chapter 10: Object-oriented programming

**Goals:** understand classes and objects; write `__init__` and methods using `self`; tell class attributes from instance attributes; use static and class methods; control printing with `__str__` and `__repr__`; build objects that contain other objects; plot data held in objects.

<a name="c10-from-procedures-to-objects"></a>

### From procedures to objects

So far, programs have been **procedural**: data sits in variables and structures, and separate functions act on it. That works, but as programs grow, it gets hard to see which functions belong with which data.

**Object-oriented programming (OOP)** bundles the data and the functions that act on it into one unit, an **object**. A **class** is the blueprint that describes what every object of that kind has (**attributes**) and can do (**methods**).

| Concept           | Analogy                                   | Code                 |
|-------------------|-------------------------------------------|----------------------|
| class             | the plan for a house                      | `class Human:`       |
| object / instance | one house built from the plan             | `ada = Human("Ada")` |
| attribute         | a fact about that house (number of rooms) | `ada.age`            |
| method            | something the house does (open door)      | `ada.grow()`         |

<a name="c10-a-first-class"></a>

### A first class

```python
class Person:
    def __init__(self, name, age=0, weight=0):
        self.name = name
        self.age = age
        self.weight = weight

    def display(self):
        print(f"{self.name} is {self.age} years old and weighs {self.weight}kg")


jane = Person("Jane Smith")              # only the required argument
jane.display()
bob = Person("Bob Jones", 26, 65)        # all three
bob.display()
bob.age += 1                             # attributes can be changed
bob.display()
```

**Output**

```text
Jane Smith is 0 years old and weighs 0kg
Bob Jones is 26 years old and weighs 65kg
Bob Jones is 27 years old and weighs 65kg
```

- `class Person:` starts the blueprint. Class names use `CapWords`.
- `__init__` is the **initialiser**. Python calls it automatically when you create an object with `Person(...)`, and its job is to set up the object's starting attributes.
- `self` is **the object being created or used**. `self.name = name` means "store the `name` argument as this object's `name` attribute".
- A **method** is a function defined inside the class. Its first parameter is always `self`, but you never pass `self` yourself: `jane.display()` passes `jane` automatically.

**What \`self\` really is**

`jane.display()` is shorthand for `Person.display(jane)`. Python looks up `display` on the class and passes the object in as the first argument, which by convention is named `self`. That's why forgetting `self` in a method definition gives `takes 0 positional arguments but 1 was given`: Python passed one argument (the object) that the method wasn't expecting.

```python
class Person:
    def __init__(self, name):
        self.name = name

    def display(self):
        print("I am", self.name)


jane = Person("Jane")
jane.display()
Person.display(jane)          # exactly the same call, written out
```

**Output**

```text
I am Jane
I am Jane
```

<a name="c10-class-attributes-vs-instance-attributes"></a>

### Class attributes vs instance attributes

- An **instance attribute** (`self.x = ...` in `__init__`) belongs to **one** object. Each object has its own copy.
- A **class attribute** (written directly in the class body) is **shared** by every object of the class. It is ideal for constants. PEP-8 writes constants in `UPPER_CASE`.

```python
class Human:
    MAX_ENERGY = 100                          # class attribute

    def __init__(self, name="Human"):
        self.name = name                      # instance attributes
        self.age = 0
        self.energy = Human.MAX_ENERGY

    def display(self):
        print(f"I am {self.name}")


a = Human("Ada")
b = Human()
a.energy -= 30
print(a.energy, b.energy, Human.MAX_ENERGY, a.MAX_ENERGY)
b.display()
```

**Output**

```text
70 100 100 100
I am Human
```

<a name="c10-static-methods-and-class-methods"></a>

### Static methods and class methods

| Kind            | Decorator       | First parameter     | Can use                              | Typical use                                   |
|-----------------|-----------------|---------------------|--------------------------------------|-----------------------------------------------|
| instance method | none            | `self` (the object) | instance and class attributes        | almost everything                             |
| class method    | `@classmethod`  | `cls` (the class)   | class attributes; can create objects | alternative constructors (`Robot.assemble()`) |
| static method   | `@staticmethod` | none                | nothing automatic                    | utility functions that belong with the class  |

```python
class Robot:
    laws = "Protect, Obey and Survive"         # class attribute

    @staticmethod
    def the_laws():
        print(Robot.laws)

    @classmethod
    def assemble(cls):
        return cls("Assembled Robot")          # cls is Robot

    def __init__(self, name="Robot"):
        self.name = name
        self.age = 0

    def display(self):
        print(f"I am {self.name}")


Robot.the_laws()                    # called on the class, no object needed
r = Robot.assemble()
r.display()
```

**Output**

```text
Protect, Obey and Survive
I am Assembled Robot
```

**Course material error**

The Week 9 page says class methods "require an instance of the class". They don't: a class method receives the **class** and is usually called on the class itself, as `Robot.assemble()` is above.

**Exercise 10.1: Human and Robot**

In `human.py`, write a class `Human` with class attribute `MAX_ENERGY = 100`, instance attributes `name` (default `"Human"`), `age` (0) and `energy` (`MAX_ENERGY`), and a `display()` method printing `I am {name}`. In `robot.py`, write `Robot` as in the example above, plus `energy` (starting at 0) and `MAX_ENERGY = 100`. Test each with a `__main__` block.

**Show solution**

File: human.py

```python
class Human:
    """A human inhabitant."""

    MAX_ENERGY = 100

    def __init__(self, name="Human", age=0):
        self.name = name
        self.age = age
        self.energy = Human.MAX_ENERGY

    def display(self):
        print(f"I am {self.name}")


if __name__ == "__main__":
    human = Human()
    human.display()
```

**Output**

```text
I am Human
```

File: robot.py

```python
class Robot:
    """A robot inhabitant."""

    MAX_ENERGY = 100
    laws = "Protect, Obey and Survive"

    @staticmethod
    def the_laws():
        print(Robot.laws)

    @classmethod
    def assemble(cls):
        return cls("Assembled Robot")

    def __init__(self, name="Robot", age=0):
        self.name = name
        self.age = age
        self.energy = 0

    def display(self):
        print(f"I am {self.name}")


if __name__ == "__main__":
    robot = Robot()
    robot.display()
```

**Output**

```text
I am Robot
```

<a name="c10-magic-methods-str-and-repr-"></a>

### Magic methods: `__str__` and `__repr__`

Printing an object normally shows something unhelpful like `<__main__.Robot object at 0x7f...>`. Two special methods fix that:

- `__str__` returns the **informal**, user-friendly text. It is used by `print(obj)` and `str(obj)`.
- `__repr__` returns the **formal**, developer-oriented text, ideally looking like code that would recreate the object. It is used by `repr(obj)` and when the object appears **inside a list or dict**.

Both must **return** a string, not print one.

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
print(r)
print(repr(r))
print([r, Robot()])
```

**Output**

```text
Robot Bolt is 3 years old.
Robot(name='Bolt', age=3)
[Robot(name='Bolt', age=3), Robot(name='Robot', age=0)]
```

`{self.name!r}` puts the repr of the name (with quotes) into the f-string.

<a name="c10-methods-that-change-state"></a>

### Methods that change state

Methods usually read or update the object's attributes. Keep the rules about valid values inside the class, so no outside code can break them:

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
        # energy must never go above the maximum
        self.energy = min(self.energy + amount, Human.MAX_ENERGY)

    def move(self, distance):
        # energy must never fall below zero
        self.energy = max(self.energy - distance, 0)

    def __str__(self):
        return f"{self.name}, age {self.age}, energy {self.energy}"


h = Human("Ada")
h.move(70)
print(h)
h.eat(500)
print(h)
h.move(1000)
h.grow()
print(h)
```

**Output**

```text
Ada, age 0, energy 30
Ada, age 0, energy 100
Ada, age 1, energy 0
```

**Exercise 10.2: Add behaviour to Robot**

Add `__repr__`, `__str__`, `grow()`, `eat(amount)` and `move(distance)` to your `Robot`, with energy kept between 0 and `MAX_ENERGY`.

**Show solution**

```python
class Robot:
    MAX_ENERGY = 100

    def __init__(self, name="Robot", age=0):
        self.name = name
        self.age = age
        self.energy = 0

    def __repr__(self):
        return f"Robot(name={self.name!r}, age={self.age}, energy={self.energy})"

    def __str__(self):
        return f"Robot {self.name} is {self.age} years old with {self.energy}% energy."

    def grow(self):
        self.age += 1

    def eat(self, amount):
        self.energy = min(self.energy + amount, Robot.MAX_ENERGY)

    def move(self, distance):
        self.energy = max(self.energy - distance, 0)


bot = Robot("Bolt")
bot.eat(80)
bot.move(30)
bot.grow()
print(bot)
print(repr(bot))
```

**Output**

```text
Robot Bolt is 1 years old with 50% energy.
Robot(name='Bolt', age=1, energy=50)
```

<a name="c10-objects-inside-objects-composition"></a>

### Objects inside objects (composition)

An object's attribute can be a list of other objects. A `Planet` **has** inhabitants:

```python
class Human:
    def __init__(self, name="Human"):
        self.name = name

    def __repr__(self):
        return f"Human({self.name!r})"


class Robot:
    def __init__(self, name="Robot"):
        self.name = name

    def __repr__(self):
        return f"Robot({self.name!r})"


class Planet:
    def __init__(self, name):
        self.name = name
        self.inhabitants = {"humans": [], "robots": []}

    def add_human(self, human):
        self.inhabitants["humans"].append(human)

    def remove_human(self, human):
        self.inhabitants["humans"].remove(human)

    def add_robot(self, robot):
        self.inhabitants["robots"].append(robot)

    def remove_robot(self, robot):
        self.inhabitants["robots"].remove(robot)

    def __repr__(self):
        return f"Planet(name={self.name!r}, inhabitants={self.inhabitants!r})"

    def __str__(self):
        humans = len(self.inhabitants["humans"])
        robots = len(self.inhabitants["robots"])
        return f"Planet {self.name} has {humans} humans and {robots} robots."


earth = Planet("Earth")
ada = Human("Ada")
earth.add_human(ada)
earth.add_human(Human("Ben"))
earth.add_robot(Robot("Bolt"))
print(earth)
earth.remove_human(ada)
print(repr(earth))
```

**Output**

```text
Planet Earth has 2 humans and 1 robots.
Planet(name='Earth', inhabitants={'humans': [Human('Ben')], 'robots': [Robot('Bolt')]})
```

The course builds this in two steps: first `humans` and `robots` as two separate list attributes (Activity 4), then one dictionary of lists (Activity 5, shown above). Try writing the two-list version yourself.

**Exercise 10.3: Universe**

Write a class `Universe` with a list of planets and a method `generate()` that creates a planet, adds a random number (1–5) of humans and robots to it, and appends it to the list. Generate three planets and print each.

**Show solution**

```python
import random


class Human:
    def __init__(self, name="Human"):
        self.name = name


class Robot:
    def __init__(self, name="Robot"):
        self.name = name


class Planet:
    def __init__(self, name):
        self.name = name
        self.inhabitants = {"humans": [], "robots": []}

    def add_human(self, human):
        self.inhabitants["humans"].append(human)

    def add_robot(self, robot):
        self.inhabitants["robots"].append(robot)

    def __str__(self):
        return (f"Planet {self.name}: {len(self.inhabitants['humans'])} humans, "
                f"{len(self.inhabitants['robots'])} robots")


class Universe:
    def __init__(self):
        self.planets = []

    def generate(self):
        planet = Planet(f"Planet-{len(self.planets) + 1}")
        for i in range(random.randint(1, 5)):
            planet.add_human(Human())
        for i in range(random.randint(1, 5)):
            planet.add_robot(Robot())
        self.planets.append(planet)


universe = Universe()
for i in range(3):
    universe.generate()
for planet in universe.planets:
    print(planet)
```

**Output**

```text
Planet Planet-1: 3 humans, 2 robots
Planet Planet-2: 4 humans, 1 robots
Planet Planet-3: 1 humans, 5 robots
```

<a name="c10-plotting-data-held-in-objects"></a>

### Plotting data held in objects

Objects are just another data source for charts. Collect the numbers into lists, then plot:

```python
import random
import matplotlib.pyplot as plt


class Planet:
    def __init__(self, name, humans, robots):
        self.name = name
        self.humans = humans
        self.robots = robots


class Universe:
    def __init__(self):
        self.planets = [Planet(f"P{i}", random.randint(1, 9), random.randint(1, 9)) for i in range(1, 6)]

    def show_populations(self, selection):
        names = [p.name for p in self.planets]
        if selection == "human":
            values = [p.humans for p in self.planets]
            title = "Humans per planet"
        elif selection == "robot":
            values = [p.robots for p in self.planets]
            title = "Robots per planet"
        else:
            values = [p.humans + p.robots for p in self.planets]
            title = "Total population per planet"
        plt.bar(names, values)
        plt.title(title)
        plt.xlabel("Planet")
        plt.ylabel("Population")
        plt.show()


Universe().show_populations("all")
```

**Output**

![matplotlib output](images/QHO444_Learn_Python/figure-12.png)

`[p.name for p in self.planets]` is a **list comprehension**: a one-line way to build a list from a loop. It is the same as starting with an empty list and appending `p.name` inside a `for` loop.

**Checkpoint 10**

1.  What is the difference between a class and an object?
2.  A method is defined `def move(self, distance):`. How many arguments do you pass in `bot.move(...)`?
3.  Two objects of the same class. One changes `self.energy`. Does the other's `energy` change? And if the class changes a class attribute?
4.  Which method does `print(obj)` use? Which is used when a list of objects is printed?
5.  A static method gets which automatic first argument?

**Answers**

1.  A class is the blueprint; an object is one instance built from it.
2.  One (`distance`). Python passes `self` for you.
3.  No: instance attributes are per object. Yes: a class attribute is shared, so every object sees the change (unless an object has an instance attribute with the same name).
4.  `__str__` (falling back to `__repr__` if there is none); a printed list uses each item's `__repr__`.
5.  None.

<a name="c10-summary"></a>

### Summary

- `class Name:` defines a blueprint; `Name(args)` creates an object, which calls `__init__`.
- `self.attr = value` in `__init__` creates instance attributes; variables in the class body are class attributes (shared).
- Methods take `self` first. `@classmethod` methods take `cls`; `@staticmethod` methods take neither.
- `__str__` is for users and `__repr__` for developers; both return strings.
- Objects can hold lists or dicts of other objects (composition: a Planet *has* Humans).

<a name="c11-inheritance-and-abstraction"></a>

## Chapter 11: Inheritance and abstraction

**Goals:** read and draw class diagrams; move shared code into a parent class; write child classes that extend and override it; call the parent's initialiser with `super()`; check types with `isinstance`; make abstract classes and abstract methods.

<a name="c11-the-problem-duplicated-classes"></a>

### The problem: duplicated classes

After Chapter 10, `Human` and `Robot` each have `name`, `age`, `energy`, `grow`, `eat` and `move`, written twice. If a bug turns up in `move`, you have to fix it twice and hope you don't miss one. **Inheritance** lets both classes share one copy.

<a name="c11-class-diagrams"></a>

### Class diagrams

A class diagram shows the classes in a program and how they relate. Each class is a box with three parts:

```text
+-------------------------------+
|  Inhabitant  <<abstract>>     |   1. name (and kind)
+-------------------------------+
|  name: str                    |   2. attributes: name and type
|  age: int                     |
|  energy: int                  |
+-------------------------------+
|  grow(): None                 |   3. methods: parameters and return type
|  eat(amount: int): None       |
|  move(distance: int): None    |
+-------------------------------+
```

The arrows between boxes show two kinds of relationship:

| Relationship                     | Meaning                                   | Drawn as                                           | Example                    |
|----------------------------------|-------------------------------------------|----------------------------------------------------|----------------------------|
| **is-a** (inheritance / extends) | the child is a special kind of the parent | solid line, hollow triangle pointing at the parent | a Human *is an* Inhabitant |
| **has-a** (uses / composition)   | one class holds objects of another        | dashed line with an arrow                          | a Planet *has* Inhabitants |

```text
                      +-------------------+
                      |    Inhabitant     |
                      |   <<abstract>>    |
                      +-------------------+
                       ^       ^        ^
              is-a     |       |        |     is-a
           +-----------+  +----+----+   +-----------+
           |   Human   |  |  Robot  |   |   Alien   |- - - -has- - ->  Tech <<abstract>>
           +-----------+  +---------+   +-----------+                   ^        ^
                                                                         |is-a    |is-a
   Planet - - - has 0..* - - -> Inhabitant                            Laser    JetPack
```

<a name="c11-inheritance-in-code"></a>

### Inheritance in code

Put the shared parts in a **parent** (base, super) class, and list the parent in brackets after the **child** (derived, sub) class name:

File: inhabitant.py

```python
class Inhabitant:
    """Everything that every inhabitant has and can do."""

    MAX_ENERGY = 100

    def __init__(self, name="Inhabitant", age=0, energy=MAX_ENERGY):
        self.name = name
        self.age = age
        self.energy = energy

    def __repr__(self):
        return f"{type(self).__name__}(name={self.name!r}, age={self.age}, energy={self.energy})"

    def __str__(self):
        return f"{self.name} is {self.age} years old with {self.energy} energy."

    def grow(self):
        self.age += 1

    def eat(self, amount):
        self.energy = min(self.energy + amount, Inhabitant.MAX_ENERGY)

    def move(self, distance):
        self.energy = max(self.energy - distance, 0)
```

File: human.py

```python
from inhabitant import Inhabitant


class Human(Inhabitant):
    def __init__(self, name="Human", age=0):
        super().__init__(name, age)              # parent sets up name, age, energy

    def display(self):
        print(f"I am {self.name}")
```

File: robot.py

```python
from inhabitant import Inhabitant


class Robot(Inhabitant):
    laws = "Protect, Obey and Survive"

    @staticmethod
    def the_laws():
        print(Robot.laws)

    def __init__(self, name="Robot", age=0):
        super().__init__(name, age, energy=0)    # robots start uncharged

    def display(self):
        print(f"BEEP. I am unit {self.name}")
```

File: test_inheritance.py

```python
from human import Human
from robot import Robot

human = Human("Ada")
robot = Robot("Bolt")
print(repr(human))
human.move(10)               # inherited from Inhabitant
robot.eat(40)                # inherited
human.display()              # Human's own method
robot.display()              # Robot's own version
print(human)
print(robot)
Robot.the_laws()
```

**Output**

```text
Human(name='Ada', age=0, energy=100)
I am Ada
BEEP. I am unit Bolt
Ada is 0 years old with 90 energy.
Bolt is 0 years old with 40 energy.
Protect, Obey and Survive
```

- `class Human(Inhabitant):` means Human **inherits** everything Inhabitant defines.
- `super().__init__(...)` runs the **parent's** initialiser, so the shared setup lives in one place.
- Each child keeps only what is special to it: here, `display` and Robot's laws.
- `type(self).__name__` in the parent's `__repr__` gives the **actual** class name, so one method serves every child.

**How Python finds a method**

When you call `human.move(10)`, Python looks for `move` first on the object, then on its class (`Human`), then on the parent (`Inhabitant`), then on *its* parent, and so on up to the built-in `object` class that everything ultimately inherits from. The first match wins. This search order is the *method resolution order*, which you can see with `Human.__mro__`. It is also why **overriding** works: if `Human` defines its own `move`, Python finds that one first and never reaches the parent's.

<a name="c11-overriding-and-extending"></a>

#### Overriding and extending

A child can **replace** a parent method by defining one with the same name, or **extend** it by calling the parent's version with `super()` and adding to it:

```python
class Inhabitant:
    def __init__(self, name):
        self.name = name
        self.energy = 100

    def move(self, distance):
        self.energy -= distance


class Robot(Inhabitant):
    def move(self, distance):
        print(f"{self.name}: servos engaged")
        super().move(distance * 2)          # robots use double energy


bot = Robot("Bolt")
bot.move(10)
print(bot.energy)
```

**Output**

```text
Bolt: servos engaged
80
```

<a name="c11-isinstance-what-kind-of-object-is-this"></a>

### isinstance: what kind of object is this?

With inheritance, one list can hold different kinds of inhabitant. `isinstance(obj, Class)` tells you whether an object is that class **or a child of it**:

```python
from human import Human
from robot import Robot
from inhabitant import Inhabitant

inhabitants = [Human("Ada"), Robot("Bolt"), Human("Ben"), Robot("Cog")]
num_humans = 0
for inhabitant in inhabitants:
    if isinstance(inhabitant, Human):
        num_humans += 1
print(f"Found {num_humans} humans.")
print(isinstance(inhabitants[1], Inhabitant), isinstance(inhabitants[1], Human))
```

**Output**

```text
Found 2 humans.
True False
```

**Exercise 11.1: Planet with one list**

Rewrite `Planet` so it stores a single list `inhabitants` with `add_inhabitant` and `remove_inhabitant` methods, and a method `count(kind)` that uses `isinstance` to count objects of a given class. Test it with humans and robots.

**Show solution**

```python
from human import Human
from robot import Robot


class Planet:
    def __init__(self, name):
        self.name = name
        self.inhabitants = []

    def add_inhabitant(self, inhabitant):
        self.inhabitants.append(inhabitant)

    def remove_inhabitant(self, inhabitant):
        self.inhabitants.remove(inhabitant)

    def count(self, kind):
        total = 0
        for inhabitant in self.inhabitants:
            if isinstance(inhabitant, kind):
                total += 1
        return total

    def __str__(self):
        return f"{self.name}: {self.count(Human)} humans, {self.count(Robot)} robots"


earth = Planet("Earth")
for name in ["Ada", "Ben", "Cara"]:
    earth.add_inhabitant(Human(name))
bolt = Robot("Bolt")
earth.add_inhabitant(bolt)
print(earth)
earth.remove_inhabitant(bolt)
print(earth)
```

**Output**

```text
Earth: 3 humans, 1 robots
Earth: 3 humans, 0 robots
```

<a name="c11-abstract-classes"></a>

### Abstract classes

"Inhabitant" is a general idea: nobody is *just* an inhabitant, they are a human or a robot or an alien. An **abstract class** expresses that: it exists to be inherited from, and Python refuses to create objects of it directly.

```python
from abc import ABC


class Inhabitant(ABC):
    def __init__(self, name):
        self.name = name


class Human(Inhabitant):
    pass


print(Human("Ada").name)
```

**Output**

```text
Ada
```

Inheriting from `ABC` (Abstract Base Class) marks the class as abstract. On its own that doesn't block creating objects yet. That takes at least one **abstract method**.

<a name="c11-abstract-methods"></a>

#### Abstract methods

An abstract method declares a method's name and parameters **without** an implementation. Any concrete subclass **must** provide one, so the parent can guarantee that every child has, say, `activate()` and `deactivate()`.

File: tech.py

```python
from abc import ABC, abstractmethod


class Tech(ABC):
    """Any piece of alien technology."""

    @abstractmethod
    def activate(self):
        pass

    @abstractmethod
    def deactivate(self):
        pass
```

```python
from tech import Tech

gadget = Tech()
```

**Output (error)**

```text
Traceback (most recent call last):
  File "main.py", line 3, in <module>
    ...
TypeError: Can't instantiate abstract class Tech without an implementation for abstract methods 'activate', 'deactivate'
```

```python
from tech import Tech


class Broken(Tech):
    def activate(self):
        print("on")
    # forgot deactivate


Broken()
```

**Output (error)**

```text
Traceback (most recent call last):
  File "main.py", line 10, in <module>
    ...
TypeError: Can't instantiate abstract class Broken without an implementation for abstract method 'deactivate'
```

**Course material error**

The Week 10 page shows `class Tech:` with `@abstractmethod def activate():`. Without `(ABC)`, Python does **not** enforce the abstract method, and without `self` the method crashes when called on an object. Use `class Tech(ABC):` and `def activate(self):`.

**Exercise 11.2: Alien tech**

Implement `Laser` (with `fire()`) and `JetPack` (with `fly()`) as concrete subclasses of `Tech`, plus an `Alien(Inhabitant)` that **has** a list of tech. Each method just prints a suitable message. Give the alien a `use_all()` method that activates every gadget, and calls `fire()` or `fly()` depending on its type, then deactivates it.

**Show solution**

File: alien_tech.py

```python
from tech import Tech
from inhabitant import Inhabitant


class Laser(Tech):
    def activate(self):
        print("Laser: charging capacitors...")

    def fire(self):
        print("Laser: PEW!")

    def deactivate(self):
        print("Laser: powered down.")


class JetPack(Tech):
    def activate(self):
        print("JetPack: igniting thrusters...")

    def fly(self):
        print("JetPack: whoosh, we have lift-off!")

    def deactivate(self):
        print("JetPack: landing.")


class Alien(Inhabitant):
    def __init__(self, name="Alien", age=0):
        super().__init__(name, age)
        self.tech = []                       # an Alien HAS tech

    def add_tech(self, gadget):
        self.tech.append(gadget)

    def use_all(self):
        for gadget in self.tech:
            gadget.activate()
            if isinstance(gadget, Laser):
                gadget.fire()
            elif isinstance(gadget, JetPack):
                gadget.fly()
            gadget.deactivate()


if __name__ == "__main__":
    zorg = Alien("Zorg")
    zorg.add_tech(Laser())
    zorg.add_tech(JetPack())
    zorg.use_all()
    print(zorg)
```

**Output**

```text
Laser: charging capacitors...
Laser: PEW!
Laser: powered down.
JetPack: igniting thrusters...
JetPack: whoosh, we have lift-off!
JetPack: landing.
Zorg is 0 years old with 100 energy.
```

**Exercise 11.3: Make Inhabitant abstract**

Change `Inhabitant` to inherit from `ABC` and add an abstract method `display(self)`. Confirm that `Human` and `Robot` still work (they both implement `display`) and that `Inhabitant()` is now refused.

**Show solution**

```python
from abc import ABC, abstractmethod


class Inhabitant(ABC):
    def __init__(self, name="Inhabitant"):
        self.name = name

    @abstractmethod
    def display(self):
        pass


class Human(Inhabitant):
    def display(self):
        print(f"I am {self.name}")


Human("Ada").display()
try:
    Inhabitant()
except TypeError as error:
    print("Refused:", error)
```

**Output**

```text
I am Ada
Refused: Can't instantiate abstract class Inhabitant without an implementation for abstract method 'display'
```

<a name="c11-why-bother-polymorphism"></a>

### Why bother? Polymorphism

Because every `Tech` is guaranteed to have `activate()` and `deactivate()`, code can work with *any* gadget without knowing which kind it is:

```python
from alien_tech import Laser, JetPack

for gadget in [Laser(), JetPack(), Laser()]:
    gadget.activate()           # each class's own version runs
```

**Output**

```text
Laser: charging capacitors...
JetPack: igniting thrusters...
Laser: charging capacitors...
```

That is **polymorphism** ("many shapes"): one method call, different behaviour depending on the object's class. It lets you add a new gadget class later without changing any of the code that uses gadgets.

**Checkpoint 11**

1.  In a class diagram, what does a solid line with a hollow triangle mean? And a dashed arrow?
2.  `class B(A):` and `B` defines no `__init__`. What happens when you call `B()`?
3.  Why call `super().__init__(...)` in a child's `__init__`?
4.  `class Shape(ABC)` has an abstract method `area`. Can you create `Shape()`? Can you create `Square()` if `Square(Shape)` doesn't define `area`?
5.  `isinstance(Robot(), Inhabitant)` when `Robot` inherits from `Inhabitant`?

**Answers**

1.  Inheritance (is-a); has-a / uses.
2.  Python uses `A`'s `__init__`.
3.  So the parent's set-up code runs, keeping the shared attributes defined in one place. Without it the child's `__init__` *replaces* the parent's, and those attributes never get created.
4.  No, and no. Both raise `TypeError` until `area` is implemented.
5.  `True`

<a name="c11-summary"></a>

### Summary

- Class diagrams show each class as name / attributes / methods; solid hollow-triangle arrows are *is-a*, dashed arrows are *has-a*.
- `class Child(Parent):` inherits; `super().__init__(...)` runs the parent's set-up; same-named methods override.
- `isinstance(obj, Class)` is true for the class and any of its parents.
- `class X(ABC):` plus `@abstractmethod` makes a class that can't be instantiated and forces subclasses to implement those methods.
- Polymorphism: the same call (`gadget.activate()`) does the right thing for each class.

<a name="c12-case-studies-titanic-and-olympics"></a>

## Chapter 12: Case studies: Titanic and Olympics

**Goals:** turn a written specification into a list of functions before coding; build a menu-driven data program step by step; split a program into `tui`, `process` and `main` modules; spot and fix errors in a spec.

Both case studies are the module's bonus Week 11 material, and they combine everything so far. The examples here run against small sample files in the same format as the real datasets. The real files (891 Titanic passengers, about 271,000 Olympic rows) give the larger numbers quoted from the SOL pages.

<a name="c12-how-to-attack-a-specification"></a>

### How to attack a specification

Before writing any code:

1.  **Highlight every name** the spec dictates: file names, function names, parameter names, variable names, exact messages. Markers (and automated tests) check these literally.
2.  **List the functions** in a table: name, parameters, what it returns or prints.
3.  **Note the data**: which columns, which types, what can be missing.
4.  **Build in thin slices**: get loading working and print the count, commit, then add the menu, commit, then one option at a time, committing after each.
5.  **Test each slice** against the expected output in the spec before moving on.

<a name="c12-case-study-1-titanic"></a>

### Case study 1: Titanic

<a name="c12-the-data"></a>

#### The data

`titanic.csv` has one row per passenger with these columns:

| Index | Column                                      | Example                     | Notes                             |
|-------|---------------------------------------------|-----------------------------|-----------------------------------|
| 0     | PassengerId                                 | `1`                         |                                   |
| 1     | Survived                                    | `0` / `1`                   | 1 = survived                      |
| 2     | Pclass                                      | `1`, `2`, `3`               | ticket class                      |
| 3     | Name                                        | `"Braund, Mr. Owen Harris"` | **contains commas, so use `csv`** |
| 4     | Sex                                         | `male` / `female`           |                                   |
| 5     | Age                                         | `22`, `0.42`, *empty*       | **decimals and blanks**           |
| 6–11  | SibSp, Parch, Ticket, Fare, Cabin, Embarked |                             | not used here                     |

<a name="c12-the-spec-as-a-function-list"></a>

#### The spec as a function list

| Function                           | Parameters  | Does                                                                                                  |
|------------------------------------|-------------|-------------------------------------------------------------------------------------------------------|
| (globals)                          |             | `records = []`, `headings = []`                                                                       |
| `load_data`                        | `file_path` | prints `Loading data...`, reads headings into `headings` and every row into `records`, prints `Done!` |
| `display_menu`                     | none        | prints options 1–5, reads an int, **returns** it                                                      |
| `display_passenger_names`          | none        | prints every name                                                                                     |
| `display_num_survivors`            | none        | counts `Survived == 1` and prints `{n} passengers survived`                                           |
| `display_passengers_per_gender`    | none        | prints `females: {f}, males: {m}`                                                                     |
| `display_passengers_per_age_group` | none        | children \< 18, adults \< 65, elderly otherwise; skips missing ages                                   |
| `display_survivors_per_age_group`  | none        | the challenge: survivors / total per group                                                            |
| `run`                              | none        | calls `load_data`, prints the count, shows the menu, dispatches on the option                         |

**Two bugs in the SOL spec, fixed here**

1.  **Age groups.** The page says "if age is below 18 → children; **if** age is below 65 → adults; otherwise elderly". As written, a 10-year-old is counted as a child **and** an adult. The second test must be `elif`, which is what the page's own expected output (113 / 590 / 11) assumes.
2.  **Age type.** Ages like `0.42` and `14.5` exist, so `int(age)` crashes. Use `float(age)`.

<a name="c12-build-it"></a>

#### Build it

**Exercise 12.1: Titanic, slice by slice**

Build `titanic.py` in this order, running and committing after each step:

1.  globals + `load_data` + `run` that prints `Successfully loaded {n} records.`
2.  `display_menu`, with `run` printing `You have selected option: {n}`
3.  options 1 to 4, each in its own function, dispatched with `if/elif/else` in `run` (with `Error! Option not recognised!` for anything else)
4.  option 5, the challenge: print `children: 61/113, adults: 228/590, elderly: 1/11` (those are the real-dataset numbers)

**Complete solution**

File: titanic.py

```python
import csv

records = []
headings = []


def load_data(file_path):
    global headings
    print("Loading data...", end="")
    with open(file_path) as file:
        reader = csv.reader(file)
        headings = next(reader)
        for values in reader:
            records.append(values)
    print("Done!")


def display_menu():
    print("""
Please select one of the following options:
[1] Display the names of all passengers
[2] Display the number of passengers that survived
[3] Display the number of passengers per gender
[4] Display the number of passengers per age group
[5] Display the number of survivors per age group
""")
    return int(input())


def display_passenger_names():
    print("The names of the passengers are...")
    for record in records:
        passenger_name = record[3]
        print(passenger_name)


def display_num_survivors():
    num_survived = 0
    for record in records:
        survival_status = int(record[1])
        if survival_status == 1:
            num_survived += 1
    print(f"{num_survived} passengers survived")


def display_passengers_per_gender():
    females = 0
    males = 0
    for record in records:
        gender = record[4]
        if gender == "male":
            males += 1
        elif gender == "female":
            females += 1
    print(f"females: {females}, males: {males}")


def age_group(age):
    """Return the name of the group a (float) age belongs to."""
    if age < 18:
        return "children"
    elif age < 65:
        return "adults"
    else:
        return "elderly"


def display_passengers_per_age_group():
    counts = {"children": 0, "adults": 0, "elderly": 0}
    for record in records:
        if record[5] != "":
            counts[age_group(float(record[5]))] += 1
    print(f"children: {counts['children']}, adults: {counts['adults']}, elderly: {counts['elderly']}")


def display_survivors_per_age_group():
    totals = {"children": 0, "adults": 0, "elderly": 0}
    survivors = {"children": 0, "adults": 0, "elderly": 0}
    for record in records:
        if record[5] == "":
            continue
        group = age_group(float(record[5]))
        totals[group] += 1
        if record[1] == "1":
            survivors[group] += 1
    parts = [f"{group}: {survivors[group]}/{totals[group]}" for group in totals]
    print(", ".join(parts))


def run():
    load_data("titanic.csv")
    print(f"Successfully loaded {len(records)} records.")
    selected_option = display_menu()
    print(f"You have selected option: {selected_option}")
    if selected_option == 1:
        display_passenger_names()
    elif selected_option == 2:
        display_num_survivors()
    elif selected_option == 3:
        display_passengers_per_gender()
    elif selected_option == 4:
        display_passengers_per_age_group()
    elif selected_option == 5:
        display_survivors_per_age_group()
    else:
        print("Error! Option not recognised!")


if __name__ == "__main__":
    run()
```

**Output**

```text
Loading data...Done!
Successfully loaded 15 records.

Please select one of the following options:
[1] Display the names of all passengers
[2] Display the number of passengers that survived
[3] Display the number of passengers per gender
[4] Display the number of passengers per age group
[5] Display the number of survivors per age group

5 ↵
You have selected option: 5
children: 3/4, adults: 5/9, elderly: 0/1
```

Notice the small helper `age_group(age)`. Options 4 and 5 both need the same age rule, so it lives in **one** place. If the rule changes, you change one function.

<a name="c12-what-to-improve"></a>

#### What to improve

The spec's design works but has weaknesses you should be able to point out:

- **Globals.** Every function depends on the hidden `records` variable. Passing `records` in as a parameter makes each function testable on its own.
- **Printing and computing are mixed.** `display_num_survivors` both counts and prints. Splitting it into `count_survivors(records)` (returns a number) and a separate display step lets the count be reused, for example in a chart.
- **The menu runs once.** A `while True` loop with an exit option is friendlier.
- **No input validation.** Typing `abc` at the menu crashes `int(input())`.

The Olympics case study fixes most of these.

<a name="c12-case-study-2-olympics-three-modules"></a>

### Case study 2: Olympics, three modules

<a name="c12-the-design"></a>

#### The design

The program is split by **responsibility**, which is the architecture AE2's template also uses:

```text
             ┌─────────────────────────┐
             │         main.py         │   controls the flow:
             │  read_data(), run()     │   load, loop, dispatch
             └───────┬────────┬────────┘
          imports    │        │   imports
       ┌─────────────▼─┐   ┌──▼──────────────┐
       │    tui.py     │   │   process.py    │
       │ all input and │◀──│ all calculations│
       │ all output    │   │ (calls tui to   │
       └───────────────┘   │  show results)  │
                           └─────────────────┘
```

| Module                         | Rule                                                           |
|--------------------------------|----------------------------------------------------------------|
| `tui.py` (text user interface) | the **only** place that calls `print` or `input`               |
| `process.py`                   | takes data as parameters, computes, uses `tui` to show results |
| `main.py`                      | reads the file, runs the menu loop, calls `process`            |

<a name="c12-the-data_1"></a>

#### The data

| Index | Column   | Index | Column                                    |
|-------|----------|-------|-------------------------------------------|
| 0     | ID       | 8     | Games                                     |
| 1     | Name     | 9     | **Year**                                  |
| 2     | Sex      | 10    | Season                                    |
| 3     | Age      | 11    | City                                      |
| 4     | Height   | 12    | Sport                                     |
| 5     | Weight   | 13    | Event                                     |
| 6     | **Team** | 14    | **Medal** (`Gold`/`Silver`/`Bronze`/`NA`) |
| 7     | NOC      |       |                                           |

**Two typos in the SOL page**

- The heading for the team display function reads `def display_medal_tally(team_tally):`. Its name is `display_team_medal_tally`.
- The example `{"United Kingdom", {"Gold": 10, ...}}` uses a comma, which would make a **set**. A dictionary needs a colon: `{"United Kingdom": {"Gold": 10, ...}}`.

**Exercise 12.2: Olympics**

Build the three modules from the spec: `tui.py` with `started(msg="")`, `completed()`, `error(msg)`, `menu()`, `display_medal_tally(tally)`, `display_team_medal_tally(team_tally)` and `display_years(years)`; `process.py` with `list_years(data)`, `tally_medals(data)` and `tally_team_medals(data)`; and `main.py` with `read_data(file_path)` and the `run()` loop (options `years`, `tally`, `team`, `exit`).

**tui.py**

File: tui.py

```python
"""Text user interface: every print and input in the program lives here."""

LINE = "-" * 60


def started(msg=""):
    print(LINE)
    print(f"Operation started: {msg}...\n")


def completed():
    print("\nOperation completed.")
    print(LINE)


def error(msg):
    print(f"Error! {msg}")


def menu():
    print("Please select one of the following options:")
    print(f"{'[years]':<10}List unique years")
    print(f"{'[tally]':<10}Tally up medals")
    print(f"{'[team]':<10}Tally up medals for each team")
    print(f"{'[exit]':<10}Exit the program")
    return input("Your selection: ").strip().lower()


def display_medal_tally(tally):
    print(f"| {'Gold':<8} | {tally['Gold']:>6} |")
    print(f"| {'Silver':<8} | {tally['Silver']:>6} |")
    print(f"| {'Bronze':<8} | {tally['Bronze']:>6} |")


def display_team_medal_tally(team_tally):
    for team, medals in team_tally.items():
        print(team)
        print(f"\tGold:{medals['Gold']}, Silver:{medals['Silver']}, Bronze:{medals['Bronze']}")


def display_years(years):
    for year in sorted(years, reverse=True):
        print(year)
```

**process.py**

File: process.py

```python
"""Processing: functions receive the data, compute, and use tui to show results."""
import tui

YEAR, TEAM, MEDAL = 9, 6, 14            # column indexes, named once


def list_years(data):
    tui.started("Listing years")
    years = set()
    for record in data:
        years.add(int(record[YEAR]))
    tui.display_years(years)
    tui.completed()
    return years


def tally_medals(data):
    tui.started("Tallying medals")
    tally = {"Gold": 0, "Silver": 0, "Bronze": 0}
    for record in data:
        medal = record[MEDAL]
        if medal in tally:
            tally[medal] += 1
    tui.display_medal_tally(tally)
    tui.completed()
    return tally


def tally_team_medals(data):
    tui.started("Tallying medals for each team")
    team_tally = {}
    for record in data:
        team, medal = record[TEAM], record[MEDAL]
        if team not in team_tally:
            team_tally[team] = {"Gold": 0, "Silver": 0, "Bronze": 0}
        if medal in team_tally[team]:
            team_tally[team][medal] += 1
    tui.display_team_medal_tally(team_tally)
    tui.completed()
    return team_tally
```

**main.py**

File: main.py

```python
import csv
import process
import tui


def read_data(file_path):
    tui.started(f"Reading data from {file_path}")
    data = []
    with open(file_path) as file:
        reader = csv.reader(file)
        next(reader)                       # skip the headings
        for line in reader:
            data.append(line)
    tui.completed()
    return data


def run():
    athlete_data = read_data("athlete_events.csv")
    while True:
        selection = tui.menu()
        if selection == "years":
            process.list_years(athlete_data)
        elif selection == "tally":
            process.tally_medals(athlete_data)
        elif selection == "team":
            process.tally_team_medals(athlete_data)
        elif selection == "exit":
            break
        else:
            tui.error("Invalid Selection!")


if __name__ == "__main__":
    run()
```

**Output**

```text
------------------------------------------------------------
Operation started: Reading data from athlete_events.csv...


Operation completed.
------------------------------------------------------------
Please select one of the following options:
[years]   List unique years
[tally]   Tally up medals
[team]    Tally up medals for each team
[exit]    Exit the program
Your selection: years ↵
------------------------------------------------------------
Operation started: Listing years...

2016
2014
1996
1994
1952
1912
1900

Operation completed.
------------------------------------------------------------
Please select one of the following options:
[years]   List unique years
[tally]   Tally up medals
[team]    Tally up medals for each team
[exit]    Exit the program
Your selection: tally ↵
------------------------------------------------------------
Operation started: Tallying medals...

| Gold     |      3 |
| Silver   |      2 |
| Bronze   |      2 |

Operation completed.
------------------------------------------------------------
Please select one of the following options:
[years]   List unique years
[tally]   Tally up medals
[team]    Tally up medals for each team
[exit]    Exit the program
Your selection: medals ↵
Error! Invalid Selection!
Please select one of the following options:
[years]   List unique years
[tally]   Tally up medals
[team]    Tally up medals for each team
[exit]    Exit the program
Your selection: team ↵
------------------------------------------------------------
Operation started: Tallying medals for each team...

Finland
    Gold:2, Silver:0, Bronze:1
Norway
    Gold:0, Silver:1, Bronze:1
Denmark/Sweden
    Gold:1, Silver:0, Bronze:0
Tonga
    Gold:0, Silver:1, Bronze:0

Operation completed.
------------------------------------------------------------
Please select one of the following options:
[years]   List unique years
[tally]   Tally up medals
[team]    Tally up medals for each team
[exit]    Exit the program
Your selection: exit ↵
```

<a name="c12-why-this-structure-is-better"></a>

#### Why this structure is better

- **Single responsibility.** To change how the menu looks, you only touch `tui.py`. To change how medals are counted, you only touch `process.py`.
- **Testable.** `process.tally_medals(some_list)` can be tested with a hand-made three-row list; no file and no user are needed.
- **Parameters and return values** carry the data. Nothing depends on hidden globals.
- **Named constants** (`YEAR`, `TEAM`, `MEDAL`) replace magic numbers like `row[14]`, so the code explains itself.
- `main.py` reads like a summary of the program.

**Going further (practice, not AE2)**

Extend the Olympics program yourself: add an option that charts the medal tally with matplotlib (the chart code belongs in a fourth module dedicated to visuals); add `[sport]`, which asks for a sport and lists the years it was held; validate the menu input in `tui.menu()` and loop until it is valid. Commit each feature separately.

**Checkpoint 12**

1.  In the three-module design, which module may call `input()`?
2.  Why is `age_group(age)` a separate function in the Titanic solution?
3.  What goes wrong if the Titanic loader uses `line.split(",")`?
4.  In `tally_team_medals`, why check `if medal in team_tally[team]` before incrementing?
5.  Name two weaknesses of using global variables in the Titanic design.

**Answers**

1.  Only `tui.py`.
2.  Two options use the same rule; keeping it in one function avoids duplicated logic and makes the rule easy to change and test.
3.  Names like `"Braund, Mr. Owen Harris"` split into extra columns, so every later index is wrong.
4.  To skip `"NA"`. Otherwise `team_tally[team]["NA"] += 1` raises a `KeyError`.
5.  Functions depend on hidden state, which makes them hard to test or reuse; any function can change the data unexpectedly; the data can't easily be passed to other modules.

<a name="c13-problem-solving-testing-debugging-and-professional-practice"></a>

## Chapter 13: Problem solving, testing, debugging and professional practice

**Goals:** follow a problem-solving process from requirements to evaluation; plan with decomposition, pseudocode and flowcharts; test systematically; debug efficiently; write PEP-8 code; recognise legal, social, ethical and professional (LSEP) issues; document your work.

<a name="c13-a-problem-solving-process"></a>

### A problem-solving process

The module's first learning outcome asks you to *describe a problem-solving process and its value*. A common version has five stages that loop:

```text
   ┌──────────────┐    ┌──────────┐    ┌───────────┐    ┌────────┐    ┌────────────┐
   │ 1 Understand │──▶│ 2 Plan   │──▶│ 3 Build   │──▶│ 4 Test │──▶│ 5 Evaluate │
   │  the problem │    │ (design) │    │ (code)    │    │& debug │    │ & reflect  │
   └──────────────┘    └──────────┘    └───────────┘    └────────┘    └─────┬──────┘
          ▲                                                                  │
          └──────────────────────── improve and repeat ◀────────────────────┘
```

1.  **Understand.** What are the inputs, the outputs and the rules? What do the data look like (types, missing values, odd cases)? Restate the requirement in your own words.
2.  **Plan.** Break the problem into sub-problems (**decomposition**) until each is a single function. Spot repeated patterns (**pattern recognition**: "this is another *count per group*"). Ignore irrelevant detail (**abstraction**). Write the steps as pseudocode or a flowchart (**algorithm design**).
3.  **Build** in small slices, running after each one.
4.  **Test** each slice against expected results, including edge cases. **Debug** what fails.
5.  **Evaluate.** Does it meet every requirement? What would you improve? This is the material for the reflective part of a report.

Its value: it turns a vague task into small certain steps, catches misunderstandings before they cost hours of coding, and leaves evidence (plans, tests, commits) that others can check.

<a name="c13-decomposition-example"></a>

#### Decomposition example

> *"Show how many passengers in each class survived, as a chart."*

```text
survival chart
├── load the data              -> load_data(path) returns list of rows
├── count per class
│   ├── totals per class       -> dictionary: class -> count
│   └── survivors per class    -> dictionary: class -> count
├── turn counts into rates     -> list of percentages, same order as labels
└── draw the chart             -> bar chart, title, axis labels, show
```

Each leaf becomes one small function with clear inputs and outputs.

<a name="c13-pseudocode"></a>

#### Pseudocode

Pseudocode is structured English halfway to code. It has no strict syntax, but it should be precise enough that turning it into Python is mechanical:

```text
FUNCTION count_per_group(rows, column)
    counts <- empty dictionary
    FOR EACH row IN rows
        key <- row[column]
        IF key NOT IN counts THEN counts[key] <- 0
        counts[key] <- counts[key] + 1
    RETURN counts
```

<a name="c13-flowcharts"></a>

#### Flowcharts

| Shape             | Means                                 |
|-------------------|---------------------------------------|
| rounded rectangle | start / end                           |
| parallelogram     | input / output                        |
| rectangle         | process (a calculation or assignment) |
| diamond           | decision (yes/no question)            |
| arrows            | flow of control                       |

A loop in a flowchart is simply an arrow that goes back up to an earlier decision diamond.

<a name="c13-testing"></a>

### Testing

**Testing** checks that the program does what the requirements say. **Debugging** finds out *why* it doesn't.

<a name="c13-a-test-table"></a>

#### A test table

Plan tests before you run them, and record the results. This table is exactly the kind of evidence a report can include:

| \#  | What is tested     | Input              | Expected                           | Actual              | Pass?                 |
|-----|--------------------|--------------------|------------------------------------|---------------------|-----------------------|
| 1   | valid menu choice  | `2`                | "Option 2 selected", runs option 2 | as expected         | ✓                     |
| 2   | choice with spaces | `2`                | accepted as 2                      | "Invalid choice"    | ✗ fixed: `.strip()`   |
| 3   | invalid choice     | `9`                | error message, menu shown again    | as expected         | ✓                     |
| 4   | non-numeric input  | `abc`              | error message, no crash            | crash: `ValueError` | ✗ fixed: `try/except` |
| 5   | missing data value | row with blank age | row skipped                        | as expected         | ✓                     |

<a name="c13-what-to-test"></a>

#### What to test

- **Normal** data: typical values.
- **Boundary** data: the edges of every rule (`17`, `18`, `64`, `65` for age groups; `0`; the first and last item).
- **Erroneous** data: wrong type, empty, a misspelled option, upper/lower case, extra spaces.
- **Every path:** each branch of every `if`, each menu option, and the exit.

<a name="c13-quick-automatic-checks-with-assert"></a>

#### Quick automatic checks with `assert`

`assert condition` does nothing if the condition is true and crashes loudly if it is false. It is a cheap way to re-check pure functions after every change:

```python
def age_group(age):
    if age < 18:
        return "children"
    elif age < 65:
        return "adults"
    return "elderly"


assert age_group(0.42) == "children"
assert age_group(17.9) == "children"
assert age_group(18) == "adults"
assert age_group(64) == "adults"
assert age_group(65) == "elderly"
print("All age_group tests passed")
```

**Output**

```text
All age_group tests passed
```

This only works on functions that **return** values, which is one more reason to separate computing from printing.

<a name="c13-debugging"></a>

### Debugging

<a name="c13-reading-a-traceback"></a>

#### Reading a traceback

```python
def average(values):
    return sum(values) / len(values)


def report(groups):
    for name, values in groups.items():
        print(name, average(values))


report({"Red": [72, 88], "Blue": []})
```

**Output (error)**

```text
Red 80.0
```

```text
Traceback (most recent call last):
  File "main.py", line 2, in average
    ...
ZeroDivisionError: division by zero
```

Read from the **bottom**: the last line is the error type and message, and the `File …, line …` lines above it show the chain of calls that led there, with the most recent last. Fix the cause (here, an empty group), not the symptom.

<a name="c13-strategies-in-the-order-to-try-them"></a>

#### Strategies, in the order to try them

1.  **Read the error message** completely. Look the error up in the Reference's *Error lookup*.
2.  **Print the values.** `print(repr(x), type(x))` just before the failing line. `repr` reveals hidden spaces, `\n`, and `'5'` versus `5`.
3.  **Shrink the problem.** Copy the failing function into a scratch file with a tiny hand-made input. If you can reproduce the bug in 5 lines, you can understand it.
4.  **Use the debugger.** In PyCharm, click in the left gutter to set a breakpoint (red dot), then run with *Debug*. Execution pauses there, and the Variables panel shows every value. Press `F8` to step over a line or `F7` to step into a function.
5.  **Rubber-duck it.** Explain the code line by line, out loud, to an object. Saying what each line *actually* does (not what you meant it to do) usually reveals the bug.
6.  **Check your assumptions about the data.** Print the first few rows. Are the columns where you think? Are the numbers really numbers?
7.  **Commit before big changes**, so you can always get back to a working version with `git restore` or by checking out an earlier commit.

<a name="c13-writing-professional-code-pep-8"></a>

### Writing professional code: PEP-8

PEP-8 is Python's style guide. PyCharm checks it as you type: a wavy underline or a yellow mark in the right gutter is a warning, and `Ctrl+Alt+L` (`Cmd+Opt+L` on a Mac) reformats a file automatically.

| Area        | Rule                                                                                                                                   |
|-------------|----------------------------------------------------------------------------------------------------------------------------------------|
| Indentation | 4 spaces per level, never tabs                                                                                                         |
| Line length | at most 79 characters (PyCharm's default limit is 120); break long lines inside brackets                                               |
| Blank lines | 2 around top-level functions and classes; 1 between methods                                                                            |
| Imports     | at the top, one per line: standard library first, then third-party, then your own modules                                              |
| Names       | `snake_case` for variables and functions, `CapWords` for classes, `UPPER_CASE` for constants; descriptive, never `l`, `O` or `I` alone |
| Spaces      | around `=` and operators (`x = a + b`), after commas, **not** inside brackets, **not** around `=` in keyword arguments (`end=""`)      |
| Comments    | `#` plus a space, saying *why*; keep them up to date; docstrings `"""..."""` for every function and class                              |
| Comparisons | `if x is None:`, `if not items:`, `if found:`, never `== True`                                                                         |

```python
# Not PEP-8
def CalcAvg(L):
  t=0
  for i in L:t+=i
  return t/len(L)


# PEP-8
def calculate_average(values):
    """Return the mean of a non-empty list of numbers."""
    total = 0
    for value in values:
        total += value
    return total / len(values)
```

<a name="c13-code-quality-beyond-style"></a>

### Code quality beyond style

- **One function, one job.** If you need "and" to describe it, split it.
- **No magic numbers.** `MEDAL = 14` then `row[MEDAL]` explains itself; `row[14]` doesn't.
- **Don't repeat yourself.** The same three lines in two places belong in a function.
- **Parameters in, return values out.** Avoid globals.
- **Separate concerns.** Input and output in one module, processing in another, flow control in a third.
- **Handle predictable errors** (bad input, missing file) with validation or `try/except`, with a helpful message.
- **User-friendly output:** consistent headings, aligned columns, clear prompts, confirmation of what the user chose.

<a name="c13-legal-social-ethical-and-professional-issues"></a>

### Legal, social, ethical and professional issues

Even a small data-analysis program raises LSEP questions. A strong report names specific ones that apply to *its* program, not a generic list.

| Area                                            | Questions to ask about your program                                                                                                                                            |
|-------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Legal: data protection** (DPA 2018 / UK GDPR) | Does the data identify people (names, IDs, locations combined with dates)? Is it the minimum needed? Is it stored and shared securely?                                         |
| **Legal: Computer Misuse Act 1990**             | Do I have permission to access every system and dataset I use?                                                                                                                 |
| **Legal: copyright and licences**               | What licence does the dataset have? Am I allowed to redistribute it? Do I credit the source? Which licence did I give my repository?                                           |
| **Social**                                      | Who might be affected by conclusions drawn from this data? Could a chart be misread?                                                                                           |
| **Ethical: bias and representativeness**        | Who is missing from the data? Survey and feedback data come only from people who chose to respond, and some groups may be over- or under-represented. Do I state these limits? |
| **Ethical: honesty**                            | Are my charts honest (axes starting at zero, nothing cherry-picked)? Do I report what doesn't work?                                                                            |
| **Professional**                                | Version control used throughout, readable PEP-8 code, comments, testing evidence, meeting deadlines, citing sources, using AI only as permitted by the brief.                  |

<a name="c13-documenting-your-work"></a>

### Documenting your work

Typical supporting evidence for a programming assessment:

- **A requirements checklist**: each task marked completed, attempted but incomplete, or not attempted, honestly.
- **Version-control evidence**: screenshots of your GitHub commit history (newest and oldest commits, with your username visible). Many small commits with clear messages, spread over weeks, show a professional process. One giant commit the night before shows the opposite.
- **Style evidence**: a PyCharm screenshot showing no PEP-8 warnings, or the remaining ones with a short explanation.
- **Design evidence**: a class diagram for any OOP part (boxes with name / attributes / methods, inheritance and has-a arrows).
- Optionally, depending on the brief: test tables, pseudocode or flowcharts, and a short evaluation.

**Read the brief's own list**

Each assessment brief says exactly what its document must contain, and sometimes says "and no more". Follow that list precisely. Extra material can cost marks or simply be ignored.

**Checkpoint 13**

1.  Name the five stages of the problem-solving process used here.
2.  For the rule "under 18 is a child", which ages are the boundary tests?
3.  Why does `print(repr(value))` beat `print(value)` when debugging?
4.  Which PEP-8 naming style is used for constants?
5.  Give one ethical issue specific to analysing a voluntary online poll.

**Answers**

1.  Understand, plan, build, test and debug, evaluate.
2.  17 (or 17.9) and 18, plus something like 0 and a decimal such as 0.42.
3.  It shows quotes, spaces and `\n`, so `'5'` and `5`, or `'Paris '` and `'Paris'`, look different.
4.  `UPPER_CASE_WITH_UNDERSCORES`
5.  Self-selection bias: respondents aren't a representative sample (people with strong opinions respond more, and some groups are under-represented), so conclusions should be stated cautiously.

<a name="c14-glossary"></a>

## Appendix: Glossary

| Term                                | Meaning                                                                                                                          |
|-------------------------------------|----------------------------------------------------------------------------------------------------------------------------------|
| **abstract class**                  | a class that can't be instantiated, only inherited from; in Python it inherits from `ABC` and has at least one `@abstractmethod` |
| **abstraction**                     | hiding detail so you can use something (a function, a class) without knowing how it works inside                                 |
| **accumulator**                     | a variable that builds up a total in a loop (`total += value`)                                                                   |
| **argument**                        | a value passed to a function when calling it                                                                                     |
| **assignment**                      | binding a name to a value with `=`                                                                                               |
| **attribute**                       | a value stored on an object (`self.name`); class attributes are shared, instance attributes are per object                       |
| **boolean**                         | `True` or `False`                                                                                                                |
| **bug**                             | a mistake that makes a program behave incorrectly                                                                                |
| **built-in function**               | a function that comes with Python (`print`, `len`, `range`)                                                                      |
| **call stack**                      | the chain of function calls currently running                                                                                    |
| **class**                           | a blueprint defining the attributes and methods of a kind of object                                                              |
| **class method**                    | a method marked `@classmethod` that receives the class (`cls`)                                                                   |
| **comment**                         | text after `#` that Python ignores                                                                                               |
| **commit**                          | a saved snapshot in Git, with a message                                                                                          |
| **composition**                     | a "has-a" relationship: an object holding other objects                                                                          |
| **concatenation**                   | joining strings (or lists, tuples) with `+`                                                                                      |
| **condition**                       | an expression that evaluates to `True` or `False`                                                                                |
| **counter**                         | a variable that goes up by one each time something happens                                                                       |
| **CSV**                             | comma-separated values, a plain-text table format                                                                                |
| **current working directory (cwd)** | the folder relative paths start from                                                                                             |
| **data structure**                  | an organised collection of values (list, tuple, set, dict)                                                                       |
| **debugging**                       | finding and fixing the cause of a bug                                                                                            |
| **decomposition**                   | breaking a problem into smaller sub-problems                                                                                     |
| **dictionary**                      | a mapping of unique keys to values                                                                                               |
| **docstring**                       | a string at the top of a function or class that documents it                                                                     |
| **escape sequence**                 | a backslash code inside a string, such as `\n`                                                                                   |
| **exception**                       | an error raised while a program runs (`ValueError`, `KeyError`, …)                                                               |
| **f-string**                        | a string prefixed `f` with `{expressions}` inserted                                                                              |
| **float**                           | a decimal number                                                                                                                 |
| **function**                        | a named, reusable block of code                                                                                                  |
| **global variable**                 | a variable defined at the top level of a module                                                                                  |
| **hashing**                         | computing a number from a value to store and find it quickly (sets, dict keys)                                                   |
| **IDE**                             | Integrated Development Environment, such as PyCharm                                                                              |
| **immutable**                       | can't be changed after creation (str, int, float, tuple)                                                                         |
| **import**                          | loading a module so you can use its contents                                                                                     |
| **index**                           | the position of an item in a sequence, starting at 0                                                                             |
| **inheritance**                     | an "is-a" relationship: a child class reuses and extends a parent class                                                          |
| **initialiser**                     | `__init__`, the method that sets up a new object                                                                                 |
| **instance**                        | one object created from a class                                                                                                  |
| **integer**                         | a whole number (`int`)                                                                                                           |
| **iterable**                        | anything a `for` loop can go through                                                                                             |
| **iteration**                       | one pass of a loop                                                                                                               |
| **JSON**                            | JavaScript Object Notation, a text format for nested data                                                                        |
| **keyword argument**                | an argument passed by name (`sep="-"`)                                                                                           |
| **lambda**                          | a small unnamed function written inline: `lambda x: x[1]`                                                                        |
| **library**                         | a collection of modules (matplotlib is a third-party library)                                                                    |
| **list**                            | an ordered, mutable sequence                                                                                                     |
| **list comprehension**              | `[expr for item in items if condition]`, building a list in one line                                                             |
| **local variable**                  | a variable created inside a function, existing only there                                                                        |
| **magic method**                    | a method with double underscores that Python calls automatically (`__init__`, `__str__`, `__repr__`)                             |
| **method**                          | a function defined inside a class                                                                                                |
| **modulo**                          | `%`, the remainder after division                                                                                                |
| **module**                          | a `.py` file whose contents can be imported                                                                                      |
| **mutable**                         | can be changed in place (list, dict, set)                                                                                        |
| **nested**                          | one structure inside another of the same kind (a loop in a loop, a dict in a dict)                                               |
| **None**                            | Python's "no value", returned by functions without a `return`                                                                    |
| **object**                          | a bundle of data (attributes) and behaviour (methods)                                                                            |
| **OOP**                             | object-oriented programming                                                                                                      |
| **overriding**                      | a child class redefining a method it inherited                                                                                   |
| **parameter**                       | a variable named in a function definition that receives an argument                                                              |
| **PEP-8**                           | Python's official style guide                                                                                                    |
| **polymorphism**                    | the same method call behaving differently for different classes                                                                  |
| **procedural programming**          | organising a program as functions acting on separate data                                                                        |
| **pseudocode**                      | structured plain-language description of an algorithm                                                                            |
| **push**                            | uploading local commits to a remote repository (GitHub)                                                                          |
| **repository**                      | a project folder tracked by Git                                                                                                  |
| **return value**                    | the value a function hands back with `return`                                                                                    |
| **scope**                           | where in the code a name can be used                                                                                             |
| **sentinel**                        | a special input value that ends a loop (`"quit"`)                                                                                |
| **set**                             | an unordered collection of unique items                                                                                          |
| **slice**                           | part of a sequence: `items[start:stop:step]`                                                                                     |
| **staging**                         | choosing which changes go in the next commit (`git add`)                                                                         |
| **static method**                   | a method marked `@staticmethod` that receives neither the object nor the class                                                   |
| **string**                          | a sequence of characters (`str`)                                                                                                 |
| **syntax error**                    | a grammar mistake that stops the program from running at all                                                                     |
| **traceback**                       | Python's error report, showing the call chain and the error                                                                      |
| **tuple**                           | an ordered, immutable sequence                                                                                                   |
| **type**                            | the kind of a value (`int`, `str`, …), which decides what you can do with it                                                     |
| **variable**                        | a name that refers to a value                                                                                                    |
| **version control**                 | recording the history of changes to files (Git)                                                                                  |

Learn Python with QHO444 · personal study notes for QHO444 (2026/27). Written in my own words from the module materials; all code was executed with Python before inclusion.
