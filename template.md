---
title: Put the title of your paper here
date: 2023-11-28

authors:
  - name: Author One
    email: authoremail@ncssm.edu
    affiliations:
      - North Carolina School of Science and Mathematics, Morganton, North Carolina
    roles: 
      - Conceptualization
      - Data Curation
      - Formal Analysis
      - Funding Acquisition
      - Writing – Original Draft
      - Writing – review & editing
  - name: Author Two
    email: authoremail@ncssm.edu
    corresponding: true
    affiliations:
      - North Carolina School of Science and Mathematics, Durham, North Carolina
    roles:
      - Software
      - Supervision
      - Validation
      - Visualization
      - Writing – Original Draft
      - Writing – review & editing

abbreviations:
  NCSSM: North Carolina School of Science and Mathematics

exports:
  - format: pdf
    template: arxiv_two_column
    output: exports/template-arxiv_version.pdf
---

+++ {"part": "abstract"}
Put your abstract here
+++ 

## Introduction
Put some introduction text here about your paper at NCSSM.


### Background
Some text can go here

### Research Goal

Some text can go here

## Methods

### Methods subsection 1
Some text can go here

### Methods subsection 2
Some text can go here

Here's an equation
:::{note} Slope Intercept Form of a Line
```{math}
:label: slope-intercept
y = mx + b
```
This is slope intercept form of a line where $m$ represents the slope of the line and $b$ represents the y-intercept
:::


### Methods subsection 3
Some text can go here

Here's a table

```{list-table} Sample Table
:header-rows:1
:name: sample-table
* - x
  - y
* - 1
  - 4
* - 5
  - 5
* - 9
  - 6
```

## Results
Some text can go here

Here's how you insert an image
```{figure} ./images/filename.png
:name: sample-image
:alt: alt text for screen readers
:align: center

Figure caption goes here
```

## Discussion

Here's how you make a citation using a DOI {cite:p}`https://doi.org/10.1124/pr.117.014944`. 

## Conclusion

### Competing Interests
The authors have no competing interests to declare.

+++ {"part": "acknowledgements"}

We would like to the North Carolina School of Science and Mathematics.

+++
