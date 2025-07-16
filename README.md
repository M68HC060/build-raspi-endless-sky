# build-raspi-endless-sky

This is my build-script for building endless-sky on Raspberry Pi (bookworm).
The script ensures that all needed packages are installed before building.

The easiest way to use this script, is to place it in your ~/bin/ directory,
then 'cd' into the cloned endless-sky repository and finally run the script:

cd ~/Sources/endless-sky; build-endless-sky

You can also supply the path as the first argument:

build-endless-sky ~/Sources/endless-sky

