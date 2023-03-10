Library (caTools)
x=mtcars
Md=na.omit(x)
rv=replace(mtcar$mpg01, is.na(mtcar$mpg01),0)
Im=replace(mtcar$mpg01, is.na(mtcar$mpg01),mean(mtcar$mpg01,na.rm=TRUE))
mtcar$mpg01 = as.factor(mtcar$mpg01)
Boxplot(mtcar$mpg01)
Boxplot.stats(mtcar$mpg01)
