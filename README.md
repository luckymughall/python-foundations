# Python Foundations

Small Python exercises documenting my programming practice.

## Programs

- `practice.py`: asks for a name, removes surrounding spaces,
  applies title-style capitalisation and prints a greeting.
- `city.py`: performs the same operations for a target city.

## Requirements

Python 3. No additional packages are required.

## How to run

Download the repository and open a terminal in its folder.

Run the name exercise:

```bash
python practice.py
```

Run the city exercise:

```bash
python city.py
```

## Example

For `city.py`, entering `  mAncHEsTeR  ` produces:

```text
Target city: Manchester
```

## Concepts practised

- User input and variables
- String methods: `strip()` and `title()`
- Method chaining
- Formatted strings using f-strings

## Limitations

- Blank input is currently accepted.
- `strip()` preserves spaces inside the text.
- `title()` can change proper names and acronyms incorrectly.
- Automated tests have not been added yet.

## Learning context

These exercises were developed through guided practice with AI coaching.
