# slow5-template

A template repository that demonstrates how slow5lib can be used to develop a new nanopore tool


Compilation and running:

```
git clone --recursive https://github.com/hasindu2008/slow5-template
cd slow5-template
make
./tool test/example.blow5
```

To build the tool to support zstd compressed blow5 files

```
make zstd=1
```

