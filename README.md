# Markdown Compiler

*** 

## Description 
A work in progress Markdown Compiler that will transform markdown into HTML.

***

## Progress

Currently I have finished the core logic of the markdown compiler and I am working on testing as well as the actual frontend display.

I also intend to add more features and develop a simple, but good looking site.

## Core Idea

The compiler makes use of concepts that I learned from my compilers course. It works in 3 stages: a scanning stage, a parsing stage, and a code generation/conversion into html stage.
1. It first scans the input markdown and converts it into tokens (doing some basic checks in the process).
2. It then parses the tokens into a valid syntax tree for markdown (doing the remaining validity checks in the process).
3. It then converts the tokens into html.
