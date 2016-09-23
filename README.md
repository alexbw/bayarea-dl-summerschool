# bayarea-dl-summerschool
Torch notebooks and slides for the Bay Area Deep Learning Summer School

## Installation Instructions

#### Install anaconda if you don't have it (instructions here for OS X)
```
wget http://repo.continuum.io/miniconda/Miniconda-latest-MacOSX-x86_64.sh
sh Miniconda-latest-MacOSX-x86_64.sh -b -p $HOME/anaconda
```

#### Add anaconda to your $PATH
```
export PATH=$HOME/anaconda/bin:$PATH
```

#### Install Lua & Torch
```
conda install lua=5.2 lua-science -c alexbw
# Although, you could install other Lua versions like 2.0 (LuaJIT), 5.1, 5.2 and 5.3
```


#### Clone this repository and start the notebook server
```
git clone https://github.com/alexbw/bayarea-dl-summerschool.git
cd bayarea-dl-summerschool
itorch notebook
# Will open a browser tab, then you can navigate to the notebooks
```

