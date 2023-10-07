# Python Exploration
This repo aims to explore and document all essential Python concepts and can be used as a summary to the course [Python Essentials](https://www.linkedin.com/learning/python-essential-training-18764650) from LinkedIn Learning.

## 1. Gearing up for Python
When we write computer programs we're working directly with the computer's memory. We're putting data into it. We're fetching data out. We're manipulating this data. Having a mental model of what's going on behind the scenes is extremely important.

To run python programs, you need to install:

- Python3 (only Python 2 is pre-installed on MacOS)
- Pip. Package installer for Python
- Jupyter Notebooks. To view the exercise files from the course.

### 1.1. Little easter egg

Input in terminal:
```
$ python3
$ import this
```

Output:
```
The Zen of Python, by Tim Peters

Beautiful is better than ugly.
Explicit is better than implicit.
Simple is better than complex.
Complex is better than complicated.
Flat is better than nested.
Sparse is better than dense.
Readability counts.
Special cases aren't special enough to break the rules.
Although practicality beats purity.
Errors should never pass silently.
Unless explicitly silenced.
In the face of ambiguity, refuse the temptation to guess.
There should be one-- and preferably only one --obvious way to do it.
Although that way may not be obvious at first unless you're Dutch.
Now is better than never.
Although never is often better than *right* now.
If the implementation is hard to explain, it's a bad idea.
If the implementation is easy to explain, it may be a good idea.
Namespaces are one honking great idea -- let's do more of those!
```

### 1.2 Text editor
So you can run programs from the terminal. Editing code can be done in e.g. VS code or PyCharm. My choice went to PyCharm for now (free community version). And here's a little [cheatsheet](https://resources.jetbrains.com/storage/products/pycharm/docs/PyCharm_ReferenceCard_mac.pdf) to optimize productivity.

### 1.3 Writing a program
Yay! The first working line of Python Code!

hello.py:
```
print('Hello world')
```

Terminal input:
```
$ python3 hello.py
```
Terminal output:
```
Hello world
```