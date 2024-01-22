# ziglab
This project is a scratch pad for learning [Zig](https://ziglang.org/).

## Install zig

Follow the installation instructions [here](https://ziglang.org/learn/getting-started/#installing-zig).

## Build executable
The variable $DIR is the sub-directory in this project which you wish to build.
For example, executing `export DIR="hello"` would make the hello sub-directory the target of the following commands.

```
cd $DIR
zig build-exe main.zig

```
## Execute
The executable built in the previous step can be executed by running the following command. It assumes that the current working directory is still equal to `$DIR`.

```
# Assuming that $DIR is the current working directory
./main
```