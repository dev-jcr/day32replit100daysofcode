# Common Errors

*First, delete any other code in your `main.py` file. Copy each code snippet below into `main.py` by clicking the copy icon in the top right of each code box. Then, hit `run` and see what errors occur. Fix the errors and press `run` again until you are error free. Click on the `👀 Answer` to compare your code to the correct code.*

## Start counting from 0

👉 I used an f-string to print out the first color in my list. Why is it printing the second color in my list, orange, instead of red?

```python
colors = ["Red", "Orange", "Yellow", "Green", "Blue", "Violet"]
print(f"The first color is {colors[1]}")
```
<details> <summary> 👀 Answer </summary>

```python
colors = ["Red", "Orange", "Yellow", "Green", "Blue", "Violet"]
print(f"The first color is {colors[0]}")
```
- Remember, start counting from 0. The first color in the list, red, is index 0.

</details>

👉 I want to access the last color in my list, violet. Why is my code crashing?

```python
colors = ["Red", "Orange", "Yellow", "Green", "Blue", "Violet"]
print(f"The first color is {colors[6]}")
```

<details> <summary> 👀 Answer </summary>

```python
colors = ["Red", "Orange", "Yellow", "Green", "Blue", "Violet"]
print(f"The last color is {colors[5]}")
```
- There is no index 6 because you need to start counting from 0. The 6th item in the list, violet, is index 5.

</details>