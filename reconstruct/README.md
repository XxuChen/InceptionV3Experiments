# Various Experiments on Inception V3 Architecture

This repository is aimed to do various experiments on Inception V3 Architecture. The whole repository is based on Tensorflow Inception V3 Image Recognization.

## Getting Started

### Runtime Environment

```
python3
```

### Fetch Checkpoint Files from Inception V3 Architecture

Go to ```./data_prep```, and run

```
$ python download.py
```

### Fetch Dataset from ImageNet

Go to ```./```, and run 

```
$ python scrape_dataset.py
```

or specify the parameters

```
$ python scrape_dataset.py --upper 1000 --read_mode 'RANDOM' --seed 5
```

# References
https://github.com/tensorflow/models