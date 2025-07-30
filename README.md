# nlp_fake_news_classification
Classifying fake news and performing other NLP operations on the dataset. This is my solution to the practical task in the [Intro to NLP Course](https://github.com/l-newbould/introtonlp-365) by [Lauren Newbould](https://github.com/l-newbould) with some additional insights added.

## Requirements

Python version 3.12 or lower is required. This is because one of the dependencies is currently [not compatible](https://github.com/piskvorky/gensim/issues/3601#issuecomment-2812768956) with the latest version of Python.

### Installation using Anaconda

This setup guide assumes you already have Anaconda installed. If not, you can visit [https://www.anaconda.com/](https://www.anaconda.com/) and follow the instructions there.

For the purpose of this demonstration, let us assume that the virtual environment is called `nlp_env`. Run the following commands in your terminal:

```
conda create --name nlp_env python==3.12
conda install jupyter
pip install -r requirements.txt
python -m spacy download en_core_web_sm
```

To load a Jupyter notebook, you can simply type `jupyter notebook` in your terminal.
