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

Repitition := "x" Number

StitchCount := "(" Number ")"

Number := [1-9] [0-9]*
```

`Command` represents all the different actions during crocheting.

