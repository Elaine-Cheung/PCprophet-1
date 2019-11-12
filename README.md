# PCprophet

Software toolkit for protein complex prediction and differential analysis of cofractionation mass spectrometry datasets

## Getting Started

These instructions will get you a copy of the project up and running on your local machine and how to test the compatibility with your current Python packages
### Prerequisites

* [Python 3.x](https://www.python.org)
* [Sklearn 0.20.3](https://pypi.org/project/sklearn/)
* [NetworkX >2.1](https://networkx.github.io)
* [Pandas >0.23](https://pandas.pydata.org)
* [Scipy >1.1.0](https://www.scipy.org)
* [Java vxx](https://www.java.com)

### Installing

We recommend using [anaconda](https://www.anaconda.com) as it contains all required packages for PCprophet

#### Command line version

```
github clone https://github.com/fossatiA/PCprophet PCprophet
```
This will get you a working copy copy of PCprophet

> **note** for the command line version only Python3 and related package dependencies are necessary

#### GUI version


- Install Java vxx
- Clone the repo

```
github clone https://github.com/fossatiA/PCprophet PCprophet
```


## Running the tests

The test module included with PCprophet tests most of the used function and the compatibility of the pickled model with the installed Sklearn version

### Test model


```
python3 PCprophet/test/test_model.py
```
PCprophet.Exceptions.ModelError will be raised in case of not compatibility and it will be necessary to downgrade the current Sklearn to a compatible version

### Test functions

```
python3 PCprophet/test/test_methods.py
```

PCprophet.Exceptions.MethodError will be raised in case of not compatibility and it will be necessary to downgrade the current Sklearn/Scipy/Pandas to a compatible version

## Usage

For usage of PCprophet refers to the [PCprophet_instructions.md](https://github.com/fossatiA/PCprophet/blob/master/PCprophet_instructions.md)


## Built With

* [Pynstaller](https://www.pyinstaller.org) - Package builder
* [...](....) - GUI builder


## Contributing

Please read [CONTRIBUTE.md](https://github.com/fossatiA/PCprophet/blob/master/CONTRIBUTE.md) for details on our code of conduct, and the process for submitting pull requests to us.


## Authors

* **Andrea Fossati** - *Initial work* - [fossatiA](https://github.com/fossatiA) fossati@imsb.biol.ethz.ch
* **Chen Li** - *Initial work* - chen.li@monash.edu

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* [mojaje](https://github.com/mojaie/pygosemsim) for the implementation of GO tree parsing
