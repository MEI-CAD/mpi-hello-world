# mpi-hello-world

## Install

Ubuntu:
```bash
sudo apt install openmpi-bin openmpi-common libopenmpi-dev libgtk2.0-dev
```

Mac OSX:
```bash
brew install open-mpi
```

## Quickstart

Compile:
```bash
mpicc hello.c -o hello
```

Run:
```bash
mpirun hello
```