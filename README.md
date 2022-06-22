# integer-compression
JS bindings to C++ compression library TurboPFor: Fastest Integer Compression ( https://github.com/powturbo/TurboPFor-Integer-Compression )

## Clone

```sh
git clone git@github.com:torwig/integer-compression.git
git submodule update --init compression
```

## Build

```sh
cd compression
make libic.a
cd ..
npm install
```

## Rebuild
```sh
node-gyp rebuild
```

## Run
```sh
node index.js
```

## NodeJS usage 

```javascipt
npm install node-int-compressor
```
