# ubuntu-setup
My configuration of Ubuntu, for quick (re)use

# Cloning

As this project keeps `i3-gaps`, `nitrogen` and `polybar` as active dependencies (in the `deps` directory), they're here as submodules, so be sure to clone the repo like this:

`git clone --recurse-submodules https://github.com/gavrilovmiroslav/ubuntu-setup`

# Installing

I keep all of my config files in `/$HOME/.config`, so all the config files will reference those locations. The safest (and quickest) way to go is to install all the needed software (either through the submodules here or system installer), and then copy the contents of this repo into `.config` (taking care not to pull the `.git` directory too).

