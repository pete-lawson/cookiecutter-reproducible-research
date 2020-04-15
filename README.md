# cookiecutter-reproducible-research

This repository provides a [cookiecutter](http://cookiecutter.readthedocs.io) template targeted towards reproducible research at the experiment rather than project level. 

## Getting Started

You need `cookiecutter` and `snakemake` installed. 

To create a new experiment run 

```
cookiecutter https://github.com/pete-lawson/cookiecutter-reproducible-research
```
and then follow the onscreen prompts to configure your experiment.

To compile the report.md project to a PDF run the following command inside your experiment directory.

```
snakemake -j 1
```
## License and Attribution
This template was inspired by, and integrates parts of, [drivendata/cookiecutter-data-science](http://drivendata.github.io/cookiecutter-data-science/), [mkrapp/cookiecutter-reproducible-science](https://github.com/mkrapp/cookiecutter-reproducible-science), and [timtroendle/cookiecutter-reproducible-research](https://github.com/timtroendle/cookiecutter-reproducible-research).
