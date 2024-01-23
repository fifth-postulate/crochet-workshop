# Pattern
Here we provide a formal grammar for the patterns in this workbook.

```plain
Pattern := Row+

Row := Index Instructions StitchCount

Index := Number ")"

Instructions := Instruction ("," Instruction)*

Instruction := (Command | "(" Instructions ")") Repition?

Command := "mr"
         | "sc"
         | "dc"
         | ...

Repitition := Number

StitchCount := "(" Number ")"

Number := [1-9] [0-9]*
```

`Command` represents all the different actions during crocheting.

One should not be to hung up on expecting the grammar to be followed to
the leter. Often some adhoc notation is introduced to clarify a point.

Furthermore, some constraints are put on patterns. For example. It is
good practice to have to row indices sorted properly.
