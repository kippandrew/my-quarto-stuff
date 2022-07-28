source("renv/activate.R")

setHook("rstudio.sessionInit", function(...) {
  renv::restore()
})
