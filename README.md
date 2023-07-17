# code-translation

This project contains a number of assets for automatic [language translation](https://en.wikipedia.org/wiki/Translator_(computing)) using generative AI.

Currently there are two notebooks included:

* `CodeConversion.ipynb` --- Uses the OpenAI API to translate source code from/to a number of different programming languages (e.g. R, Python, SAS)

* `CodeConversionMagic.ipynb` --- Creates a *sasconvert* Jupyter magic command for translating SAS code into Python code

## Prerequisites

* this project requires the `openai` Python package (already included in `requirements.txt`)
* this project has been tested against [5.6 Domino Standard Environment Py3.9 R4.2.3
](https://quay.io/domino/compute-environment-images:ubuntu20-py3.9-r4.2-domino5.6-standard) without any additional customizations
* this project requires a valid OpenAI API key loaded in an environment variable named `OPENAI_API_KEY`. If using in Domino, this can ideally be configured as a [project environment variable](https://docs.dominodatalab.com/en/latest/user_guide/d8dde6/store-project-credentials/)


