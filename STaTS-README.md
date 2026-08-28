# STaTS

Code for **STaTS: Structure-Aware Temporal Sequence Summarization via Statistical
Window Merging**, published in *Pattern Recognition Letters*, Vol. 202,
pp. 135–140, 2026.

[Paper](https://doi.org/10.1016/j.patrec.2026.02.014) ·
[arXiv](https://arxiv.org/abs/2510.09593) ·
DOI: [10.1016/j.patrec.2026.02.014](https://doi.org/10.1016/j.patrec.2026.02.014)

## What it does

STaTS is a lightweight, unsupervised framework for structure-aware summarization
of temporal sequences. It adaptively compresses a time series by merging
statistically similar windows, using a BIC-based multi-scale change detection
criterion to decide where structure actually changes.

On 150+ datasets spanning the UCR, UEA and ETT benchmarks, it reaches up to
**30× input compression while retaining 85–90% of full-resolution model
accuracy**.

## Contents

| File | Description |
|---|---|
| `main_code_3_task.ipynb` | Reference implementation and experiments across the three downstream tasks reported in the paper |

## Requirements

Python 3.9+, with:

```
numpy
pandas
scikit-learn
matplotlib
```

Install with `pip install numpy pandas scikit-learn matplotlib`, then open the
notebook in Jupyter.

## Citation

```bibtex
@article{bhowmick2026stats,
  title   = {STaTS: Structure-aware temporal sequence summarization via statistical window merging},
  author  = {Bhowmick, Disharee and Ramanathan, Ranjith and Aakur, Sathyanarayanan N.},
  journal = {Pattern Recognition Letters},
  volume  = {202},
  pages   = {135--140},
  year    = {2026},
  doi     = {10.1016/j.patrec.2026.02.014}
}
```

## Contact

Disharee Bhowmick — dzb0110@auburn.edu · [dzb0110.github.io](https://dzb0110.github.io)
