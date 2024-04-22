# Use GPU on Apple Silicon

## Environment

* MacBook Pro (13-inch, M1, 2020)
* macOS Sonoma 14.4.1
* Python 3.10.14 (via Homebrew)

## virtualenv

```bash
python -m venv .venv
source .venv/bin/activate
```

## Tensorflow

```bash
pip install -r requirements-tf.txt
```

## Pytorch

```bash
pip install -r requirements-torch.txt
```

## Run

```bash
# Tensorflow
python app-tf.py

# Pytorch
python app-torch.py
```

## References

* Tensorflow
  1. <https://developer.apple.com/metal/tensorflow-plugin/>
* Pytorch
  1. <https://developer.apple.com/metal/pytorch/>
  2. <https://pytorch.org/get-started/locally/>
