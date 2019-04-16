[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mbeyeler/2019-nonnegative-sparse-coding/master)


# Neural correlates of sparse coding and dimensionality reduction

This repository contains code to produce some of the figures in the following paper:

M Beyeler*, EL Rounds*, KD Carlson, N Dutt, JL Krichmar (2019). Neural correlates of sparse coding and dimensionality reduction. *PLOS Computational Biology*, doi:[10.1371/journal.pcbi.1006908](https://doi.org/10.1371/journal.pcbi.1006908).

- [Fig. 1B](https://github.com/mbeyeler/2019-nonnegative-sparse-coding/blob/master/fig1B-PCA-vs-NMF.ipynb): PCA and NMF applied to the CBCL face dataset.
- [Fig. 2](https://github.com/mbeyeler/2019-nonnegative-sparse-coding/blob/master/fig2-efficient-coding.ipynb): Schematic of the efficient coding hypothesis.
- [Fig. 4](https://github.com/mbeyeler/2019-nonnegative-sparse-coding/blob/master/fig4-NMF.ipynb): Example NMF reconstruction for a specific example of the CBCL face dataset.

Required packages are given in `requirements.txt`. For Figs. 1 and 4, you will also need to download the CBCL dataset from [here](http://www.ai.mit.edu/courses/6.899/lectures/faces.tar.gz). See [NIMFA instructions](https://github.com/marinkaz/nimfa/tree/master/nimfa/datasets/CBCL_faces) on where to put it.
