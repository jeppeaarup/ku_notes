# LaTeX note template

This is the LaTeX template I use as a base for course notes. It includes:

- A custom and flexible title page
- Colorboxes for theorems, definitions, and examples
- Custom fancy header and footer
- Some other small settings that I like.


## Colorboxes

Several colorboxes are defined using the `tcolorbox` package theorem environment. They can be used as follows:

```
\begin{box-type}{Title}{label}

Content

\end{box-type}
```
Where `box-type` is one of `definition`, `theorem`, `method`, `example`, `highlight`, or `proof`.

These environments can be cross-referenced using the `cleveref` package. The colorboxes add prefixes to the labels automatically (these can be customized in the preamble).

Futhermore, the template also includes a box for highlighting important content based on the `tcolorbox` colorbox environment. It can be used as follows:

```
\begin{important}
Content
\end{important}
```
This environment does not have a title or label and cannot be cross-referenced.