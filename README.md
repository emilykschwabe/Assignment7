
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Assignment7

The goal of Assignment7 is to describe a package that I use commonly on
R. Assignmnet7 will give you insight about the package kinship2 which
will create a relatedness maxtrix based off of genetic or family data.

## Package Title

The package this assignment will be exploing is “kinship2”.

## Installation

You can install the released version of Assignment7 from
[CRAN](https://CRAN.R-project.org) with:

``` r
install.packages("kinship2", repos="http://R-Forge.R-project.org")
#or
require(kinship2)
```

And the development version from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("cran/kinship2")
```

## Vignette

A formal vignette has been created for this package has been created by
Jason Sinnwell. To see the vignette please refer to the file
“vignettes”.

## Applications

I was unable to find a website for this package, but I made my own
website for the assignment. There is not a lot of information in the
website, but I successfully made a website\!

## Review

The primary purpose of this package is to analysis genetic or family
relationships to create pedigree trees or kinship matrices. Pedigree
trees are visual representations of inheritance of a trait or disease
through several generations. A kinship matrix gives a probabilistic
estimate that a random gene from a given subject is identical by descent
(ibd) to a gene in the same locus from a subject. More simply put, a
kinship maxtrix tells us the relatedness between individuals.

I like this package becasue it has a very unique purpose. There are no
other packages that can create similar outputs. This package can quickly
run through thousands of individuals and produce a simple matrix of
kinship. The relatedness values that this package determines can then be
used to determine inbreeding rates with the addition of other statistics
too.

I think the matrix function is much easier to use than the pedigree
funcation. I have onlt needed to use the matrix output in my project,
and I dabbled in the pedigree function for fun, but it was really hard
to figure out.

Personally, I did not find this package very easy to use. Since this is
not a widely used package, there are very little tutorials out there.
The function that I ended up using in my analysis was pretty simple, so
I could figure it out, but there is not a lot of additional assistance
on the web.

I would recommend this package to someone if they were specfically
needing to generate large multi generational pedigree trees or
relatedness values between many individuals.
