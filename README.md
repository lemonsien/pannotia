# pannotia
## Get dataset
Some graph exceed the size limitation of github. Thus, need to be download elsewhere by datasets/get-data.sh

## Run command
```
./pagerank ../datasets/coAuthorsDBLP.graph 1
./sssp ../datasets/coAuthorsDBLP.graph 1
./mis ../datasets/coAuthorsDBLP.graph 1
./color_max ../datasets/coAuthorsDBLP.graph 1
./bc ../datasets/coAuthorsDBLP.graph 1
```

## Modification
* Fix makefile and depricated API  bug
* Make the input file format of each benchmark consistent
* Only run a few iterations in order to get the execution time of the target kernel(irregularity)

## Acknowledgement
Original code is from [gpgpu-sim benchmark](https://github.com/gpgpu-sim/gpgpu-sim_simulations/tree/master/benchmarks/src/cuda/pannotia)
