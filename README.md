# Custom Supply Chains
My attempts at making Cartographer supply chains.

## Local Setup

Please install another tool called tappr to create build essential TAP clusters
* tappr repo is https://github.com/atmandhol/tappr

After tappr is installed, run `tappr init` to set it up.

Run the following command to start a tappr kind cluster, install TAP build-essentials profile and create a local registry and connect it
```
./hack/setup.sh
```

To teardown, 
```
./hack/teardown.sh
```
