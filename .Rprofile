cat("Set up hugo variables\n")
Sys.setenv(HUGO_ENV="production")
options(
  blogdown.method = "markdown",
  todor_extra = c("toml", "yaml"),
  todor_patterns = c("TODO")
)
if(interactive()){
  cat("Launching website with Hugo\n")
  blogdown::serve_site()
  cat("Done\n")
}

