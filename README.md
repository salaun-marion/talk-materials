# Talk-materials

This repository is hosting presentations thanks to [Quarto](https://quarto.org/) framework.

# To launch locally the quarto presentation

You can run the following command lines in the terminal at the root of the repository.

`quarto render && quarto preview`

And then it should automatically open and update automatically in your default browser on following on localhost (check in terminal).

# To modify the quarto presentation

You need only to modify one file : `index.qmd`.

The syntax is quite similar with Markdown but do not hesitate to check on Quarto documentaton website for the syntax 😉

# To publish on your github website

To have access to your slides on your : **username.github.io/talk-materials** website.
You need to use this command line to publish your slides on it : `quarto publish gh-pages`
