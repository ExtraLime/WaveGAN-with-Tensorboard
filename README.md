# WaveGAN-with-Tensorboard
This is an example of how to train Chris Donahue's WaveGAN while monitoring it on Tensorboard.

The notebooks:
  1. WG-SC09-1.12:
    - This notebook will closely replicate the work that Chris Donahue did for the landmark paper.  No need to download any supplementary data.
      + The notebook installs the versions of dependencies that are recommended by Chris, installs CUDA 9 for compatibility, and will download the SC09 training data that Chris used to train his model.
  2. WG-SCO9-1.13: This notebook is the same as the above notebook, however, it runs on TF 1.13 and is compatible with CUDA 10. (You will see deprication warnings!)
  3.
