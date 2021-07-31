# Shiny penguins

Test application for RStudio Connect

Deploying to RStudio Connect through get, using `rsconnect::writeManifest()` 
instructions at [https://docs.rstudio.com/connect/user/git-backed/](https://docs.rstudio.com/connect/user/git-backed/).

+ app.R created in directory "Shiny-Penguins"
+ changed working directory to Shiny-Penguins, `setwd("Shiny-Penguins")`
+ created Shiny-Penguins/manifest.json via `rsconnect::writeManifest()`
+ changed working directory back to project root, `setwd("..")`
+ add, commit, push manifest file up to GitHub