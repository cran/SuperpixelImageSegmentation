
## SuperpixelImageSegmentation
<br>

The R / Rcpp code of the *SuperpixelImageSegmentation* package is based primarily on the article ["Image Segmentation using SLIC Superpixels and Affinity Propagation Clustering", Bao Zhou, International Journal of Science and Research (IJSR), 2013](https://www.ijsr.net/archive/v4i4/SUB152869.pdf).

I wrote a [blog post](http://mlampros.github.io/2018/11/09/Image_Segmentation_Superpixels_Clustering/) explaining how to take advantage of the R / Rcpp code of the *SuperpixelImageSegmentation* package.

<br>

System / Software Requirements:

* [OpenImageR ](https://github.com/mlampros/OpenImageR)
* [ClusterR ](https://github.com/mlampros/ClusterR)
* a C++ 11 compiler
<br><br>


The *SuperpixelImageSegmentation* package can be installed from CRAN using,

<br>


```R

install.packages("SuperpixelImageSegmentation")
 

```
<br>

**or** by using the *install_github* function of the devtools package,
<br><br>

```R

remotes::install_github('mlampros/SuperpixelImageSegmentation')


```
<br>

**or** by directly downloading the .zip file using the **Clone or download** button in the [repository page](https://github.com/mlampros/SuperpixelImageSegmentation), extracting it locally (renaming it to *SuperpixelImageSegmentation* if necessary) and running,

<br>

```R

#--------
# on Unix
#--------

setwd('/your_folder/SuperpixelImageSegmentation/')
Rcpp::compileAttributes(verbose = TRUE)
setwd('/your_folder/')
system("R CMD build SuperpixelImageSegmentation")
system("R CMD INSTALL SuperpixelImageSegmentation_1.0.0.tar.gz")


#-----------
# on Windows
#-----------

setwd('C:/your_folder/SuperpixelImageSegmentation/')
Rcpp::compileAttributes(verbose = TRUE)
setwd('C:/your_folder/')
system("R CMD build SuperpixelImageSegmentation")
system("R CMD INSTALL SuperpixelImageSegmentation_1.0.0.tar.gz")

```


<br>

Use the following link to report bugs/issues,
<br><br>

[https://github.com/mlampros/SuperpixelImageSegmentation/issues](https://github.com/mlampros/SuperpixelImageSegmentation/issues)

<br>

### **Citation:**

If you use the code of this repository in your paper or research please cite both **SuperpixelImageSegmentation** and the **original articles / software** `https://CRAN.R-project.org/package=SuperpixelImageSegmentation`:

<br>

```R
@Manual{,
  title = {{SuperpixelImageSegmentation}: Image Segmentation using
    Superpixels, Affinity Propagation and Kmeans Clustering},
  author = {Lampros Mouselimis},
  year = {2022},
  note = {R package version 1.0.5},
  url =
    {https://CRAN.R-project.org/package=SuperpixelImageSegmentation},
}
```

<br>
