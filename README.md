# Pedagogical material for _surveygraph_

|   |  |
| ------------- | ------------- |
| ![ERC Logo](https://erc.europa.eu/sites/default/files/inline-images/LOGO_ERC-FLAG_FP.png) | Development of surveygraph software and training materials was initially funded by the European Union under the ERC Proof-of-concept programme (ERC,  Attitude-Maps-4-All, project number: 101069264). Views and opinions expressed are however those of the author(s) only and do not necessarily reflect those of the European Union or the European Research Council Executive Agency. Neither the European Union nor the granting authority can be held responsible for them.   |
|   |  |

Learning resources for the surveygraph R and python packages

Navigate to 

* __presentations__ to see how GitHub displays a dummy presentation 
* __gallery__ to see network visualisations of survey data 
* __scripts__ for jupyter notebooks and R scripts
* __feedback__ for a google survey to give us feedback on the package

_Note that none of this material exists yet, this is simply a mockup README file._

### Setting up an environment

We prefer jupyter notebooks for these tutorials. To install an R kernel,

```
install.packages('IRkernel')
IRkernel::installspec()  # to register the kernel in the current R installation
```

We then run

```
jupyter labextension install @techrah/text-shortcuts  # for RStudio’s shortcuts
```

This requires Jupyter, as well as R, to be installed. For more information see https://github.com/IRkernel/IRkernel.
