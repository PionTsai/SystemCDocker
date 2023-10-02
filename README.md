# SystemCDocker
All-in-one dockerfile for some neccessary libraries.

# Installation

Before you can use Docker to build and run the application, you need to have the following installed on your system: 
[Docker: Installation instructions for Docker](https://docs.docker.com/get-docker/)

## Build Instructions

To build the repository using CMake, follow these steps:

Open a terminal and navigate to the root directory of the repository.
Create a build directory (e.g., build/) for out-of-source builds:
```bash
mkdir build
cd build
```

Generate the build files using CMake:
```bash
cmake ..
```

Build the repository using the generated Makefile:
```bash
make
make test
```
