---
jupytext:
  formats: md:myst,ipynb
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.13
    jupytext_version: 1.16.7
kernelspec:
  display_name: Python 3 (ipykernel)
  language: python
  name: python3
---

```{code-cell} ipython3
---
slideshow:
  slide_type: '-'
---
import os
from pathlib import Path
import numpy as np
import matplotlib.pyplot as plt
%matplotlib inline
```

+++ {"slideshow": {"slide_type": "slide"}}

<center>

# Scientific Open Source Software - Bridging the Gap between Researcher and Developer

## Caltech Software Accelerator | March 21st 2025

### Ross Barnowski, [@rossbar](https://github.com/rossbar) on GitHub

</center>

+++ {"slideshow": {"slide_type": "slide"}}

# My perspective

+++ {"slideshow": {"slide_type": "subslide"}}

## Software **for** engineering

+++ {"slideshow": {"slide_type": "fragment"}}

(and science and research)

+++ {"slideshow": {"slide_type": "fragment"}}

## Software as...

+++ {"slideshow": {"slide_type": "fragment"}}

 - A tool for exploration, intuition-building, formulating hypotheses, understanding constraints

+++ {"slideshow": {"slide_type": "fragment"}}

 - A means of organizing and effectively communicating ideas

+++ {"slideshow": {"slide_type": "fragment"}}

 - Stable building blocks for new ideas

+++ {"slideshow": {"slide_type": "slide"}}

## The infinite bootstrapping of emperical knowledge

TODO: applications-technology loop

+++ {"slideshow": {"slide_type": "slide"}}

### Exploratory data analysis is a major component of modern research

+++ {"slideshow": {"slide_type": "fragment"}}

#### Priorities

+++ {"slideshow": {"slide_type": "fragment"}}

- speed to test ideas
  * Researcher time uber alles

+++ {"slideshow": {"slide_type": "fragment"}}

- **Flexibility**
  * Requirements change *frequently*, *rapidly*, and *non-linearly*

+++ {"slideshow": {"slide_type": "subslide"}}

## Case study: [deepcell-label](https://label.deepcell.org)

Browser-based labeling application for cellular data.

+++ {"slideshow": {"slide_type": "slide"}}

### Exploratory data analysis is a major component of modern research

#### Priorities

- speed to test ideas
  * Researcher time uber alles

- **Flexibility**
  * Requirements change *frequently*, *rapidly*, and *non-linearly*

+++ {"slideshow": {"slide_type": "fragment"}}

- Ability to keep things *organized* and *portable*

+++ {"slideshow": {"slide_type": "fragment"}}

- The real reason researchers should care about `git`!

