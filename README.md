# Problem Solving with Python — Chapter 10: Build an Index

This repository contains the chapter and active-learning exercise code associated with this chapter in the book *Problem Solving with Python: Using Computational Thinking in Everyday Life* by Michael D. Smith (2026), which is available from [MIT Press](https://mitpress.mit.edu/9780262383677/problem-solving-with-python/) and [Amazon](https://www.amazon.com/Problem-Solving-Python-Computational-Thinking/dp/0262552841/).

## Getting started

You will need:

- an integrated development environment (IDE)
- Python 3.10 or newer
- `pip` (usually included with Python)

If you need help getting started with an IDE, please read [my short introduction to "Understanding and Selecting an IDE"](https://ctps.io/select_ide.html).

## Cloning this repository

If you're using GitHub Codespaces, click the green "Code" button on this repo's page, select the tab "Codespaces," and click the "Create codespace on main."

Otherwise, in your IDE's terminal window, type the following commands:

```bash
git clone https://github.com/pswp-book/chap10.git
cd chap10
```

## (Optional) Create and activate a virtual environment

```bash
python -m venv .venv
# Windows
.\.venv\Scripts\activate
# macOS/Linux
source .venv/bin/activate
```

## Install dependencies

```bash
pip install -r requirements.txt
```

If there is no file `requirements.txt`, the code in this repository uses only the Python standard library.

## Reporting issues

If you find a problem in this chapter’s code (typo, bug, or mismatch with the book):

1.  Check the issues for this repo to see if it’s already reported.

2.  Open a new issue and include:
    *   The chapter number and section title (e.g., “Chapter 5, The game loop”)
    *   The filename, line number(s), and a short description of the problem.
    *   If something's wrong with the code's execution, please describe how you ran the program and the exeuction result.

## Short description of the repo's files

`rk_strmatch.py`: A Python implementation of Rabin-Karp string matching.

`simple_hash.py`: A simplified version of the hashing used in Rabin-Karp.  This
script contains both the `simple_hash` and `update_hash` functions.

`index*.py`: Scripts we use in building a book index using the Python dictionary
data type.

`JustDavid-chaps.txt`: An input for our `index32.py` script that contains only
the chapters (no preface material). The full `JustDavid.txt` file is in `chap09`.

`ale01.py`: Starter code in ALE \#1.

`ale02.py`: Starter code in ALE \#2.

`hashfun.py`: Used as a pre-class exercise to get you to think about hash
functions and how difficult it is to find a collision in one that's
well-designed.
