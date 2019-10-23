Issues are a great way to keep track of tasks, enhancements, and bugs for your projects (https://guides.github.com/features/issues/). When submitting, you need to provide the following elements:

### If you are reporting a bug:

- [ ] The code that is producing the error, it has to be a minimal reproducible example.
Stackoverflow is providing good explanations about it: https://stackoverflow.com/help/mcve. You can use package `reprex` to help you: http://reprex.tidyverse.org/. The most popular R stackoverflow question is about the subject: https://stackoverflow.com/questions/5963269/how-to-make-a-great-r-reproducible-example.

- [ ] the results of R command `sessionInfo()`. It had to be executed after you loaded the packages used by your example. This will let me know what is your version of R and what are the versions of the packages you used in your example. 

- [ ] you did checked you had the latest version of the package on CRAN (and on github if issue exists with CRAN version).

- [ ] you searched in the *open* and *closed* issues on the github repository.


### If you are asking an enhancement or a new function

ReporteRs will be maintained but will not evolve anymore. It has been rewritten with no java dependency, see [officer](https://cran.r-project.org/package=officer).

Any suggestions to make the documentation better is appriciated.

### If you are asking a question

Don't, this is not the place where to put questions. If you are looking for help on how to use the package correctly, please visit Stackoverflow and tag your question with `[r]` and `[reporters]`. I usually read them and answer when possible.

