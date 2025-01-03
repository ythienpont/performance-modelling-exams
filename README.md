# Introduction to Performance Modelling

This repository holds a collection of solutions to past exams. Our goal is to make it easy for everyone to access clear, well-organized solutions. Any contribution is welcome—whether it’s adding missing solutions, fixing typos, adding illustrations, improving formatting, or any other helpful tweaks.
If I made a mistake *anywhere*, please open an issue!

## Pre-Compiled PDF
For convenience, the PDF is available [here](https://ythienpont.github.io/performance-modelling-exams/main.pdf).

## Compiling the PDF
If you’d like to compile the PDF yourself, you can find setup instructions at [LaTeX Project](https://www.latex-project.org/get/).
On Linux it's as easy as
```
pdflatex main.tex
```
Updating the table of contents requires at least two compilations to update the .aux files.

## Submitting Your Contribution

- **Create a Pull Request**: Make your changes, and if possible, select a reviewer for feedback. (Fork repository or separate branch as collaborator) PR should be called *year*-*nr.*
  - Create an issue for the problem you are working on from the list of problems, this is a good indication to see if an exercise is currently being worked on. (Each exam has a large issue, pressing the circle while hovering over a list item creates a new issue for that problem). Note that there are helpful labels available to you, use them where possible.
  - If you are not familiar with GitHub you can always send me a message and I'll try to guide you through the process.
- **Send Your Solution**: If you’re not comfortable with LaTeX or can’t add the solution directly, you can email me a scan or picture of your solution. I’ll try to add it as soon as possible.

## Style Guide

To keep things straightforward and accessible, here’s a flexible style guide. Follow these guidelines where possible:

- **No Compile Errors**: Your code should compile without errors, and ideally without warnings. Try to fix issues like “underfull hbox” before submitting a pull request.
- **Proper English**: Clear and correct English is preferred, so please check spelling and grammar before submitting.
- **Line Breaks**: Please do not overuse linebreaks '\\\\'. You should (almost) never use these in regular text.
- **Avoid Sectioning Commands**: Please don’t use `\section`, `\subsection`, or `\subsubsection` environments, as they interfere with the table of contents. If you need a custom environment, add it to the preamble.
- **Lists and Sub-Questions**: Use `itemize` and `enumerate` environments wherever possible. For questions with sub-parts, you can use `\item[(a)]` to match Benny's formatting.
- **Math Mode**: Always use math mode for variables like `n`, `i`, etc., to keep formatting consistent.
- **Punctuation for equations**: Add punctuation (like a period or comma) at the end of displayed equations when appropriate. This helps maintain the document’s flow.
- **Use \text{} in math mode**: Wrap non-mathematical text in math mode using `\text{}` to ensure consistent formatting.
- **Aligning**: Use `align` for multi-line equations instead of `eqnarray`, as it provides better spacing and alignment.

If you have improvements for the style guide or see better ways to handle formatting and environments, feel free to suggest them!

## Copyright

For any issues regarding copyright or sharing, please reach out to me before taking any action.
