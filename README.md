# Jupyter notebooks for machine translation technology teaching
DEPRECATION NOTE: The Jupyter notebooks in this repository are no longer up to date. Updated versions of the notebooks can be found on the [DataLit<sup>MT</sup> website](https://itmk.github.io/The-DataLitMT-Project/resources/) or in the [DataLit<sup>MT</sup> github repository](https://github.com/ITMK/DataLitMT).

This is a collection of Jupyter notebooks developed as teaching aids for machine translation teaching in the [MA in Specialised Translation](https://www.th-koeln.de/en/academics/specialized-translation-masters-program_7498.php) programme at the Institute of Translation and Multilingual Communication at TH Köln, Germany. The notebooks are provided as open-source resources under the MIT License and can be used by interested parties for their own translation technology classes.  

The notebooks are provided in three forms:

**1)** As downloadable .jpynb files in this GitHub repository. The notebooks can be run on top of a local Python environment or uploaded to cloud-based environments such as Kaggle or Colaboratory (a Colab version of the notebooks is already provided).  

**2)** As Colab notebooks which can be run directly in Colaboratory.  

**3)** In a separate Binder environment, where they can also be run directly online.  

More information on how to run Jupyter notebooks in different environments and how to employ them in teaching scenarios can be found in [Barba et al. (2019): Teaching and Learning with Jupyter](https://jupyter4edu.github.io/jupyter-edu-book/). This book is an excellent resource which provides a wealth of information for lecturers interested in using Jupyter notebooks as didactic instruments in their courses.  

Initially, four notebooks are provided in this repository, two notebooks concerned with calculating string-based and word embedding-based MT quality scores and two notebooks for exploring word embeddings in the context of neural machine translation. In the future, further notebooks will be added to the repository.

#### Note on the GitHub versions of the notebooks
Sometimes, when you click on one of the notebooks in the list above in order to see its content, GitHub will not load and display the notebook properly. This is a recurring issue on GitHub's side for which there does not seem to be any permanent solution yet. If this happens, just right-click on the notebook you want to display, copy the link to the clipboard and paste it in [Jupyter's nbviewer](https://nbviewer.jupyter.org/). 

## Links to the Colab versions of the notebooks  
In order to run the notebooks in Colaboratory, a Google account is required. Also, the housekeeping steps at the beginning of the notebooks have to be run.

- [Understanding Word Embeddings for NMT – Fundamentals](https://colab.research.google.com/drive/1UUteTlvULD8mSh94Hd6pmL5OudP8l9bc?usp=sharing)
- [Understanding Word Embeddings for NMT - Exploring the Google News Model](https://colab.research.google.com/drive/1lpWc88AKJhFi8fVvbB6Lhtq8i_EtCjhY?usp=sharing)
- [MT Quality Score Calculator for Metrics Based on String Matching](https://colab.research.google.com/drive/19Mub2IJV6SoyuvvsyjSeaGiSQ1q433jD?usp=sharing)
- [MT Quality Score Calculator for Embedding-Based Metrics](https://colab.research.google.com/drive/1pK479-xhDSDHrJA4OTfU1tXV6Pwp_G4f?usp=sharing)


## Link to the Binder environment
In the Binder environment, all packages required for running the notebooks are already preinstalled. Hence, the housekeeping steps at the beginning of the notebooks can be skipped.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ITMK/MT_Teaching/HEAD)

#### Note on running the notebook on embedding-based MT quality scores in the Binder environment: 
The MT quality scores discussed in this notebook rely on rather large language models, which have to be loaded into the Binder environment in order to calculate the scores. However, loading these models may exceed the memory available in the Binder environment. Therefore, it may be advisable to run this notebook in Colab or on top of a local Python distribution instead. 
