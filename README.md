Description:
------------

This directory contains data with the Sentiment Corpus of German
Twitter.  To open the files of this corpus, you need to download and
launch [the MMAX2 annotation tool](http://mmax2.sourceforge.net/) and
then select one of the *.mmax projects located in the directories
`corpus/annotator-1/` or `corpus/annotator-2/`.

This folder contains following files and directories:

* `corpus/` -- directory containing corpus files;
  * `annotator1/` -- directory containing MMAX projects for the first
    annotator;
    * `markables/` -- directory containing annotation files for the
       first annotator;
  * `annotator2/` -- directory containing MMAX projects for the second
    annotator;
    * `markables/` directory containing annotation files for the
       second annotator;
  * `basedata/` and `source/` -- original corpus tokenization;
  * `custom/`, `scheme/`, and `style/` -- auxiliary MMAX2 data;
  * `doc/guidelines.pdf` -- guidelines used for the annotation of the
    corpus;

* `scripts/` -- directory containing scripts that were used to process
  corpus data;
  * `examples/` -- directory containing examples of input files for
    the scripts;
  * `align.py` -- auxiliary module used for annotation alignment;
  * `alt_fio.py` -- auxiliary module for AWK-like input/output operations;
  * `conll.py` -- auxiliary module for handling CONLL sentences;
  * `crf_evaluate.py` -- script for evaluating the accuracy of CRF model
  * `measure_corpus_agreement.py` -- script for measuring corpus
    agreement;
  * `merge_conll_mmax.py` -- script for aligning annotation from the
    corpus with the automatically processed CONLL data;

You can see the examples of invocations in the script files or by just
typing `--help` to see their usage.