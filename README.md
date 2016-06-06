# nlp4twitter_tutorial

[![Join the chat at https://gitter.im/leoferres/nlp4twitter_tutorial](https://badges.gitter.im/leoferres/nlp4twitter_tutorial.svg)](https://gitter.im/leoferres/nlp4twitter_tutorial?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

*Leo Ferres*

- email: <lferres@udd.cl>
- twitter: [@leoferres](https://twitter.com/leoferres)
- github: [leoferres](http://github.com/leoferres)

This repository contains notebooks and other files associated with my **nlp4twitter** tutorial.

## Installation Notes
This tutorial requires the following packages:

- Python version 2.6-2.7 or 3.3+
- `numpy` version 1.5 or later: http://www.numpy.org/
- `scipy` version 0.10 or later: http://www.scipy.org/
- `matplotlib` version 1.3 or later: http://matplotlib.org/
- `scikit-learn` version 0.14 or later: http://scikit-learn.org
- `ipython` version 2.0 or later, with notebook support: http://ipython.org
- `seaborn` version 0.5 or later
- `nltk` version 3.2.1 or later: https://github.com/nltk/nltk
- `spacy` version 0.100.6 or later: https://github.com/spacy-io/spaCy

The easiest way to get these is to use the [conda](https://store.continuum.io/) environment manager.
I suggest downloading and installing [miniconda](http://conda.pydata.org/miniconda.html).

Once this is installed, the following command will install all required packages in your Python environment:
```
$ conda install numpy scipy matplotlib scikit-learn ipython-notebook seaborn
```
Alternatively, you can download and install the (very large) Anaconda software distribution, found at https://store.continuum.io/.

## Downloading the Tutorial Materials
I would highly recommend using git, not only for this tutorial, but for the
general betterment of your life.  Once git is installed, you can clone the
material in this tutorial by using the git address shown above:

git clone git://github.com/leoferres/nlp4twitter_tutorial.git

If you can't or don't want to install git, there is a link above to download
the contents of this repository as a zip file.  I may make minor changes to
the repository in the days before the tutorial, however, so cloning the
repository is a much better option.

## Notebook Listing
You can [view the tutorial materials](http://nbviewer.ipython.org/github/leoferres/nlp4twitter_tutorial/blob/master/notebooks/00-bibs.ipynb) using the excellent nbviewer service.

Note, however, that you cannot modify or run the contents within nbviewer.
To modify them, first download the tutorial repository, change to the notebooks directory, and run ``ipython notebook``.
You should see the list in the ipython notebook launch page in your web browser.
For more information on the IPython notebook, see http://ipython.org/notebook.html

Note also that some of the code in these notebooks will not work outside the
directory structure of this tutorial, so it is important to clone the full
repository if possible.
