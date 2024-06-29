cellophane.io
=============

elephant.io socket client writen in c



sudo apt install libjson-c-dev

```
cc example_client.c -o cl -L/usr/local/lib -l:cellophane.io.so -ljson-c -lcurl -Wl,-rpath=/usr/local/lib
```
