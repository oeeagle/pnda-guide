# Change Log
All notable changes to this project will be documented in this file.

## [0.1.0] 2016-07-01
### First version

## [Pre-release]

### 2016-06-30

* Added package server instructions.
* Updated website to [pnda.io](http://pnda.io).

### 2016-06-29

* Fixed deployment issue. 

### 2016-06-28

* Renamed PaNDA to PNDA.  

### 2016-06-17

* Renamed data exploration [lab](exploration/lab.md) to tutorial.
* Added links to repository. 

### 2016-06-16

* Renamed platform-heat-templates to pnda-heat-templates, platform-dib-elements to pnda-dib-elements. 
* Updated standard PNDA flavor.

### 2016-06-09

* Updated repos.
* Removed links between repos, as they work in the guide but not on the GitHub website.

### 2016-06-08

* [jupyter lab](exploration/lab.md): Added Jupyter lab.
* [platform requirements](provisioning/platform_requirements.md): Updated resource requirements.
* Removed TODO file.

### 2016-06-08

* [downloads](downloads/README.md): Added links to download book.
* [date](README.md): The last updated date is now set automatically.

### 2016-06-07

* [getting started](gettingstarted/README.md): Explained "use the data generation tools to generate test data sets".
* [getting started](gettingstarted/README.md): On last line, better instructions for opening Impala and what to look for.
* [datasets](console/datasets.md): Added keep mode, removed nolimit policy.
* Upated multiple repo README files.
* Updated console screenshots with new design.
* Added placeholders for [consumer](consumer/lab.md) and [exploration](exploration/lab.md) labs.
* [cover](cover.jpg): Added cover.
* [provisioning/heat.md](provisioning/heat.md): Added getting started with Heat document. 
* [jupyter](exploration/jupyter.md): Added page that explains what you can do with a notebook.
* [HBase tutorial](applications/ksh.md): Added lab from DevNet.
* [OpenTSDB tutorial](applications/kso.md): Added lab from DevNet.

### 2016-05-20

* [console](console/README.md): Added better description of console workflow, and detailed screenshots.
* [references](others/README.md): Assembled all external hyperlinks into one page.
* [deployment manager](repos/platform-deployment-manager/README.md): Removed entire section that was already copied to the [applications](applications/README.md) page. Moved design section to the beginning of the chapter.
* [openbmp](producer/openbmp.md): Removed not very "useful links".
* [examples](applications/examples.md): Added links to example repos.
* [opendl](producer/opendl.md): Added link to PNDA integration instructions.
* [example-spark-batch](repos/example-spark-batch/README.md): Added better build instructions.
* [example-spark-streaming](repos/example-spark-streaming/README.md): Added better build instructions.
* [deployment manager](repos/platform-deployment-manager/README.md): Added requirements and building sections.
* [README](README.md): The version number is now updated from the git release version using scripts/version.sh.

### 2016-05-17

* [CHANGELOG.md](CHANGELOG.md): Added this file.
* [TODO.md](TODO.md): Added file.
* [provisioning/heat.md](provisioning/heat.md): Added new document with a link to the Heat wiki.
* [security](security/README.md): Replaced with new blueprint, and removed everything else under security.
* [provisioning/platform_requirements.md](provisioning/platform_requirements.md): Formatted resource requirements into tables.
* [log-aggregation](log-aggregation/README.md): Added file. Added external links.
* [introduction](README.md): Added paragraph for log aggregation. Shortend info for applications and packages.  
* [pnda-dib-elements](repos/pnda-dib-elements/README.md): Updated formatting.
* [metrics](console/metrics.md): Added link to log aggregation page.
* Capitalization: Heat not HEAT, YARN not Yarn.
* Spacing: [80 GB not 80GB](http://www.engadget.com/2010/12/16/32-gb-versus-32gb-almost-everyone-is-writing-it-wrong/).
* [logstash](repos/prod-logstash-codec-avro/README.md): Replaced producer/logstash.md with prod-logstash-codec-avro readme.
* [packages](console/packages.md): Added link to getting started with info on uploading packages.
* [datasets](console/datasets.md): Added link to getting started with info on where datasets come from.
* [pmacct](producer/pmacct.md): Moved after OpenBMP.
* [consumers](consumer/README.md): Removed links to DevNet Learning Labs.
