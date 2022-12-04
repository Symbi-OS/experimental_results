# Experiment Details

This experiment focuses on seeing how performance and aggregate throughput of multiple redis-server instances
scales as you run various number of redis instances alongside each other, and what performance looks like in different system configurations.


*Note: All of the data has been normalized to the first iteration of the __controls_off__ case.

# Experimental Setup

- MOC Node neu-3-2 acting as the server and hosting redis-server instances
- MOC Node neu-3-1 acting as the client and driving the experiment
- Kernel             : 5.1.18-300.fc30.x86_64
- Architecture       : x86_64
- Physical CPU cores : 16
- Logical CPU cores  : 32
- CPU Model name     : Intel(R) Xeon(R) CPU E5-2660 0 @ 2.20GHz
- L1d cache          : 32K
- L1i cache          : 32K
- L2 cache           : 256K
- L3 cache           : 20480K
