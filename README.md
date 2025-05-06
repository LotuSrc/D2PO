# D^2PO

This repository contains the code in both PyTorch for our paper.

> [**Earlier Tokens Contribute More: Learning Direct Preference Optimization From Temporal Decay Perspective**](https://arxiv.org/abs/2502.14340)


## Quick Start

The config template is in examples/exp. When gamma is set smaller than 1.0, the experiment runs in D^2PO mode.
```bash
llamafactory-cli train examples/exp/llama3_full_d2po.yaml
```