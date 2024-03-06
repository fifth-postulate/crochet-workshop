# Lingo
Crochet has its own vocabulary and it might takes some getting used to.

Crochet project are described in a _pattern_. A pattern usually consist of a
_bill of material_, crocheting instructions and assembly instructions.

## Bill of Material
To start a crochet project you often need a number of material and tools. Below
we list a few common ones

* Yarn
* Crochet hook
* Scissors
* Needle

## Instructions
When working on a project, you need to execute instructions. In a sense you are
a crochet machine that executes a crochet program.

To be able to communicate succinctly which instruction to execute in what order a
pattern language is used. It resembles machine code. 
For example, if you should perform a _single crochet_ six times in a row, that
would be described as

```plain
sc 6
```

### Rows
Crochet patterns often are structered around rows. Patterns reflect this.
A pattern is often a number of rows of instructions.

Each row has:

* A number, detailing which row you are currently working on.
* A sequence of instructions
* A number, indicating the number of stitches in the row once finished.

The number of stitches in the pattern serves as a sort of check digit to
signal if you made a mistake somewhere along the row.

For a for a formal grammar see the appendices.

## Assembly
Often a pattern consists of discrete parts. Two legs, two wings, the main body
and the head could have been crocheted individually and need to be sewn together
to form a chicken, for example.

With broad strokes this is what a crochet pattern is. A description how to create a
certain project.
