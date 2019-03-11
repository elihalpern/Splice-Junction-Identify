# Identifying Splice Junctions in Primate DNA using Time Series Classification

In this project, the aim is to develop a method of classifying whether a given section of primate DNA contains a splice junction or not. Furthermore, determining whether the splice junction is exon-intron, or intron-exon. This will be accomplished using a Time Series Classification model, specifically using Dynamic Time Warping.

## Getting Started

To run this file, make sure you have [Python 3.7.2](https://www.python.org/), [Jupyter Notebook](https://jupyter.org/), and (optionally) [Anaconda](https://www.anaconda.com/) installed.

### Prerequisites

* [Numpy](https://www.numpy.org/) >= 1.16.2
* [Pandas](https://pandas.pydata.org/) >= 0.24.1
* [Scikit-learn](https://scikit-learn.org/) >= 0.20.2
* [Matplotlib](https://matplotlib.org/) >= 3.02

All these can be installed automatically using the [requirements.txt](requirements.txt) file:
```
pip install -r requirements.txt
```
or if you're using Anaconda, create a virtual environment:
```
conda create --name splice_junction --file requirements.txt
```

### Running

Navigate to the directory with the ipynb file, and then launch Jupyter:

```
jupyter notebook
```

## Author

**Eli Halpern** 

## License

This project is licensed under the GNU General Public License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Dr. Abolfazl Saghafi, my research advisor who guided me through this project
* Dr. Zhijun Li, head of the Bioinformatics department at USciences