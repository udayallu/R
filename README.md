# R
R Programming code samples

## Sampling the data
```
set.seed(111)
sample=sample.int(n=nrow(data_set),size=floor(.7*nrow(data_set)),replace = F)
sample
```

```
dt = sort(sample(nrow(treedata), nrow(treedata)*.9))
traindata<-treedata[sample,]
testdata<-treedata[-sample,]
```
