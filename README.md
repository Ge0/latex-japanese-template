# Japanese LaTeX template

This repo is an exploration on how to produce high quality japanese document
through LaTeX.

In this example, we use the `yumin` font because, well, it is very fancy.

## Setup

### Linux

Install the `yumin` ttf font if not done yet:

```bash
$ sudo cp yumin.ttf /usr/share/fonts/TTF  # May vary depending on your distrib.
$ sudo fc-cache -fv
```

Then compile `test.tex`:

```bash
$ xelatex test.tex
```

Enjoy.
