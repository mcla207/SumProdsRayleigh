# On the Exact Sum of Products of Rayleigh Envelopes With Application to RIS

[![DOI](https://zenodo.org/badge/1448778071.svg)](https://doi.org/10.5281/zenodo.24022854)

Code accompanying the article:

> M. C. Luna Alvarado, C. R. Nogueira da Silva, L. P. Jiménez Jiménez,
> F. D. Almeida García, G. Fraidenraich, J. C. S. Santos Filho, and M. D. Yacoub,
> "On the Exact Sum of Products of Rayleigh Envelopes With Application to RIS,"
> *IEEE Wireless Communications Letters*, vol. 13, no. 8, pp. 2145–2149, Aug. 2024.
> DOI: [10.1109/LWC.2024.3403391](https://doi.org/10.1109/LWC.2024.3403391)

## Contents

| File | Description | Figure in the paper |
|---|---|---|
| `ABER.nb` | Average bit error rate of the RIS-aided system versus SNR, for i.i.d. and i.n.i.d. cascade fading: exact, CLT-based approximation, and asymptotic results | Fig. 1 |
| `KS-Statistic.nb` | Kolmogorov-Smirnov statistic between the sum of products of Rayleigh envelopes and its CLT-based normal approximation, versus the number of terms in the sum | Fig. 2 |

Each notebook implements the corresponding expressions of the paper and
generates the figure. [Analytical results are compared against Monte Carlo
simulations with 10^6 iterations included in the notebook.]

Note: the exact expressions are given in terms of multivariate Fox
H-functions, whose evaluation time grows quickly with the number of RIS
elements N. As in the paper, exact results are computed for N ≤ 6.

## Requirements

- Wolfram Mathematica [version, e.g. 13.3]

## Usage

Open the notebook in Mathematica and evaluate all cells by clicking on the Run all button. The figures are generated at the end of
each notebook.

## Citation

If you use this code, please cite the article above:

```bibtex
@article{LunaAlvarado2024,
  author  = {Luna Alvarado, Maria Cecilia and Nogueira da Silva, Carlos Rafael and Jim{\'e}nez Jim{\'e}nez, Lenin Patricio and Almeida Garc{\'i}a, Fernando Dar{\'i}o and Fraidenraich, Gustavo and Santos Filho, Jos{\'e} C{\^a}ndido Silveira and Yacoub, Michel Daoud},
  title   = {On the Exact Sum of Products of Rayleigh Envelopes With Application to {RIS}},
  journal = {IEEE Wireless Communications Letters},
  volume  = {13},
  number  = {8},
  pages   = {2145--2149},
  year    = {2024},
  doi     = {10.1109/LWC.2024.3403391}
}
```

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE).
