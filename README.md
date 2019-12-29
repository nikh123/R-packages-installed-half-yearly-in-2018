# Introduction

In this assignement we are 



```
# R-packages-installed-half-yearly-in-2018

# Install jsonlite

library(jsonlite)

# Gather data on R packages installed in first half of 2018

Packages_installed_in_firsthalf_2018=jsonlite::fromJSON("https://cranlogs.r-pkg.org/downloads/total/2018-01-01:2018-06-30")

# Convert the data in csv file

write.csv(Packages_installed_in_firsthalf_2018,"/Users/nikhil/Desktop/codein/Packages_installed_in_fisthalf_2018.csv")

# Gather data on R packages installed in second half of 2018

Packages_installed_in_secondhalf_2018=jsonlite::fromJSON("https://cranlogs.r-pkg.org/downloads/total/2018-07-01:2018-12-31")

# Conert the data in csv file

write.csv(Packages_installed_in_secondhalf_2018,"/Users/nikhil/Desktop/codein/Packages_installed_in_secondhalf_2018.csv")
```
