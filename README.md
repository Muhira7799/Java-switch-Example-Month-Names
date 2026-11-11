# Java `switch` Example – Month Names

A small Java program that uses a `switch` statement to print the name of a month from its number.

## What It Demonstrates

- A `switch` with twelve `case` labels, one for each month
- A one-line `case` with `break`
- A `default` case that handles invalid numbers

```java
int month = 12;
switch (month) {
    case 1:  System.out.println("January"); break;
    case 2:  System.out.println("February"); break;
    // ... cases 3 to 11 ...
    case 12: System.out.println("December"); break;
    default: System.out.println("Invalid month number! Please enter a number between 1 and 12.");
}
```

## How It Works

1. `month` is set to `12`.
2. `switch` compares it with each `case` value.
3. `case 12` matches and prints `December`.
4. `break` stops the switch.

## Output

```
December
```

| `month` | Output |
|---------|--------|
| 1 | January |
| 6 | June |
| 12 | December |
| 0 or 13 | Invalid month number! Please enter a number between 1 and 12. |

## Requirements

- Java Development Kit (JDK) 8 or higher

## Getting Started

```bash
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>
javac SwitchCase.java
java SwitchCase
```

## Project Structure

```
.
├── SwitchCase.java
└── README.md
```

## Next Steps

- Read the month number from the user with `Scanner`
- Group months into seasons or quarters by stacking `case` labels
- Try the arrow syntax (`case 1 -> ...`) in Java 14 and above
