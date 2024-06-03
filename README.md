This repo contains a python package that helps in solving a complex Foo et al parameterization. The code is in test phase so currently it takes in radius of a sphere and outputs the volume. 

Th main software to perform this calculation is contained within the parameters_fooetall directory.

# Installation
The software is tested primarily with Python 3.11 but can operate in Python 3 environment.

To install the package
```
pip install parameters-fooetall==0.1

```


The only other dependency you might need is argparse


`pip install argparse`


# Running the software

```
from parameters_fooetall import main
foo=main.params()
result = foo.calculate(1.0)
```




# Contributing to Fooetalparam

Thank you for considering contributing to Fooetalparam! Here are some guidelines to help you get started.

## How to Contribute

1. **Fork the repository**: Click the "Fork" button on the top right of the repository page.
2. **Clone your fork**: 
   `   git clone https://github.com/bennyantony2500/fooetalparam.git`
3. **Create a branch**:
   `git checkout -b my-feature-branch`

 4. **Make your changes**
 5. **Commit your changes**:
     `git checkout -b my-feature-branch`
 6. **Push to your branch**:
    `git push origin my-feature-branch`
 7. **Create a Pull Request**: Go to your fork on GitHub and click the "New Pull Request" button. Once pull request is accepted it will be merged.
