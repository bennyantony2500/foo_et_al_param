This repo contains a python package that helps in solving a complex Foo et al parameterization. The code is in test phase so currently it takes in radius of a sphere and outputs the volume. 

Th main software to perform this calculation is contained within the parameters_fooetall directory.

# Installation
The software is tested primarily with Python 3.11 but can operate in Python 3 environment.

To install the package
'''
pip install parameters-fooetall==0.1
'''
The only other dependency you might need is argparse

'''
pip install argparse
'''

# Running the software

```
from parameters_fooetall import main
foo=main.params()
result = foo.calculate(1.0)
```



# How to Contribute
If you would like to contribute changes to this repository, please do the following:

Make a local copy of the this repository by cloning the repository (e.g. git@github.com:bourque/foo_parameterization.git).

Create a branch on the clone to develop software changes on.

git branch <branchname>
git checkout <branchname>
Perform local software changes using the nominal git add/git commit -m cycle:
git status - allows you to see which files have changed.
git add <new or changed files you want to commit>
git commit -m 'Explanation of changes you've done with these files'
Push the branch to the repository with git push origin <branchname>.

In the repository on GitHub, create a pull request for the recently pushed branch.

Assign the pull request a reviewer. They will review your pull request and either accept the request and merge, or ask for additional changes.

Iterate with your reviewer(s) on additional changes if necessary, addressing any comments on your pull request.

Once the pull request has been accepted, it will be merged.
