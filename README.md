# Emotify 😃

A simple Python program that replaces certain words in a sentence with corresponding emoticons.

---

## 💻 Code

```python
def emotify():
    return (
        input("Input a Sentence: ")
        .replace("Smile", ":)")
        .replace("Grin", ":D")
        .replace("Sad", ":(")
        .replace("Mad", ">:(")
    )

print(emotify())

# Unpacking List in Python

This example demonstrates how to **unpack values from a list** into different variables using indexing and slicing.

---

## 💻 Code

```python
# Unpacking List 

lst = [1, 2, 3, 4, 5, 6]  # store variables inside the word lst

first = lst[0]       # 1st element (index 0) is stored in the 'first' variable
middle = lst[1:5]    # slicing index 1 to 4 (index 5 is not included)
last = lst[5]        # element at index 5 is stored in the 'last' variable

print("first:", first)    # Print first 
print("middle:", middle)  # Print middle
print("last:", last)      # Print last 
