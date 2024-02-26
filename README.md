# word2vec-skipgram
This is a training model for [word2vec](https://arxiv.org/pdf/1301.3781.pdf) using skipgram. The loss functions are naive-softmax and negative sampling. The training dataset is Stanford Sentiment Treebank (SST) 

## Set up the environment
Run the following in the terminal to set up the environment(Install [anaconda](https://www.anaconda.com/download/) in advance)
```
conda env create -f env.yml

conda activate word2vec
```
If you want to exit the environment, run
```
conda deactivate
```
## Get the dataset
We are going to use the Stanford Sentiment Treebank (SST) dataset to train word vectors. To fetch the dataset, run
```
sh get_datasets.sh
```
You can also use your own dataset to train the model by editing the file.
## Train the model
Run the python file to train the model. The parameters will be saved.
```
python run.py
```
