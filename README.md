SaladCoin is using [CryptoNote](https://cryptonote.org) cryptocurrency protocol.

## SaladCoin

This was made for fun, during Christmas with family. Think of it as a fun hackathon, for a proof of concept, to understand a bit better blockchains, *coins, etc.
LinkedIn: https://www.linkedin.com/feed/update/urn:li:activity:6351008248694403072


This is a working AltCoin.
There is a server working as as seed node with which you can play once you compile your own seed node & wallet, make transactions.


It is using ports:
* 20001 for P2P
* 20002 for RPC.



## Building CryptoNote / SaladCoin

### On *nix

Dependencies: GCC 4.7.3 or later, CMake 2.8.6 or later, and Boost 1.55.

You may download them from:

* http://gcc.gnu.org/
* http://www.cmake.org/
* http://www.boost.org/
* Alternatively, it may be possible to install them using a package manager.

To build, change to a directory where this file is located, and run `make`. The resulting executables can be found in `build/release/src`.

**Advanced options:**

* Parallel build: run `make -j<number of threads>` instead of `make`.
* Debug build: run `make build-debug`.
* Test suite: run `make test-release` to run tests in addition to building. Running `make test-debug` will do the same to the debug version.
* Building with Clang: it may be possible to use Clang instead of GCC, but this may not work everywhere. To build, run `export CC=clang CXX=clang++` before running `make`.

### On Windows
Dependencies: MSVC 2013 or later, CMake 2.8.6 or later, and Boost 1.55. You may download them from:

* http://www.microsoft.com/
* http://www.cmake.org/
* http://www.boost.org/

To build, change to a directory where this file is located, and run theas commands: 
```
mkdir build
cd build
cmake -G "Visual Studio 12 Win64" ..
```

And then do Build.
Good luck!