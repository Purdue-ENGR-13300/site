---
jupytext:
  text_representation:
    extension: .md
    format_name: myst
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---
```{include} ../macros.md
```

(individual)=
# Individual Assignments

````{admonition} Assigment Goals
:class: note

```{include} ../guidelines/python.md
```
```{include} ../guidelines/individual_task_points.md
```
```{include} ../guidelines/common_steps.md
```

````

## Notes Before You Start


```{include} ../guidelines/gradescope.md
```

```{include} ../guidelines/individual.md
```

## Submissions


```{code-cell} ipython3
:tags: ["remove-cell"]

from myst_nb import glue

mnum = "05"

glue("deliverable_PY1_2_1_word_pdf", mnum+"_2_1_username.pdf")
glue("deliverable_PY1_2_1_excel_pdf", mnum+"_2_1_excel_username.pdf")
glue("deliverable_PY1_2_1_py", mnum+"_2_1_username.py")
glue("deliverable_PY1_2_2_pdf", mnum+"_2_2_username.pdf")
glue("deliverable_PY1_2_2_py", mnum+"_2_2_username.py")
```

```{table} Deliverables
:class: deliverables
:name: tab:M05:individual_deliverables

|    Task(s) |  Deliverables                               |
|:----------:|:--------------------------------------------|
|          1 | {glue:text}`deliverable_PY1_2_1_word_pdf`   |
|          1 | {glue:text}`deliverable_PY1_2_1_excel_pdf`  |
|          1 | {glue:text}`deliverable_PY1_2_1_py`         |
|          2 | {glue:text}`deliverable_PY1_2_2_pdf`        |
|          2 | {glue:text}`deliverable_PY1_2_2_py`         |
```