# [pysimilar](https://pypi.org/project/pysimilar)

[![Downloads](https://pepy.tech/badge/pysimilar)](https://pepy.tech/project/pysimilar)
[![Downloads](https://pepy.tech/badge/pysimilar/month)](https://pepy.tech/project/pysimilar)
[![Downloads](https://pepy.tech/badge/pysimilar/week)](https://pepy.tech/project/pysimilar)

A python library for computing the similarity between two string(text) based on cosine similarity made by [kalebu](https://github.com/Kalebu)

<a href="https://www.buymeacoffee.com/kalebuj" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="41" width="174"></a>


How does it work ?
------------------

It uses Tfidf Vectorizer to transform the text into vectors and then obtained vectors are converted into arrays of numbers and then finally cosine similary computation is employed resulting to output indicating how similar they are.

Installation
-------------
You can either install it directly from *Github* or use *pip* to install it, here is how you to install it directly from github;

```bash
$  git clone https://github.com/Kalebu/pysimilar
$  cd pysimilar
$ pysimilar -> python setup.py install

```

Installation with pip
----------------------

```python
$ pip install pysimilar
```

Example of usage
----------------
Pysimilar allows you to either specify the string you want to compare directly or specify path to files containing string you want to compare.

Here an example on how to compare strings directly;

```python
>>> from pysimilar import compare
>>> compare('very light indeed', 'how fast is light')
0.17077611319011649
```

Here how to compare files with textual documents;

```python
>>> compare('README.md', 'LICENSE', isfile=True)
0.25545580376557886
```

Contributions
-------------
If you have anything valuable to add to the *lib*, whether its a documentation, typo error, source code, please don't hesitate to contribute just fork it and submit your pull request and I will try to be as friendly as I can to assist you making the contributions.


Give it a star
--------------
Did you find this repo useful to you ? then give it a star so as more people can be aware of it and use it, Share that love *

All the Credits
---------------

All the Credits to [kalebu](https://github.com/Kalebu) and other future contributors 