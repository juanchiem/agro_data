## Serie climatica tandil 
dat <- read.csv("https://raw.githubusercontent.com/juanchiem/agro_data/master/tandil_serie71-20.csv", sep = ",")
dat$date <- as.Date(dat$date, format =  "%Y-%m-%d")

## Recursos web

### Intro 
[R4DS](https://r4ds.had.co.nz/index.html)

### Modelos

[Model Syntax in R](http://conjugateprior.org/2013/01/formulae-in-r-anova/)

[ANOVA: A Short Intro Using R](https://stat.ethz.ch/~meier/teaching/anova/)

[glmmFAQ](https://bbolker.github.io/mixedmodels-misc/glmmFAQ.html)

[A brief introduction to mixed effects modelling and multi-model inference in ecology](https://peerj.com/articles/4794/)

[Data Analysis Examples](https://stats.idre.ucla.edu/other/dae/)

[An R companion to Statistics: data analysis and modelling](https://mspeekenbrink.github.io/sdam-r-companion/index.html)

[Statistics for Ecologists](https://fw8051statistics4ecologists.netlify.app/index.html)  

[R for Statistical Learning](https://daviddalpiaz.github.io/r4sl/linear-models.html)

[K-fold Cross validation](https://www.youtube.com/watch?v=kituDjzXwfE)

https://dzchilds.github.io/stats-for-bio/

### Exp. design

[Analysis and Interpretation of Interactions in Agricultural Research](https://dl.sciencesocieties.org/publications/aj/pdfs/107/2/748)

[Analysis of Combined Experiments Revisited](https://dl.sciencesocieties.org/publications/aj/pdfs/107/2/763)

[Data Analysis and Visualization in R for Ecologists](https://datacarpentry.org/R-ecology-lesson/index.html)

[RNAseq analysis with R](http://monashbioinformaticsplatform.github.io/RNAseq-DE-analysis-with-R/)

[regresion_lineal_multiple](https://www.cienciadedatos.net/documentos/25_regresion_lineal_multiple.html#Introducci%C3%B3n)

[Statistical Design and Analysis of Biological Experiments](https://n.ethz.ch/~kahans/doe2021/)

[guide-to-field-trial-spatial-analysis](https://idahoagstats.github.io/guide-to-field-trial-spatial-analysis/)

Effect size
https://www.youtube.com/watch?v=9LVD9oLg1A0&list=PLM-piyaPQYiZ5UxJMvzGlDrDHSRK2IbP6&index=22
https://www.youtube.com/watch?v=tTgouKMz-eI&list=PLM-piyaPQYiZ5UxJMvzGlDrDHSRK2IbP6&index=21

## Power con R
http://staff.pubhealth.ku.dk/~tag/Teaching/share/R-tutorials/Basic-statistics/Power.html
https://www.rpubs.com/Mareiza/378540 
https://www.statmethods.net/stats/power.html 
https://cran.r-project.org/web/packages/pwr/vignettes/pwr-vignette.html 
https://stats.idre.ucla.edu/r/dae/one-way-anova-power-analysis/
https://rdrr.io/cran/pwr2/man/pwr2-package.html  
https://homepage.divms.uiowa.edu/~rlenth/Power/
https://psfaculty.plantsciences.ucdavis.edu/agr205/Lectures/2010%20Iago/Topic%206/RCBD%20Power%20Analysis.pdf 
[sample_size_r_module](https://med.und.edu/research/daccota/_files/pdfs/berdc_resource_pdfs/sample_size_r_module.pdf)
[sample_size_flax](http://www.unh.edu/halelab/ANFS933/supp_mats/RCBD_Power_Analysis.pdf)


