# Cookie cutter template for Stellar Classification in TASOC wg0

Very simple [cookie cutter][] template for [TASOC][] stellar classification. 

## Getting started

To use make sure you have [cookie cutter][] installed:

```
pip install -U cookiecutter
```

Now create a new classification project:

```
$ cookiecutter https://github.com/andresgsaravia/StellarClassificationTemplate
project_name [my_stellar_classification]: Your-project-name-here
author_name [John Doe]: Your-name-here
author_email [me@example.com]: Your-email-hre
```

You will get a folder structure like this

```
.
├── data
│   ├── final
│   ├── intermediate
│   └── raw
├── Makefile
├── notebooks
├── README.md
├── src
└── visualizations
```

There is a `Makefile` with some useful commands described in the following section.

## Makefile commands

There are some simple but helpful scripts implemented as make commands. If you have [make][] installed you can run 

```
$ make command
```

where `command` can be any of following:

- `show-help`: Summary of all available commands.
- `get-data`: Downloads and extracts the simulated data into `./data/raw`. It will warn you if you already have done so. (Due to server permissions this does not work right now).
- `test-accuracy`: (TODO) Compares your predictions with the simulated values and reports the accuracy.
- `confusion-matrix`: (TODO) Generates a confusion matrix in `visualizations` with your predictions.

[cookie cutter]: https://cookiecutter.readthedocs.io/en/latest/
[TASOC]: https://tasoc.dk/
[make]: https://www.gnu.org/software/make/
