Java file = all of our code 

.md file = Text, definitions, etc;

## Intro to Java

A Java program can be characterized as an **object** represented in a **class**.
Currently our program has a *Main* object. Inside of this object we have the *Main* class.

## Output

In Java, to output an item to the console we use: `System.out.println()` prints the statement and moves to the next line, while
`System.out.print()` just prints the statement.

## Comments

A comment is used as user annotation with the purpose of being human readable.

**Line comments** follow double back slashes.`//` (Single Line Comment)

**Block comments** are contained within `/* Comments */` (Multiple Line Comments)

## Identifier

In Java use the term **identifier** to describe a variable, parameter, constant, user-defined method or user-defined class.
- Cannot begin with digit
- Can only contain letters, digits, or underscores
- Case-sensitive `age != Age` (age is not equal to Age)
`Apple == Apple`

*Note: *
- class names start with a capital letter
- reserved words are entirely lowercase and may not be used as identifiers (Reserved words will show up in blue.)

## Types
**Primitive** or **built-in** types in Java are
- `int` An integer
- `boolean` True or False (boolean shirtColor = false)
- `double` Floating-point number (2,73)
- `char` Single character

*Note: * Integers have a fixed amount of memory, so there is a limit to how many digits you can store(2^31 - 1)

## Variables
Variables are a type of identifier that stores a value of a specific type.

We can create variables using **declaration**
- `int age;` (format: type, identifier, semicolon)
- `double x, y;`
- `boolean found;`
- `char letter;` 

We can also initialize a variable in its **declaration** (declaring variable is like saying this variable exists, initializing is giving it a value)
- `int count = 1;`
- `double p = 3.14;`
- `char c = '8';`

## Chars
[ASCII CHART]
(https://groups.google.com/d/msgid/chaboyamathclub/CACo3uW4Gd0%3D9u%2BJ%2BXTMgB1zcNBVv539RoLL0_%3DPMqi8yD2M5Yg%40mail.gmail.com?utm_medium=email&utm_source=footer)

Each character is associated with an ASCII value.

## Type cast

One type can be cast to another compatible type if appropriate.

`char letter = 'c';`
`int value = int(letter);`

int total, n;
double average;
average = (double)total/n //total cast to double to ensure real division is used

*Note: * Casting a floating-point number to an interger simply truncates the number (rounds down).









