#RPI Homework LaTeX template

This is my custom LaTeX template for the following courses in RPI:

- CSCI 2200 Foundations of Computer Science
- ECSE 2010 Electric Circuits

##Installation

Please refer to the document of your own distribution of LaTeX.

I personally use [MiKTeX](http://docs.miktex.org/manual/localadditions.html), so I have set an environment variable `TEXINPUT` to my local repo.

##Usage

```LaTeX
\usepackage{rpihomework}
```
This is the basic package, containing a modified article layout and some essential packages.

A shorthand `\Ans` for an answer leader is also defined.

```LaTeX
\usepackage{rpifocshw}
```
This package is for logic related content.

##Contribution

Please don't hold back on suggestions, issues and pull requests.

##Memorable

This is my first independent original github repo.
