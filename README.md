# ipython_magic_tikz

IPython magic for rendering *Tikz* generated images

Based on: https://github.com/robjstan/tikzmagic

IPython magic for executing *LaTeX* `tikz` code and rendering result in Jupyter notebook code output cell.

To install:

`pip install git+https://github.com/innovationOUtside/ipython_magic_tikz.git`

To upgrade a current installation to the latest repo version without updating dependencies:

`pip install --upgrade --no-deps git+https://github.com/innovationOUtside/ipython_magic_tikz.git`

To load the magic in a Jupyter notebook:

`%load_ext tikz_magic`

Then call as block magic: `%%tikz`

To import one or packages, use the `-p` switch and comma separate package names. For example:

`%%tikz -p circuitikz,calc`

By default, the magic wraps `tikz` code in `\begin{tikzpicture} ... \end{tikzpicture}` tags. Suppress these using the `%%tikz --no-wrap` switch.
