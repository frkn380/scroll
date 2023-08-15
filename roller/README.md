# Roller

## Build
```shell
make clean && make roller
```

## Start
- Set environment variables
```shell
export CHAIN_ID=534353 # change to correct chain_id
export RUST_MIN_STACK=100000000 
export LD_LIBRARY_PATH=$LD_LIBRARY_PATH:./prover/lib:/usr/local/cuda/   # cuda only for GPU machine
```

- Use config.toml  
```shell
./build/bin/roller
```