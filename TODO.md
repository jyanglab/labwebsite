# Changes

## hosted by github with Jekyll and servr

## publication management
```
install.packages("devtools")
devtools::install_github("romainfrancois/bibtex")
devtools::install_github("mwmclean/RefManageR")
```
[manual](https://github.com/mwmclean/RefManageR/blob/master/vignettes/RefManageR.pdf)

## added new tab:
Simply add a new markdown file

## modified head
In `_includes/head.html`
`margin-top:100px;` controls the position of the manu.

## added header backgroud image

## added others
added `_includes/google_analytics.html`


# TODO

add logo

html:
```
<header>
     <div id="company_logo"></div>
</header>
```
css:
```
#company_logo{
width:50px;
height:50px;
background-image:url();
}
```
OR:
```
<!-- Could be div. Could be H1, etc -->
    <h1 class="logo">
      <a href="#" class="logo__link">
        <img src="http://placehold.it/240x80&amp;text=logo.png" alt="nope" class="logo__img">
        <span class="logo__text">[Logo Text]</span>
      </a>
      <span class="logo__byline">Logo Byline</span>
    </h1>
```


Our lab's research interests is to integrate biology understanding, genome sequencing, statistics modeling and machine learning to illuminate the genetic or genomic basis of phenotypic variation and to enhance plant improvement.
Our lab's major research interests include:

1. *A* Advanced biological knowledge.
Yield is the ultimate goal for plant improvement. Stress is the key factor that affect grain yield expression.
We are collaborating with colleagues to automatic measure grain yield and related traits in large scale. And try to understanding the molecular mechanism of stress responses.

2. *G* Genetics Codes.
We identify **trait associated variants (TAVs)** using **QTL mapping**, **Genome-wide Association Study (GWAS)**, **selection scanning**, and **XP-GWAS**;

3. *C* Comparative Genomics.
RNA-seq, DMR, methylation.

4. *T* Tools or computational software/packages.
using HPC, Distributed computation, and machine learning Technologies.
We delivery handy tools, R or python packages to facilitate the large data exploration.
