---
# modify this according to your needs
title: Your paper's long title
short_title: Your paper
bibliography:
  - citations.bib
---

+++ { "part": "abstract" }
Your abstract goes here.
+++

```{warning}
**IMPORTANT:** Project Elara has switched over to the open-source forge [Codeberg](https://codeberg.org/). The Project Elara repositories have been moved to [this Codeberg page](https://codeberg.org/elaraproject/). **This paper template is no longer maintained on this GitHub-based site**.
```

:::{note}
This is a note that you can use to convey important information.
:::

# Overview

You can use regular markdown, `code`, **bold** and _italics_ as usual. You can also typeset equations:

$$
F(\omega) = \dfrac{1}{2\pi} \int f(t) e^{-i\omega t} dt
$$

You can even use footnotes[^1] and BibTeX citations like [@ieareport] from your `citations.bib`. Figures can be made as follows, and linked to by their label, such as [](#fig1):

:::{figure} fig/bessel-function.svg
:label: fig1
:alt: An illustration of the proposed system, showing solar collectors placed in geosynchronous orbit facing the Sun
:align: center

In this case, our figure is a plot of the Bessel function of the first kind, $J_0(x)$.
:::

You can also link to other files and even other headings in other files, like [](#appendix). More information about cross-references is available in [MyST's official documentation](https://mystmd.org/guide/cross-references).

Lastly, building a PDF is simple (although you need to have LaTeX installated). Assuming you do, just run:

```
myst build --pdf
```

And your paper PDF (assuming it builds successfully) will appear in the `public/` folder. Happy writing!

[^1]: This is your footnote.
