# Shiny User Group

[![gitleaks](https://github.com/NEFSC/Shiny-User-Group/actions/workflows/secretScan.yml/badge.svg)](https://github.com/NEFSC/Shiny-User-Group/actions/workflows/secretScan.yml)

A group of NEFSC employees and contractors that meet bi-weekly to discuss topics in R shiny and related tools. For more on how folks at the Center are using shiny check out our [shiny-book](https://nefsc.github.io/NEFSC-shiny-book/). 


## Getting Started

All apps developed by the Shiny Group are located on the **internal** server `shiny1`. Anyone who is inside of the NEFSC firewall (either physically or via VPN) should be able to run any of the apps developed by the Shiny Group. (Login [credentials](#creds) are required to contribute an app or to collaborate with others on the development of an app.) 

Each app developed by a particular user will reside in a unique folder under their account name. The following url format is used to run any app `http://shiny1.nefsc.noaa.gov:3838/username/appname`. The app is physically located at `\\net.nefsc.noaa.gov\shiny1\username\appname` 

## Required Credentials {#creds}

Credentials are required to access the source code of any app.

* An account/permissions to access the `shiny1` server
* If working remotely then a VPN account is also required.

The VPN account is needed (only if working remotely) to run the app and to update/develop an app on the server

Please contact ITD for help in setting up accounts and providing access.

## Saving the app

A Shiny app can be developed:

* locally (and then copied to the server) or
* directly on the server. 

Rstudio is installed on the Shiny (`shiny1`) server to help with live testing of an app. To launch Rstudio in a browser use the following url: `http://shiny1.nefsc.noaa.gov` then log in with credentials.

Save apps to `\\net.nefsc.noaa.gov\shiny1\username\appname`


## Contact (in alphabetical order)

| [kimberly-bastille](https://github.com/kimberly-bastille) | [andybeet](https://github.com/andybeet) | [jmhatch](https://github.com/jmhatch) | [ejosephson](https://github.com/ejosephson) | [alomiller](https://github.com/alomiller) | [atyrell3](https://github.com/atyrell3) |
|---|---|---|---|---|---|
<img src = "https://avatars.githubusercontent.com/u/39955661?s=100&v=4" > | <img src = "https://avatars1.githubusercontent.com/u/22455149?s=100&v=4" > | <img src = "https://avatars.githubusercontent.com/u/35869229?s=100&v=4" width = "100" height = "100" > | <img src = "https://avatars.githubusercontent.com/u/77019097?s=100&v=4"> | <img src = "https://avatars.githubusercontent.com/u/11235095?s=100&v=4" > | <img src = "https://avatars.githubusercontent.com/u/77738923?s=100&v=4" > ||



#### Legal disclaimer

*This repository is a scientific product and is not official
communication of the National Oceanic and Atmospheric Administration, or
the United States Department of Commerce. All NOAA GitHub project code
is provided on an 'as is' basis and the user assumes responsibility for
its use. Any claims against the Department of Commerce or Department of
Commerce bureaus stemming from the use of this GitHub project will be
governed by all applicable Federal law. Any reference to specific
commercial products, processes, or services by service mark, trademark,
manufacturer, or otherwise, does not constitute or imply their
endorsement, recommendation or favoring by the Department of Commerce.
The Department of Commerce seal and logo, or the seal and logo of a DOC
bureau, shall not be used in any manner to imply endorsement of any
commercial product or activity by DOC or the United States Government.*
