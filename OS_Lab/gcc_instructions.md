## Verify the installation of GCC
whereis gcc
which gcc
gcc --version

**If GCC is not installed**
sudo apt-get update
sudo apt-get install build-essential manpages-dev

## To open a text editor
gedit filename

**Example**
gedit program.c

## To compile C-Program
gcc -o program program.c

## To execute C-Program
**Navigate to location**
./program