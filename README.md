# Python Recursion Example

A small Python example that demonstrates recursion by counting down through recursive calls and printing each value as the calls return.

## Why this project is useful

The `tri_recursion` function in [`recursion.py`](recursion.py) shows the two essential parts of a recursive function:

- A base case that stops the recursion when `k` is no longer positive.
- A recursive call with a smaller value, followed by work as each call returns.

It is a minimal example for learning how recursive calls build up and unwind. It uses only the Python standard library.

## Get started

You need Python 3. From the project directory, run:

```bash
python3 recursion.py
```

The script runs `tri_recursion(6)`. Its output is:

```text
Recursion Example Results
1
2
3
4
5
6
```

The function reaches its base case at zero, then prints the positive values in ascending order as the recursive calls unwind.

## Get help

For questions or problems, [open an issue](https://github.com/VoidLance/course-files-python-recursion/issues).

## Maintainers and contributions

No maintainer contact details or separate contribution guide are provided in this repository. Contributions are welcome through issues and pull requests; please keep changes focused on the recursion example and verify them by running the script with Python 3.
