# Set your email and name for Git
email <- "econ.mtlin@gmail.com"
name <- "econmtlin"

# Run the git config commands
system(paste('git config --global user.email', shQuote(email)))
system(paste('git config --global user.name', shQuote(name)))

# Alternatively, you can use system2
system2("git", args = c("config", "--global", "user.email", email))
system2("git", args = c("config", "--global", "user.name", name))
