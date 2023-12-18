This repository contains the two corpora of case reports from the European Court of Human Rights (ECHR) in Spanish that were built and annotated for pseudonymization as part of the work presented in the (unpublished) paper "Automatic pseudonymization of case reports from the ECHR in Spanish: evaluation of two different annotation approaches".

As it is mentioned in the paper, the two corpora differ on the annotation procedure: one corpus (file ES-projected.tsv) was annotated by automatically projecting the annotations of the English corpus built by Pilán et al. (2022), and the other corpus (file ES-manual.tsv) was manually annotated by following a reinterpretation of their guidelines.

The files ES-projected-sents-number.tsv and ES-manual-sents-number.tsv have the exact same content as the two aforementioned files, but here the sentences are numbered in order to facilitate the assessment of the mBERT model.

In addition to that, this repository contains four Jupyter Notebooks. These notebooks display the experiments that were carried out for assessing Flair and mBERT on a Named Entity Recognition (NER) task employing the newly-built corpora.

References

Pilán, I., Lison, P., Ovrelid, L., Papadopoulou, A., Sánchez, D. & Batet, M. (2022). The Text Anonymization Benchmark (TAB): A Dedicated Corpus and Evaluation Framework for Text Anonymization. In Computational Linguistics, 48(4), pp. 1053–1101. Cambridge, MA: MIT Press. doi: 10.1162/coli_a_00458.
