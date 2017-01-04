# Toy Data

This repo provides a small amount of textual data, for use in testing code and
sanity checks.  To embed this repo as a subdirectory in your repo, type the
following in the main directory of your repo:

       git submodule add https://github.com/jonsafari/toy-data

Depending on your needs, you may need to tokenize and lowercase the data. You can
do this using a tokenizer, like [Tok-tok](https://github.com/jonsafari/tok-tok),
which does multilingual tokenization, lowercasing, digit conflation, and can
accomodate empty lines and comments.

The data comes from the [WMT](http://www.statmt.org/wmt16/translation-task.html)
News Commentary dataset, and is cleaned up.  Download the full data there for
large-scale experiments.
