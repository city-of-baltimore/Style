# Style
Package development for visual style guides for City charts, plots, tables, maps, etc. Integrates approved color palettes, fonts, sizing, etc.

## Using the template
import plotly_theme

import plotly.io as pio

pio.templates.default = "COB"

>> Note: In order for the import to succeed, the plotly_theme.py file must be on Python's module search path. See https://docs.python.org/3/tutorial/modules.html#the-module-search-path for more information.
