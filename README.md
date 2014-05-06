# A Walk Through Big Data Genomics Data Types

You can view this notebook online via iPython's nbviewer [here](http://nbviewer.ipython.org/github/hammerlab/bdgenomics-notebook/blob/master/Big-Data-Genomics-Tutorial.ipynb). (Note, for some reason raw text fields lose formatting when viewed this way: downloading and locally running this notebook makes viewing those fields easier.)

This [iPython notebook](http://ipython.org/) is meant to introduce you to the various datatypes used with the ADAM stack to process next-generation sequencing (NGS) data.

To get up and running, simply start the iPython notebook in this directory with `ipython notebook` and open the notebook.

ADAM uses [Avro](http://avro.apache.org/) to specify its datatypes, and thus you must have the `avro` Python package installed in order to run this tutorial. The easiest way to do this is with `pip install avro`.
