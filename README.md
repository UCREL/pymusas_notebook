# PyMUSAS Notebooks

This repository contain multiple notebooks, that can be opened in Google Colab, and the data the notebooks use to demonstrate the uses of [PyMUSAS](https://github.com/UCREL/pymusas).

## Introductory notebooks

The following notebooks are introductions into PyMUSAS.

* [./PyMUSAS.ipynb](./PyMUSAS.ipynb) notebook, which uses the [./Nile.txt](./Nile.txt) and [./danube.txt](./danube.txt) text files from Wikipedia, is a basic introduction into PyMUSAS and tagging in general, the guide is English only and covers; 
    - How to install and setup PyMUSAS for English.
    - How to tag text whereby the text can come from a Python string variable or a file.
    - How to view the POS tags in combination with it's associated tokens.
    - Create histograms of the most frequent POS and tokens in your tagged text
    - Compare the frequency of tokens between two texts
    - Generating keyness values of tokens based off the two texts.
* [./ucrel_summer_school.ipynb](./ucrel_summer_school.ipynb) notebook is a longer and more detailed introduction, it also supports 9 of the PyMUSAS supported 12+ languages including English. The guide covers;
    - Load a Rule Based semantic tagger.
    - Semantically tag a single sentence.
    - Semantically tagging a large dataset using datasets from HuggingFace.
    - Comparing two semantically tagged dataset through visualisation and a keyness metric.
    - At the end it allows the user to explore the Hybrid and Neural tagger through the tutorials on the [PyMUSAS documentation website](https://ucrel.github.io/pymusas/).