# Project Elara Report & Paper Template

This repository houses an open-source template for creating papers and technical reports for Project Elara. Follow the development instructions to quickly set up a new project.

> :warning: **IMPORTANT:** Project Elara has switched over to the open-source forge [Codeberg](https://codeberg.org/). The Project Elara repositories have been moved to [this Codeberg page](https://codeberg.org/elaraproject/). **This GitHub repository is no longer maintained**.

A live version of this template can be seen at [this web preview](https://elaraproject.github.io/elara-paper-template).

## Development

> Everything in this report is released to the **public domain** like the rest of [Project Elara](https://github.com/elaraproject/), meaning it is essentially **unlicensed research**, so you can use it for basically any project you want, _however_ you want, with or without attribution.

This template is built with [MyST](https://mystmd.org/). To get started, first clone the repository:

```sh
git clone https://github.com/elaraproject/elara-paper-template
```

Ensure you have [Python](https://www.python.org/) and [pip](https://pypi.org/project/pip/) installed. Then install MyST with:

```sh
pip install mystmd
```

To start a live development server, run:

```
myst start
```

To build the PDF, you must have [LaTeX installed](https://www.latex-project.org/get/). With a working LaTeX installation, the PDF can then be built with:

```
myst build --pdf
```
