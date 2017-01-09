# Toy Data

This provides a small amount of textual data, for use in testing code and
sanity checks.  You can embed this as a subdirectory in your repo, by typing the
following in the main directory of your repo:

       git submodule add https://github.com/jonsafari/toy-data
	   git add .gitmodules
	   git commit .gitmodules toy-data/ -m 'add .gitmodules'

Depending on your needs, you may need to tokenize and lowercase the data. You can
do this using a tokenizer, like [Tok-tok](https://github.com/jonsafari/tok-tok),
which does multilingual tokenization, lowercasing, digit conflation, and can
accomodate empty lines and comments.

The data comes from the [WMT](http://www.statmt.org/wmt16/translation-task.html)
News Commentary dataset, and is cleaned up.  Download the full data there for
large-scale experiments.
It is triple-aligned in **English**, **Spanish**, and **German**.  Below are the
number of sentences in each set:

| Set      | Sentences | Tokens |
| ---      | ---       | ---    |
| Training | 1000      | ~23K   |
| Dev      | 200       | ~4.5K  |
| Test     | 200       | ~4.8K  |

