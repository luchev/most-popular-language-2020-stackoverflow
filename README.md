# What is the most popular programming language in 2020?

Based on the Stack Overflow developer survey for 2020. The survey results can be found [here](https://insights.stackoverflow.com/survey).

In this project we look at the Stack Overflow data and try to figure out:

- Which is the most frequently used programming language?
- Does language popularity affect salary?
- Does language popularity affect work satisfaction?
- Can we use simple linear regression to determine a developer's salary based only on the languages they use?

## Dependencies

The code in this project depends on the following python libraries, which can be installed with pip.

- `pandas`
- `numpy`
- `matplotlib`
- `sklearn`

To view the Jupyter notebooks on your local machine you will also need to install `jupyter`.

## Getting started

Before you run any of the code in the notebooks, download the Stack Overflow survey results from [here](https://insights.stackoverflow.com/survey) and place them in a subdirectory `data/`.

The results file should be named `2020.csv` and the schema filed should be `2020-schema.csv`, both of them saved under `data/`.

Then you can simply run  `jupyter notebook --ip=0.0.0.0 --port=4040` to view the notebooks.

If you get an error when running jupyter, try changing the port or removing the `--ip` option.

## Results
Check out the results in this [Medium post](https://medium.com/@luchevz/whats-the-most-popular-programming-language-in-2020-6c18919f965b).
