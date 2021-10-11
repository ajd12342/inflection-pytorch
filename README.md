# Stem2Morph: Low-Resource Morphological Inflection
This is a fork of [https://github.com/antonisa/inflection](https://github.com/antonisa/inflection).

We reimplement the original code from `inflection.py` (which is in `dynet`) in Pytorch. The Pytorch code can be found in `torch_inflection.py`.
This was done as part of a course project for CS772 Spring 2021, IIT Bombay.

Install the requirements using
```
pip install -r requirements.txt
```

Download data from [this](https://github.com/sigmorphon/2019/tree/master/task1) URL and copy the `task1` folder into this repo,renaming `task1` to `all-data`.

Presentation slides at https://github.com/ajd12342/inflection-pytorch/blob/master/presentation.pdf.

Contributors - Yash Sharma, Diwan Anuj Jitendra, Aditya Vavre
