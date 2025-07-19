# 💬 Comments and Code Structure in Python

Before diving into complex code, let’s learn how to **talk to your future self** (and others) using **comments** and keep your code **clean and readable**. 🧹💡

---

## 📝 What Are Comments?

Comments are **lines ignored by Python**, used to:

- Explain what your code does
- Make your code easier to understand
- Temporarily disable lines of code (during debugging)

---

## 🐍 Single-Line Comments

Use the `#` symbol:

```python
# This is a comment
print("Hello!")  # This prints Hello!
```

✅ Python ignores anything after `#` on that line.

---

## 📚 Multi-Line Comments (Trick)

Python doesn’t have a dedicated multi-line comment feature, but you can **simulate it**:

```python
"""
This is a multi-line comment.
It is often used as a docstring.
"""
print("Python is cool!")
```

> ⚠️ Technically, this is a **docstring**, not a real multi-line comment — but it works for adding block notes.

---

## 🧹 Code Structure Tips

Clean code = Easy code!

### 1. 🧱 Indentation

Python **uses indentation** (spaces/tabs) to define code blocks:

```python
if 5 > 3:
    print("Yes")  # Indented = inside the if-block
print("Outside")  # Not indented = outside
```

✅ Default: **4 spaces** (no tabs!)

---

### 2. ✂️ Use Blank Lines

Helps separate logic:

```python
# Step 1: Input
name = input("Enter your name: ")

# Step 2: Output
print("Hi", name)
```

---

### 3. 🔤 Use Meaningful Names

```python
# ❌ Not helpful
x = "Naman"

# ✅ Much better
user_name = "Naman"
```

---

### 4. 🔁 Avoid Repetition

If you're repeating code, think about using a function (you’ll learn this soon!):

```python
# Instead of repeating this:
print("Hello, Naman!")
print("Hello, Alex!")

# You could:
def greet(name):
    print("Hello,", name)

greet("Naman")
greet("Alex")
```

---

## 🧪 Practice Challenge

Can you add comments to this code?

```python
name = input("What's your name?")

print("Welcome", name)

# Add your own comment here
```

# 🚀 Pro Tips for Faster Coding

Take your coding game to the next level with these **must-know shortcuts** (especially for **VS Code**):

| Shortcut                         | What It Does                                         |
|----------------------------------|------------------------------------------------------|
| `Ctrl + /`                       | Toggle comment on selected line(s)                  |
| `Alt + ↑ / ↓`                    | Move current line or block **up or down**           |
| `Alt + Shift + ↑ / ↓`           | **Duplicate** current line or block up/down         |
| `Ctrl + Shift + K`              | **Delete** the current line                         |
| `Ctrl + Space`                  | Trigger **IntelliSense / autocomplete**             |
| `Ctrl + P`                      | **Quick file search** in your project               |
| `Ctrl + Shift + F`              | **Find across files**                               |
| `Ctrl + Shift + [` or `]`       | Collapse/Expand code blocks                         |

> 💡 These make your workflow smoother and keep you in the zone.

---

## 📚 Next Steps

Now that you know how to leave comments and write a clean code structure, it's time to play with **variables and datatypes**.  
👉 [Continue to: Variables and Data Types →](variables-data-types.md)

---

# Happy coding! 🐍✨