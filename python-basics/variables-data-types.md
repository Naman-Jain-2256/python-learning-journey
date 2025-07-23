# 🧠 Variables and Data Types

Welcome to the **foundation of Python programming**! 🧱  
In this lesson, you'll learn how to store, label, and manage data using **variables** and explore the many **data types** Python supports.

---

## 📦 What are Variables?

Variables are like **containers** that store data. You name them, fill them, and use them anytime in your program.

```python
name = 'John'
age = 20
is_learning_python = True
```

Here's what's happening:
- `name` stores a **string**
- `age` stores a **number**
- `is_learning_python` stores a **boolean** 

---

## 🧰 Variable Naming Rules (and Tips!)
✅ Can contain letters, digits, and underscores ( _ )  
❌ Cannot start with a digit  
❌ No spaces or special characters  
✅ Be descriptive and readable  
✅ Case-sensitive (`Name` ≠ `name`)

**Good examples**:
```python
first_name = 'Alice'
total_marks = 87
```

**Avoid**:
```python
x = 'Alice'
tm = 87
```

---

## 🧪 Common Data Types in Python

| Type    | Example            | Description                   |
| ------- | ------------------ | ----------------------------- |
| `int`   | `10`, `-3`, `0`    | Whole numbers                 |
| `float` | `3.14`, `-0.01`    | Decimal numbers               |
| `str`   | `"Hello"`          | Text/String                   |
| `bool`  | `True`, `False`    | Boolean logic                 |
| `list`  | `[1, 2, 3]`        | Ordered, mutable collection   |
| `tuple` | `(1, 2, 3)`        | Ordered, immutable collection |
| `dict`  | `{"key": "value"}` | Key-value pairs               |
| `set`   | `{1, 2, 3}`        | Unordered, unique elements    |

---

## 🧠 Type Checking and Conversion

You can check or convert data types easily:
```python
type(10)         # <class 'int'>
int("5")         # now string 5 is integer datatype
str(100)         # now integer 100 is string datatype
float("3.14")    # now string 3.14 is float datatype
```
> Note that improper conversion raises an error:
```python
int("abc")  # ❌ This will cause a ValueError
```
> We will discuss more in **Type Casting** topic 

---

## ✨ Bonus: Dynamic Typing

Python is **dynamically typed**, meaning you don’t declare data types. Python figures it out!
```python
a = 10      # int
a = "Ten"   # beware variable 'a' now contains a string "Ten" not 10
# Be cautious when using 'a' in math after reassignment
```
This makes coding faster — but be careful with type errors!

---

## 🧪 Try It Yourself!
```python
# Store your name and age
your_name = "Your Name"
your_age = 20

# Print them
print("Hi,", your_name, "you are", your_age, "years old.")

# You can alternatively use f-strings for above
print(f"Hi, {your_name}, you are {your_age} years old.")
# It is a modern way in which the variable inside curly brackets gets automatically included
```

---

## 🔧 Pro Tips

- 💡 Use `Ctrl + /` to quickly comment/uncomment lines in VS Code.
- ⬆️⬇️ Move lines with `Alt + ↑ / ↓`
- ➕ Duplicate lines with `Shift + Alt + ↓ / ↑`
- 📋 Use `F2` to rename variables across the file.

---

## 🔚 Summary

Variables are your program’s memory. They hold everything — names, numbers, choices, even lists of data! With dynamic typing, Python makes it easy — just assign and go!

---

## 📚 Next Steps

Now that know about variables and data types, it's time to rock **Type Casting**  
👉 [Continue to: Type Casting →](type-casting.md)

---

# Happy coding! 🐍✨