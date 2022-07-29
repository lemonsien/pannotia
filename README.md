# pannotia
## Get dataset
some graph exceed the size limitation of github. Thus, need to be download elsewhere by datasets/get-data.sh

## Run command
```
./pagerank ../datasets/coAuthorsDBLP.graph 1
./sssp ../datasets/coAuthorsDBLP.graph 1
./mis ../datasets/coAuthorsDBLP.graph 1
./color_max ../datasets/coAuthorsDBLP.graph 1
./bc ../datasets/coAuthorsDBLP.graph 1
```

## modification
* fix makefile and depricated API  bug
* make the input file format of each benchmark consistent
* only run a few iterations in order to get the execution time of the target kernel(irregularity)
