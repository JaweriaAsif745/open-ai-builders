# Python Basics for AI Beginners 🐍

This guide introduces a few Python concepts commonly used in artificial intelligence and machine learning.

## 1. Variables

Variables store information.

```python
project_name = "My First AI Project"
number_of_samples = 100

print(project_name)
print(number_of_samples)
```

## 2. Lists

Lists can store multiple values, such as model predictions or dataset labels.

```python
sentiments = ["positive", "negative", "positive"]

print(sentiments[0])
print("Number of examples:", len(sentiments))
```

## 3. Functions

Functions let us reuse code.

```python
def greet_builder(name):
    return f"Hello, {name}! Welcome to AI."

print(greet_builder("AI Builder"))
```

## 4. A Tiny Data Example

Calculate the average of a few sample values.

```python
scores = [80, 90, 85, 95]

average_score = sum(scores) / len(scores)

print("Average score:", average_score)
```

## Try It Yourself 💡

1. Change the project name and print it.
2. Add another sentiment to the list.
3. Create a function that doubles a number.
4. Change the scores and calculate the new average.

## What's Next?

After learning these basics, explore Python libraries such as NumPy, Pandas, and scikit-learn.

Contributions that improve these examples or add new beginner exercises are welcome!
