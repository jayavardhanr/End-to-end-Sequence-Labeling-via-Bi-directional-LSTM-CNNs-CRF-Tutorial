# End-to-end-Sequence-Labeling-via-Bi-directional-LSTM-CNNs-CRF-Tutorial

This is a PyTorch tutorial for the ACL'16 paper 
[**End-to-end Sequence Labeling via Bi-directional LSTM-CNNs-CRF**](http://www.aclweb.org/anthology/P16-1101)

This repository includes

* [**IPython Notebook of the tutorial**](https://github.com/jayavardhanr/End-to-end-Sequence-Labeling-via-Bi-directional-LSTM-CNNs-CRF-Tutorial/blob/master/Named_Entity_Recognition-LSTM-CNN-CRF-Tutorial.ipynb)
* Data folder
* Setup Instructions file
* Pretrained models directory (The notebook will automatically download pre-trained models into this directory, as required)

### Authors

[**Anirudh Ganesh**](https://github.com/TheAnig)

[**Peddamail Jayavardhan Reddy**](https://github.com/jayavardhanr)


### Installation
The best way to install pytorch is via the [**pytorch webpage**](http://pytorch.org/)

### Setup

#### Creating new Conda environment
`conda create -n pytorch python=3.5`

#### Activate the condo environment
`source activate pytorch`

#### Setting up notebooks with specific python version (python 3.5)
```
conda install notebook ipykernel
ipython kernel install --user
```

#### PyTorch Installation command:
`conda install pytorch torchvision -c pytorch`

#### NumPy installation
`conda install -c anaconda numpy`

#### Download GloVe vectors and extract glove.6B.100d.txt into "./data/" folder

`wget http://nlp.stanford.edu/data/glove.6B.zip`

#### Data Files


You can download the data files from within this repo [**over here**](https://github.com/TheAnig/NER-LSTM-CNN-Pytorch/tree/master/data)