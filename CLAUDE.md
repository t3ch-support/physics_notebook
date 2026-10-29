# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

This is a personal LaTeX notebook of worked solutions to physics exercises (currently from Feynman's "Exercises for the Feynman Lectures on Physics"). `main.tex` is the single compiled document; `text.tex` is a scratch/test file not included in `main.tex`.

Content is organized as `\section{Chapter N: Title}` followed by `\subsection{<exercise question text>}` with the worked answer below as an `itemize` list. New exercises should follow this same pattern so the document stays consistent.

## Build

Compile with MiKTeX (installed locally):

```
pdflatex main.tex
```

or, to fully resolve references/citations in one pass:

```
latexmk -pdf main.tex
```

There is no other build tooling, linter, or test suite in this repo.
