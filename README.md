# Advanced_GAIN

An attempt to boost the performance of PyTorch implementation of(https://arxiv.org/abs/1806.02920).

- The code is taken from (https://github.com/dhanajitb/GAIN-Pytorch). The datasets are also present in the amazing repository. The code of generator and discriminator is modified in the notebook. However results are not so good.

- The idea is to use Network Deconvolution(https://arxiv.org/abs/1905.11926) model in generator and discriminator to improve the performance.

- Network deconvolution code: (https://arxiv.org/abs/1905.11926)

- The notebook is tested on Python 3.6 and PyTorch 1.4.0.

- The code can be run in either GPU or CPU (using use_gpu flag).


Contributing
------------
- For major changes, please open an [issue](https://github.com/purbayankar/Advanced_GAIN/issues) first to discuss what you would like to change.

- If you want to contribute please:
1. Fork the Project
2. Create your Feature Branch (`git checkout -b <your_branch_name>`)
3. Stage your Changes (`git add .`)
4. Commit your Changes (`git commit -m '<your_commit_message>'`)
5. Push to the Branch (`git push origin <your_branch_name>`)
6. Open a [Pull Request](https://github.com/purbayankar/Advanced_GAIN/pulls)
