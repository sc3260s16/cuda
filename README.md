# CUDA Examples

To run these examples you'll need to be logged into a GPU gateway. Type the following while logged into a normal cluster gateway:

	ssh vmps81

You'll be prompted for your password, which is the same password you use to access the cluster.

To build the examples make sure you have a recent version of CUDA loaded into your environment:

	setpkgs -a cuda7.0

## Suggested Order

1. vector-addition
	- CPU-version  
	- Single-block-GPU-version
	- tiled-GPU-version
2. matrix-multiply
	- cpu-version
	- naive
	- tiled	 
	- shared-memory
3. multi-gpu