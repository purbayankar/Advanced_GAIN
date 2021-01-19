# Advanced_GAIN

An attempt to boost the performance of PyTorch implementation of(https://arxiv.org/abs/1806.02920).

- The code is taken from (https://github.com/dhanajitb/GAIN-Pytorch). The datasets are also present in the amazing repository. The code of generator and discriminator is modified in the notebook. However results are not so good.

- The idea is to use Network Deconvolution(https://arxiv.org/abs/1905.11926) model in generator and discriminator to improve the performance.

- Network deconvolution code: (https://arxiv.org/abs/1905.11926)

- The notebook is tested on Python 3.6 and PyTorch 1.4.0.

- The code can be run in either GPU or CPU (using use_gpu flag).
