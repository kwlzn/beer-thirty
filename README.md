# Beer Thirty Tap Menu

This is a quick/dirty Jupyter Notebook for analyzing the tap menu at [Beer Thirty](https://www.beerthirtysantacruz.com/) (a popular tap room in Santa Cruz, CA).

In particular, this repo provides a notebook that:

1. Parses the [bthirty.com](http://bthirty.com) TapHunter menu data into a [pandas](https://pandas.pydata.org/) dataframe for easy manipulation/analysis.
2. Groups by category (IPAs, Sours, etc).
3. Sorts within the group by ABV and heatmaps the ABV column.
4. Cross-references [Untapp'd](https://untappd.com) for ratings + review links.
5. Renders this in a table for easy tap selection.

## How to Run?

The easiest way to run this notebook is via [Google Colab](https://colab.research.google.com):

1) Click [here](https://colab.research.google.com/github/kwlzn/beer-thirty/blob/main/beerthirty-tap-menu.ipynb) to open the notebook in Colab.
2) Go to the `Runtime` drop-down menu > `Run All`.
3) Scroll to the bottom to see the table.

Colab also lets you modify the contents of the notebook for further analysis/improvement - contributions welcome!
