# Hacking-the-Wiki-Games

If the notebook is not rendered, visit https://nbviewer.jupyter.org/github/kevin1kevin1k/Hacking-the-Wiki-Games/blob/master/linguistics-final.ipynb.

### Instructions for running the notebook

- Visit https://fasttext.cc/docs/en/pretrained-vectors.html and download the pre-trained Ensligh model. Alternatively, you can run

  ```bash
  wget https://dl.fbaipublicfiles.com/fasttext/vectors-wiki/wiki.en.zip
  unzip wiki.en.zip
  ```

  **Note that the model takes up more than 10GB space.**

- Install the required Python packages

  ```bash
  pip install -r requirements.txt
  ```

- Download WordNet in Python by running

  ```python
  import nltk
  nltk.download()
  # Then interactively download WordNet
  ```

- Now you can run the notebook!

  **Note that it may take a while (~10 mins) to load the model.**