# Super-RL-PSF
Super Repo to contain both RL and PSF

To clone with submodules run: 
```
git clone --recurse-submodules https://github.com/PerLunsj/Super-RL-PSF.git
```

Create env with conda and install conda and pip requirements of submodules (Warning large pip requirements): 
```
cd Super-RL-PSF
conda env create -f environment.yml
```
To work in conda env:
```
conda activate super
```

### Updating to submodules (unstable):
To update to the lastest submodule
```
git submodule update --init --recursive
```

