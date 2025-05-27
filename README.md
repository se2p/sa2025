# Software Analysis SS2025

This repository collects examples from the Software Analysis lecture in
Jupyter notebooks. 

## Installation

PDF Exports of the notebooks will be uploaded to StudIP, and markdown
exports are included in the repository. To run the notebooks on your own you
will need to install [Jupyter](https://jupyter.org/install).

## Contents

### 1: Initial character-based analysis

This chapter describes two very basic analyses of source code at character
level, by splitting source code files into lines: The first analysis is to
count lines of code, and the second on is a basic code clone detection
technique, capable of detecting type 1 clones.

[Markdown Export](rendered/1%20Analysis%20Basics.md)


### 2: On the Naturalness of Code: Token-level analysis

This chapter looks at the process of converting source code into token streams,
and applying different types of analyses on these, such as code clone detection
or code completion based on language models.

[Markdown Export](rendered/2%20Naturalness%20of%20Code.md)



### 3: Syntax-based analysis

This chapter considers syntactic information on top of the lexical
information provided by the tokens. That is, it considers what language
constructs the tokens are used in, by looking at the abstract syntax tree.
We further look at how we can automatically generate parsers using Antlr,
and then use these to translate programs and to create abstract syntax
trees. We also use the Abstract Syntax Trees to do some basic linting.

[Markdown Export](rendered/3%20Syntax-based%20Analysis.md)


### 4: Control-flow analysis

This chapter looks at how to extract information about the flow of control
between the statements in a program, and how to represent this in the
control flow graph. The control flow graph is the foundation for further
control flow analyses, and in particular we consider dominance and
post-dominance relations, which in turn are the foundation for control
dependence analysis.

[Markdown Export](rendered/4%20Controlflow_Analysis.md)
