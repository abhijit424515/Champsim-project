# Cache Hierarchy and Optimization for Graph Analytics
## Instructions to run

In the `src` directory, additional files (i.e. `excl.cc.cache`, `incl.cc.cache`, `nine.cc.cache`) can be observed, which are the implementations for the **3 inclusive policies**:
1. Exclusion policy
1. Inclusion policy
1. Non-Inclusion policy

Currently, `cache.cc` is identical to `nine.cc.cache`. 
However, for testing purposes, you need to rename the file for the respective inclusive policy to `cache.cc` and then run the Champsim simulator.

After that, run the following commands

```bash
./build_champsim.sh [branch_pred] [l1i_pref] [l1d_pref] [l2c_pref] [llc_pref] [llc_repl] [num_core]
```

```bash
./run_champsim.sh [BINARY] [N_WARM] [N_SIM] [TRACE] [OPTION]
```