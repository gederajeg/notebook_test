This is a test repo for deploying R notebook on GitHub

Important steps include:

- create .Rmd Notebook file and name it as `index.Rmd`.
- save the .Rmd file into a notebook named `index.nb.html`. This html notebook file will be the website content hosted by GitHub.
- create a symlink .html file from terminal as follows: `ln -s index.nb.html index.html`. This idea comes from @RaoOfPhysics based on [#1020](https://github.com/rstudio/rmarkdown/issues/1020), and from the example in @jcvdav [repo](https://github.com/jcvdav/CausalInference).
- These files can be put in the root directory of the repo (as in @jcvdav's [repo](https://github.com/jcvdav/CausalInference)).

