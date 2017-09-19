```
conda install -c r r-essentials
conda install zlib
conda install jupyter
conda insatll -c r r-xml
conda install -c r r-devtools
```

in a R session ... 

```
source("http://bioconductor.org/biocLite.R")
biocLite("SummarizedExperiment") 
biocLite("mygene")
devtools::install_github('kkdey/maptpx')
devtools::install_github('kkdey/CountClust')
```
