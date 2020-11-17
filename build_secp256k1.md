#install secp256k1 dep from source

```
$ git clone https://github.com/bitcoin-core/secp256k1.git
$ ./autogen.sh
$ ./configure
$ make
$ make check
$ sudo make install

$ git clone https://github.com/ludbb/secp256k1-py.git
$ LIB_DIR=/lib_to_secp256k1 pip install secp256k1

```

