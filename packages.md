---
layout: page
title: R packages
---

## Packages I wrote and maintain

For each package the first link refers to the Github repository.

### Packages submitted to [rOpenSci](http://ropensci.org/)

Note: getting your package reviewed at rOpenSci is the best thing that can happen to your package! I am now a co-editor at rOpenSci package onboarding. If you too want to contribute packages to the project, or to become a reviewer, see the [onboarding repo](https://github.com/ropensci/onboarding/).

* [`ropenaq`](https://github.com/ropenscilabs/ropenaq) is an interface to [OpenAQ API](https://openaq.org/) which is a platform of open air quality data. [Software review](https://github.com/ropensci/onboarding/issues/24) by [Andrew MacDonald](https://github.com/aammd) and [Andy Teucher](https://github.com/ateucher). The package is [on CRAN](https://CRAN.R-project.org/package=ropenaq).

* [`opencage`](https://github.com/ropenscilabs/opencage) is an interface to [opencage API](https://geocoder.opencagedata.com/) which offers forward and reverse geocoding. [Software review](https://github.com/ropensci/onboarding/issues/36) by [Julia Silge](https://github.com/juliasilge). The package is [on CRAN](https://CRAN.R-project.org/package=opencage).

* [`riem`](https://github.com/ropenscilabs/riem) allows to get METAR reports (weather reports) through the [Iowa Environment Mesonet](https://mesonet.agron.iastate.edu/request/download.phtml?network=IN__ASOS). [Software review](https://github.com/ropensci/onboarding/issues/39) by [Brooke Anderson](https://github.com/geanders). The package is [on CRAN](https://CRAN.R-project.org/package=riem).

* [`geoparser`](https://github.com/ropenscilabs/geoparser) is an interface to [geoparser API](https://geoparser.io) which offers geoparsing: finding locations in text. [Software review](https://github.com/ropensci/onboarding/issues/43) by [Bob Rudis](https://github.com/hrbrmstr). The package is [on CRAN](https://CRAN.R-project.org/package=geoparser).

* [`monkeylearn`](https://github.com/ropenscilabs/geoparser) is an interface to [monkeylearn API](http://monkeylearn.com/) which offers machine learning modules for text analysis. [Software review](https://github.com/ropensci/onboarding/issues/45) by [Thomas Leeper](https://github.com/leeper). The package is [on CRAN](https://CRAN.R-project.org/package=monkeylearn).

### Public packages written [for CHAI project](http://www.chaiproject.org/)

I made my work a bit easier with those packages.

* [`rtimicropem`](https://github.com/masalmon/rtimicropem) which reads RTI MicroPEM output files and supports their analysis in R.

* [`watchme`](https://github.com/masalmon/watchme) where I store a bunch of functions for analysing codes given to autographer pictures.

* [`convertagd`](https://github.com/maelle/convertagd) in which I packaged the code of a colleague's for converting .agd files from Actigraph (accelerometers).

* [`eml.tools`](https://github.com/maelle/eml.tools) currently only has one function helping the translation of factors when the data has EML (Ecological Metadata Language) metadata.



## Packages I contribute(d) to

* [`surveillance`](https://cran.r-project.org/web/packages/surveillance/) which offers many tools for statistical methods for the modeling and monitoring of time series of counts, proportions and categorical data, as well as for the modeling of continuous-time point processes of epidemic phenomena. I contributed to the monitoring part of the package mainly by adding several algorithms (functions `farringtonFlexible`, `earsC`, `bodaDelay`) and by writing an article about those functionalities of the package [in the Journal of Statistical Software](https://www.jstatsoft.org/article/view/v070i10) together with [Dirk Schumacher](https://www.dirk-schumacher.net/) and my PhD advisor [Michael Höhle](http://staff.math.su.se/hoehle/).

* [`EML`](https://github.com/ropensci/eml), an Ecological Metadata Language interface for R that I used at work and to which I started contributing a bit after noticing I could not write my first name in the metadata due to a small encoding issue. 

* [`overpass`](https://github.com/hrbrmstr/overpass) and [`osmdata`](https://github.com/osmdatar/osmdata) both provide acess to Openstreetmap Overpass API data. I got interested in it for [a side-project at work](https://github.com/maelle/cycle_infrastructure_modeshare).

## Packages I reviewed for rOpenSci

* [David Robinson](https://github.com/dgrtwo)'s [gutenbergr](https://github.com/ropenscilabs/gutenbergr) which  offers tools to download and process public domain works in the Project Gutenberg collection. See my review [here](https://github.com/ropensci/onboarding/issues/41).

* [Claudia Vitolo](https://github.com/cvitolo)'s [rdefra](https://github.com/ropenscilabs/rdefra) which  retrieves air pollution data and metadata from the Air Information Resource (UK-AIR) of the Department for Environment, Food and Rural Affairs in the United Kingdom. See my review [here](https://github.com/ropensci/onboarding/issues/68).