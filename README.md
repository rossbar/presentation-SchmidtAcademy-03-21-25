# Scientific Open Source Software - Bridging the Gap between Researcher and Developer

Companion presentation to open-source software discussion prepared for the
Caltech Software Accelerator meeting hosted by the Schmidt Academy @ Caltech,
03/21/2025

## Setup for presentation

Create a python virtual environment and enter it:

```bash
python -m venv presentation-env
source presentation-env/bin/activate
```

Then install the dependencies:

```bash
(presentation-env)$ pip install -r requirements.txt
```

## View the presentation

To view the presentation either as a notebook or rendered as slides, use `jupyter lab`

```bash
jupyter lab
```

To open as a notebook, right-click on `presentation.md` -> `Open with` and
select `Jupytext notebook`.
To view as a slideshow, select `Rise Slides`

**NOTE:**
If either of these options is missing, make sure `jupytext`, `jupyterlab-rise`,
and `jupyterlab-myst` are all installed (see `requirements.txt`).

RISE quick start:

- Toggle presentation mode with `alt+r`
- Toggle full-screen with `F11`
- Navigation:
  * Move one slide/fragment forward: `space`
  * Move one slide/fragment back: `shift+space`
- Run executable cells just like a normal notebook: `shift+enter`
