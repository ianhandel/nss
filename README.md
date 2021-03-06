# nss
- [nss](#nss)
    + [What is `nss` for?](#what-is-nss-for)
    + [Install](#install)
    + [Data Not Included](#in-git-ignore)
    + [License](#license)



## What is nss for?
This package aims to provide [National Student Survey](https://www.officeforstudents.org.uk/advice-and-guidance/student-information-and-data/national-student-survey-nss/) data in a tidy, documented format. 

At present the package provides top-level data from 2017 and 2018 iterations of survey.


### Subject Level Data
As of 2018, the previously used Joint Academic Coding System ( [JACS](https://www.hesa.ac.uk/support/documentation/jacs)) classification of subjects will be replaced by the Higher Education Classification of subjects ( [HECoS](https://www.hesa.ac.uk/innovation/hecos)) codes. In 2018 a third system, the Common Aggregation Hierarchy (or [CAH](https://www.hesa.ac.uk/innovation/hecos)) is being used to bridge the gap between JACS and HECoS. 

**At present I am working on a memory-cheap and future-proof way of joining JACS, CAH and HECoS codes together. Subject level data will follow**


### Pre 2017 Data

The survey changed from 2016-2017 and HEFCE, who owned the data prior to Office for Students, were very concerned that people may compile 2017 and pre-2017 data as there was a significant survey change at that point. 

In the future I would like to combine this with older datasets. 


**Presently working on a memory-cheap and future-proof way of joining JACS, CAH and HECoS codes together**

### A word on naming
Through the gentle guidance of my good colleague ["@ianhandel"](https://github.com/ianhandel) I conceded to naming this package as the lowercase `nss`, and the top level object shares that name. However column headings have capitals because that's easier to read and this is a hill I am prepared to die on. 



## Install
At present, no plans to push this through CRAN so use GitHub.


``` r
devtools::install_github("jillymackay/nss")
```



## In Git Ignore

### data_raw/

+ NSS_taught_all12.xlsx (NB - renamed file from HEFCE download)

+ NSS_taught_all12.xlsx

+ NSS_taught_all_14-new.xlsx

+ NSS_taught_all15.xlsx

+ NSS_taught_all16.xlsx

+ NSS_taught_all17.xlsx

+ NSS_taught_all18.xlsx

+ NSSFullTime1_candidate11.xls (NB-renamed file from HEFCE download)

+ NSSFullTime2_candidate11.xls (NB-renamed file from HEFCE download)

+ NSSFullTime08.xls (NB-renamed file from HEFCE download)

+ NSSFullTime109.xls (NB-renamed file from HEFCE download)

+ NSSFullTime110.xls (NB-renamed file from HEFCE download)

+ NSSFullTime209.xls (NB-renamed file from HEFCE download)

+ NSSFullTime210.xls (NB-renamed file from HEFCE download)

### data_raw/data_LP
**NB: See R/AdditionalData.R**
+ 1994_Group.csv

+ ABSA.csv

+ Cathedrals_Group.csv

+ GW4.csv

+ Million_Plus.csv

+ N8_Research_Partnership.csv

+ NCUK.csv

+ Oxbridge.csv

+ Russell_Group.csv

+ Science_and_Engineering_South.csv

+ University_Alliance.csv

+ White_Rose_University_Consortium.csv

+ HECoS-CAH Version 1.1.xlsx  (From: [https://www.hesa.ac.uk/innovation/hecos](https://www.hesa.ac.uk/innovation/hecos))


License
-------

The National Student Survey data is coordinated by the Office for Students. It is currently (as of 2018) delivered by Ipsos MORI and results made available by Texuna Technologies.
https://www.officeforstudents.org.uk/advice-and-guidance/student-information-and-data/national-student-survey-nss/contacts-and-privacy/

All the data used here is publicly available. 

All this code is CC0

