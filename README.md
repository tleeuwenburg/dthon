# Python Dthon

This repository holds setup instructions for creating a Python environment which is well-suited to data science and machine learning projects. It can be used by anyone wanting to set up for a hackathon, data hackathon, or personal project which involves working with data in a variety of ways.

It assumes minimal prior knowledge, and attempts to automate as much of the process as possible. It is expected to work easily on both Linux and Mac environments. The technologies should work well on Windows, but the automation scripts may not work (merge requests welcome).

The list of packages is a curated list of best-of-breed alternatives. There are many other fine packages which could be used, but the objective of this repository is to reduce the complexity of choosing a working tech stack.

## Overview of the Process ##

1. Install miniconda manually. https://conda.io/docs/install/quick.html has relevant installation instructions.
2. Run "create_minimal.sh" to create and activate a "named" style environment called "dthon".
3. Run "add_standard.sh" to add a the basic package set to the current virtual environment

Alternatively, you can run "add_everything.sh" for a comprehensive set of packages.

## Additional Packages ##

In order to simplify the "base build", reduce the complexity of the environment and reduce the size of the download, some additional scripts are present which can install additional functionality which may be of use. These may be found in the "additions" directory.

## Notes for Windows users ##

If you are on Windows, you should have no trouble installing the miniconda environment following the instructions in the quick install guide (linked above). The additions scripts are calls to the "conda" command, which should work as-is regardless of platform. If you run through the same sequence of commands as contained in the .sh scripts, you should be able to reproduce the dthon environment without issue. However, this is untested, so there are no guarantees.

## Documentation and getting started ##

This repository does not include any examples, tutorials or test cases. This is to keep the scope well-defined and small. However, in future as an extension exercise, creating additional walkthrough or tutorial repositories based on the dthon environment could be very useful. Please get in touch if you would find this helpful.
