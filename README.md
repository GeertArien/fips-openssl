# fips-openssl

Static pre-compiled [openssl](https://www.openssl.org/) libraries for fips build system. 

### Pre-combiled library

libcurlssl.a has been created like this:

1. git clone https://github.com/openssl/openssl.git
2. cd openssl
3. ./config no-shared
5. make
6. the resulting libs are libcrypto.a and libssl.a

### Dependencies

Requires linking with __libdl__.
