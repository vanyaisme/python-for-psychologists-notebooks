# Complete Python Guide for Psychology Students in Jupyter Notebooks

A Python course built for psychology students and researchers with no prior programming experience from `print()` to data analysis with pandas and matplotlib.

This repo is the companion to the running web page at **[peer-support.live](https://peer-support.live)**.

---

## Learning Roadmap

The course is split into three tiers across nine stages and 29 sections.

**Beginner** — Sections 01–13
| Stage | Topics |
|-------|--------|
| 1 · Foundations | `print`, Variables, `input`, Operators, Strings |
| 2 · Control Flow | Conditionals, For Loops, Turtle, While Loops, Nested Loops |
| 3 · Errors & Debugging | Exception Handling Basics, Common Errors, Debugging |

**Intermediate** — Sections 14–21
| Stage | Topics |
|-------|--------|
| 4 · Data Structures | Lists, Tuples & Sets, Dictionaries, Comprehensions |
| 5 · Functions & OOP | Functions, `map` / `filter` / `zip`, Classes & OOP |
| 6 · Robust Code | Exception Handling (full toolkit) |

**Advanced** — Sections 22–29
| Stage | Topics |
|-------|--------|
| 7 · Files & Data Formats | File I/O, CSV Module, JSON Files |
| 8 · Python Toolkit | Regular Expressions, Imports & Packages |
| 9 · Data Science | Matplotlib & SciPy, Pandas |

---

## What's in This Repo

All notebooks are in the `notebooks/` folder, alongside the data files they use.

| Notebook             | Contents                                                     |
| -------------------- | ------------------------------------------------------------ |
| `beginner.ipynb`     | Stages 1–3 — foundations, control flow, basic error handling |
| `intermediate.ipynb` | Stages 4–6 — data structures, functions, OOP, robust code    |
| `advanced.ipynb`     | Stages 7–9 — file formats, regex, modules, data analysis     |
| `exercises.ipynb`    | Practice tasks for every topic                               |
| `assignments.ipynb`  | UM assignments with requirements (PIP 1–4)                   |
| `challenges.ipynb`   | Optional harder problems — attempt any time you feel ready   |

---

## Getting Started

### 0. Install Python

If you don't have Python installed yet, download the latest version from **[python.org/downloads](https://www.python.org/downloads/)** and run the installer.

> **macOS / Linux:** Python often comes pre-installed, but it may be outdated. Check with `python3 --version` in the terminal — you need **3.10 or newer**. If not, download from python.org or run `brew install python` (macOS).

> **Windows:** During installation, make sure to check **"Add Python to PATH"** before clicking Install.

### 1. Download the repo

Click **Code → Download ZIP** on GitHub and unzip it, or clone it:

```bash
git clone https://github.com/vanyaisme/python-for-psychologists-notebooks.git
cd python-for-psychologists-notebooks
```

### 2. Create a virtual environment

```bash
python3 -m venv .venv
source .venv/bin/activate      # macOS / Linux
.venv\Scripts\activate         # Windows
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

This installs JupyterLab and all required packages — no separate Jupyter installation needed.

### 4. Install Python's Tk support

**macOS:**

If you don't have Homebrew installed yet:

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Then install Tk support:

```bash
brew install python-tk
```

**Linux (apt):**

```bash
sudo apt-get install python3-tk
```

**Windows:** already included in the standard Python installer — no extra step needed.

### 5. Launch JupyterLab

```bash
jupyter lab
```

Open the `notebooks/` folder in the left sidebar and start with `beginner.ipynb`.

---

> **Python 3.10 or newer** is recommended.
