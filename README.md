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
