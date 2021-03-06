This fork fixes the problems inherent with the original ctcdecode: https://github.com/parlance/ctcdecode

Fix for ```RuntimeError: Not enough space``` used from https://github.com/parlance/ctcdecode/issues/124

## Installation:

```bash
# get the code
git clone --recursive https://github.com/anicolson/ctcdecode.git
cd ctcdecode
pip install .
```

# FROM ORIGINAL CTCDECODE:

## ctcdecode

ctcdecode is an implementation of CTC (Connectionist Temporal Classification) beam search decoding for PyTorch.
C++ code borrowed liberally from Paddle Paddles' [DeepSpeech](https://github.com/PaddlePaddle/DeepSpeech).
It includes swappable scorer support enabling standard beam search, and KenLM-based decoding.

### Installation
The library is largely self-contained and requires only PyTorch 1.0. Building the C++ library requires gcc or clang. KenLM language modeling support is also optionally included, and enabled by default.

```bash
# get the code
git clone --recursive https://github.com/parlance/ctcdecode.git
cd ctcdecode
pip install .
```
