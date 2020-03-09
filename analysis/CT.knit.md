---
title: "CT"
author: "Jens Daniel Müller & Lara Burchardt"
date:  "09 March, 2020"
output: 
  workflowr::wflow_html:
    number_sections: true
    toc_depth: 3
    toc_float:
      collapsed: false
editor_options:
  chunk_output_type: console
---

<p>
<button type="button" class="btn btn-default btn-workflowr btn-workflowr-report"
  data-toggle="collapse" data-target="#workflowr-report">
  <span class="glyphicon glyphicon-list" aria-hidden="true"></span>
  workflowr
  <span class="glyphicon glyphicon-ok text-success" aria-hidden="true"></span>
</button>
</p>

<div id="workflowr-report" class="collapse">
<ul class="nav nav-tabs">
  <li class="active"><a data-toggle="tab" href="#summary">Summary</a></li>
  <li><a data-toggle="tab" href="#checks">
  Checks <span class="glyphicon glyphicon-ok text-success" aria-hidden="true"></span>
  </a></li>
  <li><a data-toggle="tab" href="#versions">Past versions</a></li>
</ul>

<div class="tab-content">
<div id="summary" class="tab-pane fade in active">
  <p><strong>Last updated:</strong> 2020-03-09</p>
  <p><strong>Checks:</strong>
  <span class="glyphicon glyphicon-ok text-success" aria-hidden="true"></span>
  7
  <span class="glyphicon glyphicon-exclamation-sign text-danger" aria-hidden="true"></span>
  0
  </p>
  <p><strong>Knit directory:</strong>
  <code>Baltic_Productivity/</code>
  <span class="glyphicon glyphicon-question-sign" aria-hidden="true"
  title="This is the local directory in which the code in this file was executed.">
  </span>
  </p>
  <p>
  This reproducible <a href="http://rmarkdown.rstudio.com">R Markdown</a>
  analysis was created with <a
  href="https://github.com/jdblischak/workflowr">workflowr</a> (version
  1.6.0). The <em>Checks</em> tab describes the
  reproducibility checks that were applied when the results were created.
  The <em>Past versions</em> tab lists the development history.
  </p>
<hr>
</div>
<div id="checks" class="tab-pane fade">
  <div class="panel-group" id="workflowr-checks">
  <div class="panel panel-default">
<div class="panel-heading">
<p class="panel-title">
<a data-toggle="collapse" data-parent="#workflowr-checks" href="#strongRMarkdownfilestronguptodate">
  <span class="glyphicon glyphicon-ok text-success" aria-hidden="true"></span>
  <strong>R Markdown file:</strong> up-to-date
</a>
</p>
</div>
<div id="strongRMarkdownfilestronguptodate" class="panel-collapse collapse">
<div class="panel-body">
  
Great! Since the R Markdown file has been committed to the Git repository, you
know the exact version of the code that produced these results.

</div>
</div>
</div>
<div class="panel panel-default">
<div class="panel-heading">
<p class="panel-title">
<a data-toggle="collapse" data-parent="#workflowr-checks" href="#strongEnvironmentstrongempty">
  <span class="glyphicon glyphicon-ok text-success" aria-hidden="true"></span>
  <strong>Environment:</strong> empty
</a>
</p>
</div>
<div id="strongEnvironmentstrongempty" class="panel-collapse collapse">
<div class="panel-body">
  
Great job! The global environment was empty. Objects defined in the global
environment can affect the analysis in your R Markdown file in unknown ways.
For reproduciblity it's best to always run the code in an empty environment.

</div>
</div>
</div>
<div class="panel panel-default">
<div class="panel-heading">
<p class="panel-title">
<a data-toggle="collapse" data-parent="#workflowr-checks" href="#strongSeedstrongcodesetseed20191017code">
  <span class="glyphicon glyphicon-ok text-success" aria-hidden="true"></span>
  <strong>Seed:</strong> <code>set.seed(20191017)</code>
</a>
</p>
</div>
<div id="strongSeedstrongcodesetseed20191017code" class="panel-collapse collapse">
<div class="panel-body">
  
The command <code>set.seed(20191017)</code> was run prior to running the code in the R Markdown file.
Setting a seed ensures that any results that rely on randomness, e.g.
subsampling or permutations, are reproducible.

</div>
</div>
</div>
<div class="panel panel-default">
<div class="panel-heading">
<p class="panel-title">
<a data-toggle="collapse" data-parent="#workflowr-checks" href="#strongSessioninformationstrongrecorded">
  <span class="glyphicon glyphicon-ok text-success" aria-hidden="true"></span>
  <strong>Session information:</strong> recorded
</a>
</p>
</div>
<div id="strongSessioninformationstrongrecorded" class="panel-collapse collapse">
<div class="panel-body">
  
Great job! Recording the operating system, R version, and package versions is
critical for reproducibility.

</div>
</div>
</div>
<div class="panel panel-default">
<div class="panel-heading">
<p class="panel-title">
<a data-toggle="collapse" data-parent="#workflowr-checks" href="#strongCachestrongnone">
  <span class="glyphicon glyphicon-ok text-success" aria-hidden="true"></span>
  <strong>Cache:</strong> none
</a>
</p>
</div>
<div id="strongCachestrongnone" class="panel-collapse collapse">
<div class="panel-body">
  
Nice! There were no cached chunks for this analysis, so you can be confident
that you successfully produced the results during this run.

</div>
</div>
</div>
<div class="panel panel-default">
<div class="panel-heading">
<p class="panel-title">
<a data-toggle="collapse" data-parent="#workflowr-checks" href="#strongFilepathsstrongrelative">
  <span class="glyphicon glyphicon-ok text-success" aria-hidden="true"></span>
  <strong>File paths:</strong> relative
</a>
</p>
</div>
<div id="strongFilepathsstrongrelative" class="panel-collapse collapse">
<div class="panel-body">
  
Great job! Using relative paths to the files within your workflowr project
makes it easier to run your code on other machines.

</div>
</div>
</div>
<div class="panel panel-default">
<div class="panel-heading">
<p class="panel-title">
<a data-toggle="collapse" data-parent="#workflowr-checks" href="#strongRepositoryversionstrongahrefhttpsgithubcomjensdanielmuellerBalticProductivitytree39c44ac89b3f4a0928498ce26b2948b2f9a88334targetblank39c44aca">
  <span class="glyphicon glyphicon-ok text-success" aria-hidden="true"></span>
  <strong>Repository version:</strong> <a href="https://github.com/jens-daniel-mueller/Baltic_Productivity/tree/39c44ac89b3f4a0928498ce26b2948b2f9a88334" target="_blank">39c44ac</a>
</a>
</p>
</div>
<div id="strongRepositoryversionstrongahrefhttpsgithubcomjensdanielmuellerBalticProductivitytree39c44ac89b3f4a0928498ce26b2948b2f9a88334targetblank39c44aca" class="panel-collapse collapse">
<div class="panel-body">
  
 
<p>
Great! You are using Git for version control. Tracking code development and
connecting the code version to the results is critical for reproducibility.
The version displayed above was the version of the Git repository at the time
these results were generated.
<br><br>
Note that you need to be careful to ensure that all relevant files for the
analysis have been committed to Git prior to generating the results (you can
use <code>wflow_publish</code> or <code>wflow_git_commit</code>). workflowr only
checks the R Markdown file, but you know if there are other scripts or data
files that it depends on. Below is the status of the Git repository when the
results were generated:
</p>
 <pre><code>
Ignored files:
	Ignored:    .Rhistory
	Ignored:    .Rproj.user/
	Ignored:    data/ARGO/
	Ignored:    data/Finnmaid/
	Ignored:    data/GETM/
	Ignored:    data/OSTIA/
	Ignored:    data/_merged_data_files/
	Ignored:    data/_summarized_data_files/

Untracked files:
	Untracked:  code/Finnmaid-GETM.Rmd

Unstaged changes:
	Deleted:    analysis/Finnmaid-GETM.Rmd

</code></pre> <p>
Note that any generated files, e.g. HTML, png, CSS, etc., are not included in
this status report because it is ok for generated content to have uncommitted
changes.
</p>

</div>
</div>
</div>
</div>
<hr>
</div>
<div id="versions" class="tab-pane fade">
  <p>There are no past versions. Publish this analysis with
      <code>wflow_publish()</code> to start tracking its development.</p>
<hr>
</div>
</div>
</div>










```r
library(tidyverse)
library(ncdf4)
library(vroom) #'rlang' needs to be installed
library(lubridate)
library(geosphere)
library(dygraphs)
library(xts)
library(here)
library(metR)
```


```r
# route
select_route <- "E"

# variable names in 2d and 3d GETM files
var <- "SSS_east"

# latitude limits
low_lat <- 57.5
high_lat <- 58.5
```

# CT 

Here we calculate the mean salinity across all measurments made between march - september in the NGS subregion. 


```r
filesList_2d <- list.files(path= "data", pattern = "Finnmaid.E.2d", recursive = TRUE)
```


```r
nc <- nc_open(paste("data/Finnmaid/", "FM_all_2019_on_standard_tracks.nc", sep = ""))

# read required vectors from netcdf file
route <- ncvar_get(nc, "route")
route <- unlist(strsplit(route, ""))
date_time <- ncvar_get(nc, "time")
latitude_east <- ncvar_get(nc, "latitude_east")

array <- ncvar_get(nc, var) # store the data in a 2-dimensional array
#dim(array) # should have 2 dimensions: 544 coordinate, 2089 time steps
  
  fillvalue <- ncatt_get(nc, var, "_FillValue")
  array[array == fillvalue$value] <- NA
  rm(fillvalue)
  
  #i <- 5
  for (i in seq(1,length(route),1)){
  
      
    if(route[i] == select_route) {
      slice <- array[i,]
      
      value <- mean(slice[latitude_east > low_lat & latitude_east < high_lat], na.rm = TRUE)
      sd    <- sd(slice[latitude_east > low_lat & latitude_east < high_lat], na.rm = TRUE)
      date <- ymd("2000-01-01") + date_time[i]
      
      temp <- bind_cols(date = date, var=var, value = value, sd = sd)
      
      if (exists("timeseries", inherits = FALSE)){
        timeseries <- bind_rows(timeseries, temp)
      } else{timeseries <- temp}
      
      rm(temp, value, date, sd)
      
    } 
  }
nc_close(nc)

fm_sss__ngs <- timeseries %>% 
  mutate(sss = value,
         year = year(date),
         month = month(date))

fm_sss_ngs_monthlymean <- fm_sss__ngs %>% 
  filter(month >=3 , month <=9) %>% 
  summarise(sss_mean = mean(sss, na.rm = TRUE))
```

The mean salinity between March and September for the NGS subregion for all years is 6.7291982.

<br>
<p>
<button type="button" class="btn btn-default btn-workflowr btn-workflowr-sessioninfo"
  data-toggle="collapse" data-target="#workflowr-sessioninfo"
  style = "display: block;">
  <span class="glyphicon glyphicon-wrench" aria-hidden="true"></span>
  Session information
</button>
</p>

<div id="workflowr-sessioninfo" class="collapse">

```r
sessionInfo()
```

```
R version 3.5.0 (2018-04-23)
Platform: x86_64-w64-mingw32/x64 (64-bit)
Running under: Windows 10 x64 (build 18363)

Matrix products: default

locale:
[1] LC_COLLATE=English_United States.1252 
[2] LC_CTYPE=English_United States.1252   
[3] LC_MONETARY=English_United States.1252
[4] LC_NUMERIC=C                          
[5] LC_TIME=English_United States.1252    

attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods   base     

other attached packages:
 [1] metR_0.5.0       here_0.1         xts_0.11-2       zoo_1.8-6       
 [5] dygraphs_1.1.1.6 geosphere_1.5-10 lubridate_1.7.4  vroom_1.2.0     
 [9] ncdf4_1.17       forcats_0.4.0    stringr_1.4.0    dplyr_0.8.3     
[13] purrr_0.3.3      readr_1.3.1      tidyr_1.0.0      tibble_2.1.3    
[17] ggplot2_3.3.0    tidyverse_1.3.0 

loaded via a namespace (and not attached):
 [1] nlme_3.1-137         bitops_1.0-6         fs_1.3.1            
 [4] bit64_0.9-7          httr_1.4.1           rprojroot_1.3-2     
 [7] tools_3.5.0          backports_1.1.5      utf8_1.1.4          
[10] R6_2.4.0             DBI_1.0.0            colorspace_1.4-1    
[13] withr_2.1.2          sp_1.3-2             tidyselect_0.2.5    
[16] gridExtra_2.3        bit_1.1-14           compiler_3.5.0      
[19] git2r_0.26.1         cli_1.1.0            rvest_0.3.5         
[22] xml2_1.2.2           scales_1.0.0         checkmate_1.9.4     
[25] digest_0.6.22        foreign_0.8-70       rmarkdown_2.0       
[28] pkgconfig_2.0.3      htmltools_0.4.0      dbplyr_1.4.2        
[31] maps_3.3.0           htmlwidgets_1.5.1    rlang_0.4.5         
[34] readxl_1.3.1         rstudioapi_0.10      generics_0.0.2      
[37] jsonlite_1.6         RCurl_1.95-4.12      magrittr_1.5        
[40] Formula_1.2-3        dotCall64_1.0-0      Matrix_1.2-14       
[43] fansi_0.4.0          Rcpp_1.0.2           munsell_0.5.0       
[46] lifecycle_0.1.0      stringi_1.4.3        yaml_2.2.0          
[49] plyr_1.8.4           grid_3.5.0           maptools_0.9-8      
[52] formula.tools_1.7.1  promises_1.1.0       crayon_1.3.4        
[55] lattice_0.20-35      haven_2.2.0          hms_0.5.2           
[58] zeallot_0.1.0        knitr_1.26           pillar_1.4.2        
[61] reprex_0.3.0         glue_1.3.1           evaluate_0.14       
[64] data.table_1.12.6    modelr_0.1.5         operator.tools_1.6.3
[67] vctrs_0.2.0          spam_2.3-0.2         httpuv_1.5.2        
[70] cellranger_1.1.0     gtable_0.3.0         assertthat_0.2.1    
[73] xfun_0.10            broom_0.5.3          later_1.0.0         
[76] memoise_1.1.0        fields_9.9           workflowr_1.6.0     
```
</div>
