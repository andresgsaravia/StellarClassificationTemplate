# Stellar classification for [TASOC][] wg0
## {{cookiecutter.project_name}}

Author: {{cookiecutter.author_name}}
e-mail: {{cookiecutter.author_email}}


## Folder structure

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

[TASOC]: https://tasoc.dk/
[make]: https://www.gnu.org/software/make/
