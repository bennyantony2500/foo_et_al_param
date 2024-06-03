This repository contains a software package and supporting materials for the complex yet ficticious Foo parameterization for atmosphereic sea-spray physics. Currently, the code simply calculates the volume of a sphere from a user-supplied radius.

The main software to perform this calculation is contained within the foo_parameterization module.

Installation
The software is intended to operate in a Python 3 environment, however it has only been tested with Python 3.9 specifically.

To install the foo_parameterization package, simply run:

pip install foo_parameterization
This should install the package and any necessary dependencies.

Another option for installing is using conda. More information about conda and how to acquire/install it can be found here:

Miniconda or
Anaconda
With conda installed, users can install the environment by running:

conda env create -f environment.yml
conda activate foo-env
Usage
To run the software from the command line:

python foo_parameterization.py -r <radius>
where <radius> is the radius from which to calculate the volume of a sphere.

To run the software from within a python environment:

from foo_parameterization import foo_parameterization
foo = foo_parameterization.FooParameterization()
result = foo.calculate(1.0)
How to Contribute
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
