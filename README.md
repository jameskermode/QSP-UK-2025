# QSP-UK 2025

The [marimo](https://github.com/marimo-team/marimo) notebook [UQ.py](UQ.py) contains the code and slides from my [QSP-UK 2025](https://warwick.ac.uk/fac/sci/eng/research/grouplist/biomedicaleng/qsp-uk/) talk.

I talked about uncertainty quantification, predictive modelling and scientific machine learning and the potential future application of these and other techniques we are developing in the [HetSys CDT](https://warwick.ac.uk/fac/sci/hetsys/) and the [Warwick Centre for Predictive Modelling](https://warwick.ac.uk/WCPM) at Warwick to pharmacokinetics models.

To run the demo, install marimo then instantiate a sandbox environment with the required dependencies:

```
pip install marimo
marimo run --sandbox UQ.py
```

### Further Reading

No single textbook covers all the topics in this emerging area. The following books provide good coverage of most of the topics:

- Uncertainty Quantification and Predictive Computational Science, McClaren available from [Springer](https://link.springer.com/book/10.1007/978-3-319-99525-0)
- Understanding Deep Learning, Simon Prince (2023). [PDF version](https://udlbook.github.io/udlbook/) freely available.

### Acknowledgements

- The first version  of the catalysis example was originally adapted from [an excellent UQ course](https://github.com/PredictiveScienceLab/uq-course) by [Ilias Bilionis](https://predictivesciencelab.org/). More details are available in [Tsilofis2014](https://arxiv.org/abs/1410.5522)
- The material on optimisation, SciML and MCMC were adapted from my [PX914]([https://courses.warwick.ac.uk/modules/2023/PX914-15](https://courses.warwick.ac.uk/modules/2024/PX914-15)) and [ES98E](https://courses.warwick.ac.uk/modules/2024/ES98E-15) postgraduate modules taught in the [HetSys CDT](https://warwick.ac.uk/fac/sci/hetsys/) at Warwick.

