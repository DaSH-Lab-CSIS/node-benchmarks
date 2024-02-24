# List of any and all performance anomalies in Storage-N systems

# Cinebench :
- ## Storage-0:
	- GPU : *6958*
	- CPU-MultiCore *897*
	- CPU-SingleCore *110*
- ## Storage-1:
	- GPU *6935*
	- CPU-MultiCore *918*
	- CPU-SingleCore *111*
- ## Storage-2:
	- GPU *6942*
	- CPU-MultiCore *910*
	- CPU-SingleCore *111*
- ## Storage-3:
	- GPU *6920*
	- CPU-MultiCore *920*
	- CPU-SingleCore *110*
### No significant differences

# Corona
- ## Storage-0 : 5,109,480
- ## Storage-1 : 5,288,234
- ## Storage-2 : 5,296,405
- ## Storage-3 : 5,252,086

### Storage-0 multi-core was slightly worse, but well within margin of error.

# Geekbench

## Storage-0
- ## Single Core : 2577
- ## Multi Core : 15197
- ## GPU-OpenCL : 74102
- ## GPU-Vulkan : 71016
## Storage-1
- ## Single Core : 2591
- ## Multi Core : 15383
- ## GPU-OpenCL : 73667
- ## GPU-Vulkan : 70818
## Storage-2
- ## Single Core : 2576
- ## Multi Core : 15194
- ## GPU-OpenCL : 75250
- ## GPU-Vulkan : 71486
## Storage-3
- ## Single Core : 2594
- ## Multi Core : 15148
- ## GPU-OpenCL : 75911
- ## GPU-Vulkan : 70200

### Storage-0 seems on par here, so everything should be fine. GPUs are in spec as well.

# 3D-Mark :
- ## Storage-0 
	- ## TimeSpy :  6436
	- ## FireStrike : 15127
- ## Storage-1
	- ## TimeSpy : 6369
	- ## FireStrike : 15162
- ## Storage-2
	- ## TimeSpy : 6551
	- ## FireStrike : 15477
- ## Storage-3
	- ## TimeSpy : 6419
	- ## FireStrike : 15124
# Compubench : 

## OpenCL : 
## Everything looks fine

## Cuda :
## Everything looks fine


# CrystalDiskMark : 

- ## SSDs:
	- ## Random Reads show variations (60-90), everything else is consistent
- ## HDDs:
	- ## Similar random reads and writes, but sequential shows around a 5-10% variation. 
	- ## Some drives show results ranging from 205-210 whereas some are in the low 190s.
	- ## Might not be cause for concern but worth investigating further
# S.M.A.R.T :
- ## No increase in negative indicators.

# Overall Results : 

- ## Systems are performing more or less within spec. 
- ## Variation in Hard Drive speed is significant and must be investigated further. 
- ## MultiCore performance differences aren't a big deal.


