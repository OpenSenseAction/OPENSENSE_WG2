# OPENSENSE_WG2
Info on WG2 "Method and software homogenisation" of COST Action OPENENSENSE

## Table for available OS processing software

name | description | language | packaging | CI | License 
-----|-------------|----------|----------|----|--------
| [pycomlink](https://github.com/pycomlink/pycomlink) | CML processing methods | Python | pypi, conda-forge | yes | BSD-3-clause 
| [RAINLINK](https://github.com/overeem11/RAINLINK) | CML processing methods | R | none | no | GPL v3 (not in repo) |
| [TITAN](https://github.com/metno/TITAN/) | Automatic quality control of in-situ observations | R, C++ | none | tests, but no CI | GPL v3 |
| [PWSQC](https://github.com/LottedeVos/PWSQC)| Quality control of PWS data | R | none | no | (cc-by-sa 4.0) |
| [PyNNcml](https://github.com/haihabi/PyNNcml)| CML processing methods | Python | none | yes | MIT |
| [Rcmlrain](https://github.com/fenclmar/Rcmlrain)| CML processing methods | R | none | no | MIT |
| [pws-pyqc](https://github.com/AbbasElHachem/pws-pyqc)| Quality control of PWS data | Python | none | no | GPL v3 |
| [intense-qc](https://github.com/nclwater/intense-qc) | Quality control of hourly rainfall data | Python | pypi | yes | None
| to be continued... | | | |  |

## Pathway towards better accessibility of software

1. Add URL to list above
2. Add license to repo
3. Make install as easy as possible (provide environment specifications or use package manager)
4. Add unit tests
5. Set guidlines for contributions
