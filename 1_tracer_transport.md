# 1. Tracer Transport 

* Look at the example in [Molins et al., 2022](https://doi.org/10.1029/2022WR032074)

Molins, Sergi, et al. "A Multicomponent Reactive Transport Model for Integrated Surface‐Subsurface Hydrology Problems." Water Resources Research 58.8 (2022): e2022WR032074. [DOI](https://doi.org/10.1029/2022WR032074)

* Look at ATS Demos

https://github.com/amanzi/ats-demos

* Start the ATS dockerhub image 

`docker pull metsi/ats:master-latest`

`docker run -it -v $(pwd):/home/amanzi_user/work:delegated -w /home/amanzi_user/work metsi/ats:master-latest`

* Pull ats-demos

`git clone https://github.com/amanzi/ats-demos.git`

* Explore the integrated hydrology reactive transport demos

`cd 13_integrated_hydro_reactive_transport`

* Open to edit 1D column infiltration of tracer demo

`open 1d-infiltration-column.xml`

