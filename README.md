# Welcome! 
This doc is intended to orient you to the WOAQ-WOEIP partnership and get you up and running as a contributor, if you so choose (we hope you choose).

### Who we are
West Oakland Air Quality (WOAQ) is a project of [OpenOakland](http://openoakland.org/), a nonprofit Code for America brigade bridging technology and community for a thriving and equitable Oakland.

West Oakland Environmental Indicators Project ([WOEIP](http://www.woeip.org/)) is an environmental justice nonprofit using collaborative, community-based participatory research to empower local residents so they can achieve their own vision for healthy neighborhoods.


## Overview
WOAQ is developing a user-friendly database that allows WOEIP to manage the local air quality (AQ) data they've been collecting for years, visualize that data in meaningful ways, and use this to empower local residents to drive change in their community.

### Process
* Understand the practical problems we're trying to solve through primary, secondary, and user research (current user group: staff and volunteers of WOEIP; in the future: possibly local residents, environmental advocates, and academic researchers).
* Translate research insights into [product requirements](https://www.lucidchart.com/invitations/accept/1fad5bab-1293-43a8-b28d-fa6e7782660a).
* Translate product requirements into [Trello cards](https://trello.com/invite/b/EBnxZHmx/6e43b909891f622463a67da64dbb8101/west-oakland-air-quality) and GitHub issues in this repo.
* Build.
* Test.
* Improve.

## Tech structure
We're currently trying to consolidate the following code into this single repo for the sake of efficiency.
* Data upload tool (a flask app hosted on Heroku) [repo](https://github.com/Ethan-bradley/WoaqUploadAppCode) and [user interface](https://whispering-refuge-49854.herokuapp.com/)
* Data Visualization tool: [repo](https://github.com/openoakland/woaq/) and [user interface](https://openoakland.github.io/woaq/).

## About the data
*Initial data set:*
* WOEIP collects air quality data with a DusTrak II mobile sensor and a coordinated GPS device. These produce two files per collection session, which need to be associated with each other. The DusTrak produces a CSV file, and the GPS device produces a log file.
* For current state of this data, see the [associated Trello card](https://trello.com/c/l1NxFPFT).
* Some of the CSV and log files have been compiled into the data visualization tool referenced above under "Tech structure." Additional third-party (non-WOEIP) data sets have been compiled into that tool, as well. All of the compiled data needs to be re-evaluated, as we don't have a clear understanding of how it was originally processed (it's possible details are in the source repo linked under "Tech structure" above).

## Contributing
* We currently use the [WOAQ Trello board](https://trello.com/invite/b/EBnxZHmx/6e43b909891f622463a67da64dbb8101/west-oakland-air-quality) for general project management. See the [Instructions](https://trello.com/c/msbASe3F) in Trello for how to get started on tasks listed there.


## Still TBD:
* Distinguish between contributing to the code or to the real-world application
* Those wishing to contribute to the code will link to the [contributing.md](https://github.com/openoakland/woeip/blob/master/.gitignore/contributing.md)
* Those wishing to contribute to the real-world application will link to whereever the team sees best.
