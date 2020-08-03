# What is the most popular programming language in 2020?

Which is the most frequently used programming language and which programming language pays best in 2020? Analysis of the Stack Overflow developer survey for 2020.

## Project Motivation

Going into this project I was interested in finding out how are programming languages ranked and can I choose my own criteria when ranking them? How do people determine JavaScript is the most popular language and why do they recommend it so much? I used Stack Overflow's developer survey to draw my own conclusions on the following questions:

- Which is the most frequently used programming language?
- Does language popularity affect salary?
- Does language popularity affect work satisfaction?
- Can we use simple linear regression to determine a developer's salary based only on the languages they use?

## File descriptions

The project is divided into 3 parts trying to answer the questions above in order

1. `most_used_programming_language_overall.ipynb` tries to determine the most frequently used language overall
2. `salary_and_satisfaction_based_on_language.ipynb` looks at the relationship between programming language and salary/work satisfaction
3. `predicting_salary.ipynb` builds a simple linear regression using the data and finds out that a programming language is not enough to determine one's salary

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
Check out the full results in this [Medium post](https://medium.com/@luchevz/whats-the-most-popular-programming-language-in-2020-6c18919f965b).

Here's a preview of the most frequently used programming languages in 2020.

![https://i.imgur.com/AnlNx5q.png](https://i.imgur.com/AnlNx5q.png)

## Acknowledgements

[Stack Overflow](https://stackoverflow.com/) for making their developer survey [results](https://insights.stackoverflow.com/survey) public.

[Josh Bernhard](https://medium.com/@josh_2774) with his amazing article [How Do YOU Become A Developer?](https://medium.com/@josh_2774/how-do-you-become-a-developer-5ef1c1c68711), which motivated me to write this project.