# KS21 — Key Scientific & Technological Issues in Business
### ESCP Business School | Python Programming Course

> Complete study materials for the KS21 course — includes session-by-session notes, all corrected exercise solutions, and an interactive mock exam.

---

## 📂 Repository Contents

| File | Description |
|------|-------------|
| `KS21_Course_Resume.docx` | Full Word document — all sessions, code patterns, exam answer key & cheat sheet |
| `KS21_Mock_Exam.html` | Interactive mock exam — 17 questions, instant feedback, score tracker |

---

## 📚 Sessions Covered

### Session 1 — Algorithms
- Variables, sequences, conditionals (`if`/`elif`/`else`)
- While loops, counting, Fibonacci sequence
- `int(input())` for user input

### Session 2 — String Processing
- `len()`, indexing `[i]`, slicing `[a:b]`
- Iterating through characters
- Counting words, finding patterns

### Session 3 — Subprograms & Lists
- `def`, parameters, `return`
- List creation, `append()`, `for` vs `while`
- Searching, counting, nested lists
- `import random`

### Session 4 — Object-Oriented Programming
- `class`, `__init__` constructor
- Public vs private attributes (`__` prefix)
- Methods, getter methods
- Lists of objects

### Session 5 — Pandas
- **DataFrame** = 2D labeled structure (rows + columns) ← *10 pts on exam*
- **Series** = 1D labeled array (single column)
- `pd.DataFrame()`, `pd.read_csv()`, `df.head()`, `df.describe()`

---

## 🎯 Key Exam Points

```python
# 1. Code tracing — always go line by line
x = 4; y = x + 3; x = y * 2; result = x + y - 2  # → result = 19

# 2. IndexError — classic trap!
myList = ["a", "b", "c", "d"]   # 4 elements → indices 0, 1, 2, 3
myList[4]                        # IndexError: list index out of range

# 3. OOP — private attributes need getter methods
class Product:
    def __init__(self, name):
        self.__name = name       # private!
    def getName(self):           # getter
        return self.__name

item = Product("Laptop")
item.getName()                   # ✓ correct way to access

# 4. DataFrame vs Series (10 pts!)
import pandas as pd
df = pd.DataFrame({'A': [1,2,3], 'B': [4,5,6]})  # 2D → DataFrame
s  = df['A']                                        # 1D → Series
```

---

## 🚀 How to Use the Mock Exam

1. Download `KS21_Mock_Exam.html`
2. Open it in any browser (no internet needed)
3. Answer questions, click **Check Answer** for instant feedback
4. Use the session filter tabs to focus on specific topics
5. Click **Show All** to reveal all answers at once

---

*ESCP Business School | Yanis Taimi | April 2026*
