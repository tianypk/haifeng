##读取tsv 文件
read.tsv <- function(file=file, header=TRUE, sep="\t"){ 
    return(read.table(file=file, header=header, sep=sep))}
write.tsv <- function(x,file, quote=FALSE, sep="\t", row.names=FALSE, col.names=TRUE){
    return(write.table(x=x, file=file, quote=quote, sep=sep,
                       row.names = row.names, col.names=col.names))
}


getwd()
setwd("E:\\LTW2\\co-operation with xuling\\TCGA-liver")
a=read.tsv("TCGA-LIHC.survival.tsv")
dim(a)
head(a)
class(a)
