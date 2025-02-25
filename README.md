# TREATS
Implementation of the protocol THREATS based on the TFHE library.

version 1.0 -- first release date: 11-07-2021

### Description

THREATS is a novel privacy preserving authentication protocol based on fully homomorphic encryption.
Human authentication is based on biometric matching, implemented in the proof-of-concept using face matching.

This work is presented in the paper *Privacy-Preserving Biometric Matching Using Homomorphic Encryption*, by Pradel and Mitchell, to appear in the 20th IEEE International Conference on Trust, Security and Privacy in Computing and Communications (TrustCom 2021), on 18-20th August 2021 in Shenyang, China.

### Dependencies

This code has been tested on Ubuntu 20.04 and 21.04, 64-bit. 
It is based on the TFHE library, and uses one of the FFT processor TFHE uses.
Please follow the installation instructions on the [TFHE page](https://github.com/tfhe/tfhe) before installing THREATS.

### Installation

To build THREATS, after cloning the repository, enter the following commands:
```
cd threats
mkdir build
cd build
cmake ..
make
```
The executable `Client` is created and can be executed.

### Licence

THREATS is open-source software distributed under the terms of the Apache 2.0 license.
