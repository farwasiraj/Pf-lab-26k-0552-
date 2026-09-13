# C Basics

## 1. Data Types

| Data Type | Description |
|---|---|
| int | Stores whole numbers |
| float | Stores decimal numbers |
| double | Stores decimal numbers with more precision |
| char | Stores a single character |
| bool | Stores true or false |
| void | Represents no value |

## 2. Format Specifiers

| Format Specifier | Description |
|---|---|
| %d | Signed integer |
| %u | Unsigned integer |
| %o | Octal |
| %x | Hexadecimal (lowercase) |
| %X | Hexadecimal (uppercase) |
| %f | Floating-point value |
| %e | Scientific notation |
| %E | Scientific notation |
| %c | Character |
| %s | String |
| %ld | Long integer |

## 3. Input and Output Functions

### scanf()
Used to take formatted input.

### printf()
Used to display formatted output.

### getchar()
Used to read one character.

### putchar()
Used to display one character.

### puts()
Used to display a string followed by a new line.

## 4. Escape Sequences

| Escape Sequence | Meaning | Example |
|---|---|---|
| \n | New line | "Hello\nWorld" |
| \t | Tab | "Name:\tAli" |
| \\ | Backslash | "C:\\Files" |
| \" | Double quote | "He said \"Hi\"" |
| \b | Backspace | "ABC\b" |

## 5. Precision

Precision specifies how many digits are displayed after the decimal point.
Example:
Printf("%.2f",12.3456);
Output: 12.35
