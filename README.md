# Claude Code plugins

1) in the /plugin menu, navigate to marketplaces and install git@github.com:maxbalk/maxb-marketplace.git
2) select the plugin to install
3) restart claude code

## Metals

1) Install metals and bloop. [Coursier](https://get-coursier.io/) is recommended to manage these as system packages.
2) run `sbt bloopInstall` if you don't already have the project indexed in a .bloop directory
3) start a session from the project root and claude should now have access to metals


## Terraform-ls

1) make `terraform-ls` available on your path. The official binary is available via homebrew
