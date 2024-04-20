Clustering of mtcars dataset

dat=mtcars
pmatrix=scale(dat)
d=dist(pmatrix)
c=hclust(d,method="ward.D2")
plot(c)
rect.hclust(c,k=5)

Mitrogdimi/Mitrogdimi is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
