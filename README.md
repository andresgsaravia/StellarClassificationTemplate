# Cookie cutter template for peak-bagging

Very simple [cookie cutter][] template for [TASOC][] stellar classification. To use make sure you have [cookie cutter][] installed:

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

[cookie cutter]: https://cookiecutter.readthedocs.io/en/latest/
[TASOC]: https://tasoc.dk/
