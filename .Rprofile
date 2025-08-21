# Install required packages if not available
if (!requireNamespace("rstudioapi", quietly = TRUE)) {
  install.packages("rstudioapi")
}
if (!requireNamespace("usethis", quietly = TRUE)) {
  install.packages("usethis")
}

# Configure RStudio to use native pipe
rstudioapi::writeRStudioPreference("insert_native_pipe_operator", TRUE)

# Configure blank slate
usethis::use_blank_slate()