# Setup
Download the repo, select the branch matching the OS, and execute the `setup` file.

# Supported OS
| OS | Branch name |
| -- | ----------- |
| Debian 12 | debian12 |

# Adding new configurations
1. Install the program and configure as normal
2. Move all configuration files to the 'dotfiles' folder, matching the folder structure as if 'dotfiles' were $HOME
3. From inside the 'dotfiles' folder, run `stow .`
