# Some Tips for Lab (and Project) Work

1. Be sure you carefully go through the HTML result of your Lab before you submit it to ensure that everything looks OK, and that, for instance, the Table of Contents works properly.
2. Use the templates provided by Dr. Love when you can.
3. Do not use `opts_chunk$set` to turn off warnings and messages throughout a Lab document or any other work you submit to us. We need to see those warnings if they exist anywhere, and it is only OK to turn off messages for the R package setup, not the work after that point. Do turn the messages off in your package loading chunk with `#| message: FALSE`.
4. Do not source in files (like R scripts) using directories that we don't have. Use a `data` subdirectory of your R Project directory for this Lab, so you can use `source("data/Love-431.R")` rather than `source("D/DirectoryPathNoOneElseHas/data/Love-431.R").
5. Use the tidyverse to manage data, whenever possible.
6. Do not load in individual packages from the tidyverse that are in the core tidyverse (auto-loaded when you load the tidyverse). The list of core packages is [available here](https://www.tidyverse.org/packages/#core-tidyverse).
7. Load the tidyverse last in your R setup.
8. Hit F7 to use spell-check in RStudio on your Quarto file. It's not perfect, especially with headers, but at least it might help.
9. Do not load in R packages that you do not wind up using.
10. Ensure that the session information is available as a section in the Table of Contents.
11. Use the [version of R that Dr. Love recommends](https://thomaselove.github.io/431-2024/software.html). At the moment, that's R version 4.4.1.
12. [Update your R packages](https://thomaselove.github.io/431-2024/software.html#updating-your-r-packages).
