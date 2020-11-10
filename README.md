# dl-eeg-tutorial
Hands-on tutorial on deep learning for EEG classification.

In this hands-on tutorial, you will train a convolutional neural network to identify sleep stages from raw EEG signals, and try to improve the classification performance of an existing model. The tutorial will guide you through the different steps of loading publicly available sleep recordings, preparing the data for training, creating a neural network, training it, and analyzing its behaviour. The tutorial is based on the open source packages MNE-Python and pytorch and can be run using Google Colab.

Inspiration for this tutorial was taken from the [MNE-Python](https://mne.tools/stable/auto_tutorials/sample-datasets/plot_sleep.html) and [braindecode](https://braindecode.org/auto_examples/plot_sleep_staging.html) sleep staging examples, as well as the [`mne-torch`](https://github.com/mne-tools/mne-torch) repository.

[**Open this tutorial in Google Colab**](https://colab.research.google.com/github/hubertjb/dl-eeg-tutorial/blob/main/sleep_staging_physionet.ipynb)

## Running locally

To run this tutorial locally, make sure the repo has been cloned on your machine, and that the required packages are installed in a Python environment (3.6 or above). The packages can be installed by running:
```
pip install -r requirements.txt
```

The entire tutorial is contained in `sleep_staging_physionet.ipynb` and can be run with `jupyter notebook`.
Tested on Ubuntu 20.04.

## Authors

[Hubert Banville](https://hubertjb.github.io/)
