# LaTeX note template

This is the LaTeX template I use as a base for course notes. It includes:

- A custom and flexible title page
- Colorboxes for theorems, definitions, and examples
- Custom fancy header and footer


## Colorboxes

The colorboxes for theorems, definitions, and examples are defined in `preamble.tex`. You can customize the colors there.

```
\begin{box-type}{Title}{label}

Content

\end{box-type}
```
Where `box-type` is one of `theorem`, `definition`, or `example`.
