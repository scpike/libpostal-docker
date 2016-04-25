libpostal (https://github.com/openvenues/libpostal) is a C library for
parsing and normalizing street addresses. Using libpostal requires
compiling a C program that downloads ~2GB of training data. This (very
simple) Dockerfile automates that compilation and creates a container
with libpostal compiled and ready to use.