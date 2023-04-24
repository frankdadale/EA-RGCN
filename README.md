# Smart contract vulnerability detection based on semantic graph and residual graph convolutional networks with edge attention

## Usage.
- Unzip  ```/utils/python-solidity-parser-master.zip```, and run ```python3 setup.py install```.
- Configure the source code path in ```/utils/Sourcecode2AST.ipynb``` before running it.
- Run ```SG.ipynb``` to convert AST files to **Semantic Graph** and **Edge Series**.
- Run ```BFS_EA_RGCN(SG).ipynb``` to train the model to get the final result.

## requirements
- scikit-learn==1.1.1
- scipy==1.5.0
- torch-geometric==2.2.0
- torch==1.9.1
- tqdm==4.47.0
- /utils/layer.py
- /utils/utils.py
- /utils/pytorchtools.py


## Citation

If you find this work helpful, please kindly cite our [paper](https://www.sciencedirect.com/science/article/pii/S0164121223001000?dgcid=coauthor).

```
@article{CHEN2023111705,
title = {Smart contract vulnerability detection based on semantic graph and residual graph convolutional networks with edge attention},
journal = {Journal of Systems and Software},
volume = {202},
pages = {111705},
year = {2023},
issn = {0164-1212},
doi = {https://doi.org/10.1016/j.jss.2023.111705},
url = {https://www.sciencedirect.com/science/article/pii/S0164121223001000},
author = {Da Chen and Lin Feng and Yuqi Fan and Siyuan Shang and Zhenchun Wei},
keywords = {Smart contract vulnerability detection, Code graph, Graph convolutional networks, Edge attention, Residual block}
}
```