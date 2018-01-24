# Roger Federer: 20 Years – 20 Titles

## Preliminary Remarks

This document illustrates the analysis of the article [20 years, 20 titles on srf.ch](https://www.srf.ch/static/srf-data/data/2018/federer/#/en).

SRF Data attaches great importance to transparent and reproducible data preprocessing and -analysis. SRF Data believes in the principles of open data but also open and reproducible methods. Third parties should be empowered to build on the work of SRF Data and to generate new analyses and applications.

### R-Script & Processed Data

The analysis of the data was conducted in the [R project for statistical computing](https://www.r-project.org/). The RMarkdown script used to generate this document and all the resulting data can be downloaded under this [link](https://srfdata.github.io/2018-01-roger-federer/rscript.zip). Through executing `analysis.Rmd`, the herein described process can be reproduced and this document can be generated. In the course of this, data from the folder `ìnput` will be processed and results will be written into `output`.

**R version 3.4.2** is used. If the code does not work, it is very likely that an older R version is installed. If an error occures it sometimes helps to execute the script several times. Particularly in the case of package installation problems it could be helpful to restart the R session and execute the code over again. If necessary, third party libraries like `libgdal-dev` have to be installed.

### License

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons Lizenzvertrag" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a>
<br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Dataset" property="dct:title" rel="dct:type">2018-01-roger-federer</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/srfdata/2018-01-roger-federer" property="cc:attributionName" rel="cc:attributionURL">SRF Data</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

### Other Projects

All code & data from [SRF Data](https://srf.ch/data) are available under [https://srfdata.github.io](https://srfdata.github.io).

### Exclusion of Liability

The published information has been collated carefully, but no guarantee is offered of its completeness, correctness or up-to-date nature. No liability is accepted for damage or loss incurred from the use of this script or the information drawn from it. This exclusion of liability also applies to third-party content that is accessible via this offer.