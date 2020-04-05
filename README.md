# smetweb-platform
Exchange, launch, and rate simulation tasks, data, models, and results

[concept:2017]: https://www.rivm.nl/rivm/kennis-en-kunde/strategisch-programma-rivm/spr-2015-2018/wiskundige-modellering-ziekten/smet-web
[colloquium:2017]: https://prezi.com/jf83tcotit-y/
[poster:2017]: ./doc/20170321-poster-transmissiedag.pdf
[report:2017]: ./doc/20171127-spr-mdm-status-report.pdf
[omf]: https://openmodelingfoundation.org/
[omf-standards]: https://github.com/openmodelingfoundation/standards.git

## Platform Design

TODO: [GitHub + PlantUML integration](https://blog.anoff.io/2018-07-31-diagrams-with-plantuml/)

## Concept

The main idea is to have something of a CI simulation platform available, 
not just to take away the hassle of continuously integrating simulation projects 
(i.e. collect and prepare data, compile and run simulation models, collect and store results),
similar to [Jenkins](https://jenkins.io) or [TeamCity](https://www.jetbrains.com/teamcity/),
but also to enhance the community involved (e.g. sharing of data sources, 
code comments, scenarios, ratings, comments, etc.) 
similar to [Kaggle](www.kaggle.com) and [StackOverflow](www.stackoverflow.com), 
and in a containerized fashion using Docker Compose, such that 
anyone can run any model on their local device, or scale up to remote data centers.

This approach is intended to support education at any level, 
collaboration between professionals and enthusiasts, hackathons and 
other initiatives such as the ones that recently launched in response to the COVID-19 pandemic:

* https://codevid19.com/
* https://coronathon.in/ (India)
* April 18-19: https://www.thecoronavirushackathon.com/
* April 8-15: https://pmoshackingcovid19.hackathon.com/#/event
* ~~April 3-5: https://www.mitcnc.org/events/beat-the-pandemic/~~
* ~~March 26, 29: https://covid-global-hackathon.devpost.com/ (WHO, Facebook, Microsoft, etc.)~~
* ~~March 27-29: https://covidhacks.io/~~
* ~~March 27-29: https://datavant.com/pandemic-response-hackathon/~~
* ~~March 27: https://www.codevscovid19.org/~~
* ~~March 25-26: https://www.cendcoronavirushackathon.com/~~

The Smet Web concept started as an [innovation project for 
Mathematical Disease Modeling][concept:2017] at the RIVM in 2017. 
After being awarded with initial funding in January, the concept was presented 
in February to health and/or modeling specialists at a [modeling colloquium (prezi)][colloquium:2017],
in March to Dutch health organisations (GGDs) at the [27th Transmissiedag (poster)][poster:2017],
and in December to the Strategic Programme of the RIVM board in a [final report (pdf)][report:2017].

### Trusted Model Repositories
Simulation model repositories that adhere to 
[good repository practices](https://www.coretrustseal.org/why-certification/requirements/) and
[software citation principles](https://www.force11.org/software-citation-principles) include:

  * [Astrophysics Source Code Library](https://ascl.net/)
  * [Code Ocean](https://codeocean.com/)
  * [Community Surface Dynamics Modeling System (CSDMS) Model Repository](https://csdms.colorado.edu/wiki/Model_download_portal)
  * [Computational Infrastructure for Geodynamics](https://geodynamics.org/cig/software/)
  * [CoMSES Computational Model Library (CML)](https://www.comses.net/codebases/)
  * [figshare](https://figshare.com/)
  * [HydroShare](https://hydroshare.org/)
  * [Open Science Framework](https://osf.io/)
  * [Zenodo](https://zenodo.org/)
  * etc.

Feel free to share your links here.

### Open Modeling Foundation Standards
The aims of the SmetWeb resemble those of the [Open Modeling Foundation][omf]
(OMF) founded in 2018 by several modeling organisations that cooperate to publish 
several [modeling standards on GitHub][omf-standards].

The OMFs current members include: 
  * the [Agricultural Model Intercomparison and Improvement Project](https://agmip.org/),
  * the [Community Surface Dynamics Modeling System](https://csdms.colorado.edu/wiki/Main_Page),
  * the [International Society for Ecological Modeling](https://www.isemworld.org/),
  * the [CoMSES Network](https://www.comses.net/) (which includes 
  * the [OpenABM Consortium](https://www.openabm.org)),
  * the [Key Laboratory of Virtual Geographic Environment](http://vgekl.njnu.edu.cn/),
  * the [Analysis, Integration, and Modeling of the Earth System (AIMES) Project](https://aimesproject.org/),
  * the [International Environmental Modelling & Software Society](https://www.iemss.org/),
  * the [Earth Science Information Partners](https://www.esipfed.org/),
  * the [OpenMI Association](https://www.openmi.org/), and
  * the [Potsdam Institute for Climate Impact Research](http://www.pik-potsdam.de/). 
