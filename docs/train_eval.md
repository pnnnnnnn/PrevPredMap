# Prerequisites

**Please ensure you have prepared the environment and the nuScenes dataset.**

# Train and Test

Train PrevPredMap with 4 GPUs 
```
./tools/dist_train.sh ./projects/configs/ppmap/ppmap_nusc_r50_24ep.py 4
```

Eval PrevPredMap with 4 GPUs
```
./tools/dist_test_map.sh ./projects/configs/ppmap/ppmap_nusc_r50_24ep.py ./path/to/ckpts.pth 4
```




# Visualization 

we provide tools for visualization and benchmark under `path/to/PrevPredMap/tools/maptr`