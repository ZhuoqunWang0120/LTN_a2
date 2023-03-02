
## Parameters
notu, J, nj, ntop, signal, seed, H

## Collect results
For nOTU = 50, 75, run
```
# remember to change the notu and parameter ranges in each file
/work/zw122/LTN_analysis1/src/simulation/cross_group_comparison/collect_teststat_notu.sh 
/work/zw122/LTN_analysis1/src/simulation/cross_group_comparison/run_roc_ltn_notu.R # collect ROC of LTN
/work/zw122/LTN_analysis1/src/simulation/cross_group_comparison/run_roc_dirfactor_notu.R
/work/zw122/LTN_analysis1/src/simulation/cross_group_comparison/run_roc_maaslin_notu.R
/work/zw122/LTN_analysis1/src/simulation/cross_group_comparison/combine_roc_notu.R 
```




