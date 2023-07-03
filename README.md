# PyHEP.dev 2023 preparation

In preparation for the [PyHEP.dev](https://indico.cern.ch/e/PyHEP2023.dev) workshop, let's organize ourselves into groups to determine who we're going to get in touch with and what we're going to work on.

## Instructions

**Step 1:** Look at the [list of topical groups](https://github.com/HSF/PyHEP.dev-workshops/issues?q=is%3Aopen+is%3Aissue+label%3A2023+label%3Atopical-group) and pick the ones you're most interested in. Add a comment to introduce yourself, your background, what you work on, and what you hope to achieve at the workshop.

**Step 2:** As conversations develop, it may seem natural to split a group into more manageable topics or add a new topical group that we didn't think of. Feel free to do that.

**Step 3:** These conversations should lead to kick-off talks. _Everyone_ should [submit an abstract](https://indico.cern.ch/event/1234156/abstracts/) and prepare a PDF presentation for one of the [morning sessions](https://indico.cern.ch/event/1234156/timetable/#20230725.detailed). Include the topical group(s) the talk addresses and estimated time (5, 10, or 15 minutes) in the abstract. (Everyone should give a talk, even if only a 5 minute talk to introduce yourself and what you're interested in.)

**Step 4:** At the workshop, mornings are dedicated to kick-off talks and the afternoonds are free-form. The best way to use this workshop is to gather with the people you interacted with in the topical groups and get something done, whether that's detailed roadmap planning, designing new interfaces between libraries, coding sprints, brainstorming new ideas, getting integrated into a project/onboarding new members, transitioning a project into a new phase based on others' experience, writing documentation or tutorials, etc.

Remember, this is _your_ workshop, your chance to be in the same room with developers of many Python packages in HEP. It will be as useful as you make it!

<br><br><br><br><br>

## Library maintainers who will be present

Do you want to connect with the maintainers of a particular library, but don't know who they are? The following people and the packages they maintain are listed below. If the following is incorrect or incomplete, please help us fix it with a [pull request](https://github.com/HSF/PyHEP.dev-workshops/pulls). Thank you!

- [scikit-build](https://github.com/scikit-build/scikit-build), improved build system generator for CPython C, C++, Cython and Fortran extensions: [@henryiii](https://github.com/henryiii)
- [cookie](https://github.com/scientific-python/cookie), Scientific Python library development guide and cookie-cutter: [@henryiii](https://github.com/henryiii)
- [SkyHookDM](https://github.com/apache/arrow/tree/main/cpp/src/skyhook) ([website](https://sites.google.com/view/skyhookdm/home)), tabular data management in object storage, now part of the Apache Arrow project: [@JayjeetAtGithub](https://github.com/JayjeetAtGithub)
- [ServiceX](https://github.com/ssl-hep/ServiceX) ([website](https://iris-hep.org/projects/servicex.html)), a data delivery service pilot for IRIS-HEP DOMA: Daalen, [@masonproffitt](https://github.com/masonproffitt), [@gordonwatts](https://github.com/gordonwatts)
- [hepfile](https://github.com/mattbellis/hepfile), general file schema defined to handle heterogeneous data but implemented in Python and HDF5: [@mattbellis](https://github.com/mattbellis)
- [Uproot](https://github.com/scikit-hep/uproot5), ROOT I/O in pure Python and NumPy: [@ioanaif](https://github.com/ioanaif), [@Moelf](https://github.com/Moelf), [@jpivarski](https://github.com/jpivarski)
- [pylhe](https://github.com/scikit-hep/pylhe), lightweight Python interface to read Les Houches Event (LHE) files: [@lukasheinrich](https://github.com/lukasheinrich), [@matthewfeickert](https://github.com/matthewfeickert)
- [ATLAS PHYSLITE](https://indico.jlab.org/event/459/contributions/11586), a new reduced common data format in ROOT files for ATLAS: [@nikoladze](https://github.com/nikoladze), [@gordonwatts](https://github.com/gordonwatts)
- [Pythia](https://gitlab.com/Pythia8) ([website](https://pythia.org/)), a program for generating high-energy physics collision events, high energy collisions between electrons, protons, photons, and heavy nuclei: philten
- [fastjet](https://github.com/scikit-hep/fastjet), wrapper for FastJet in the Scikit-HEP ecosystem: [@rkansal47](https://github.com/rkansal47)
- [GNN Tracking](https://github.com/gnn-tracking), charged particle tracking with graph neural networks: [@klieret](https://github.com/klieret)
- [Coffea](https://github.com/CoffeaTeam/coffea), basic tools and wrappers for enabling not-too-alien syntax when running columnar collider HEP analysis: [@lgray](https://github.com/lgray), [@nsmith-](https://github.com/nsmith-)
- [hist](https://github.com/scikit-hep/hist), histogramming for analysis powered by boost-histogram: [@amangoel185](https://github.com/amangoel185), [@henryiii](https://github.com/henryiii)
- [uproot-browser](https://github.com/scikit-hep/uproot-browser), a TUI viewer for ROOT files: [@amangoel185](https://github.com/amangoel185), [@henryiii](https://github.com/henryiii)
- [JetNet](https://github.com/jet-net/JetNet), for developing and reproducing ML + HEP projects: [@rkansal47](https://github.com/rkansal47)
- [Awkward Array](https://github.com/scikit-hep/awkward), manipulate JSON-like data with NumPy-like idioms: [@agoose77](https://github.com/agoose77), [@ianna](https://github.com/ianna), [@jpivarski](https://github.com/jpivarski)
- [Cling](https://github.com/root-project/cling), a C++ interpreter based on LLVM: [@vgvassilev](https://github.com/vgvassilev)
- [cppyy](https://github.com/wlav/cppyy), fully automatic, dynamic Python-C++ bindings by leveraging the Cling C++ interpreter and LLVM: [@sudo-panda](https://github.com/sudo-panda)
- [FCCAnalyses](https://github.com/HEP-FCC/FCCAnalyses), common analysis framework for the Future Circular Collider (FCC): [@kjvbrt](https://github.com/kjvbrt)
- [func_adl](https://github.com/iris-hep/func_adl), constructs hierarchical data queries using SQL-like concepts in Python: [@masonproffitt](https://github.com/masonproffitt), [@gordonwatts](https://github.com/gordonwatts)
- [Common Partial Wave Analysis](https://github.com/ComPWA), makes amplitude analysis accessible through transparent and interactive documentation, modern software development tools, and collaboration-independent frameworks: [@redeboer](https://github.com/redeboer)
- [Rio+](https://www.dropbox.com/sh/ydpg4xj4n817ppk/AACLohbJW2JDkFwlfiF2MlBva?dl=0), a C++ package for amplitude analysis: [@JMolinaHN](https://github.com/JMolinaHN)
- [GooFit](https://github.com/goofit/goofit), a massively-parallel framework for maximum-likelihood fits, implemented in CUDA/OpenMP: [@mdsokoloff](https://github.com/mdsokoloff)
- [zfit](https://github.com/zfit/zfit), model manipulation and fitting library based on TensorFlow and optimised for simple and direct manipulation of probability density functions, with a focus on scalability, parallelisation and user friendly experience: [@jonas-eschle](https://github.com/jonas-eschle)
- [pyhf](https://github.com/scikit-hep/pyhf), pure-Python HistFactory implementation with tensors and autodiff: [@matthewfeickert](https://github.com/matthewfeickert), [@lukasheinrich](https://github.com/lukasheinrich)
- [cabinetry](https://github.com/scikit-hep/cabinetry), for designing and steering profile likelihood fits: [@alexander-held](https://github.com/alexander-held)
- [correctionlib](https://github.com/cms-nanoaod/correctionlib), a generic correction library: [@nsmith-](https://github.com/nsmith-)
- [hepstats](https://github.com/scikit-hep/hepstats), statistical tools and utilities: [@jonas-eschle](https://github.com/jonas-eschle)
- [coffea-casa](https://github.com/CoffeaTeam/coffea-casa), prototype Analysis Facility: [@oshadura](https://github.com/oshadura)
- [Work Queue](https://github.com/cooperative-computing-lab/cctools/tree/master/work_queue) ([website](http://ccl.cse.nd.edu/software/workqueue/)), a framework for building large distributed applications that span thousands of machines drawn from clusters, clouds, and grids: [@btovar](https://github.com/btovar)
- [dask-awkward](https://github.com/dask-contrib/dask-awkward), native Dask collection for Awkward Arrays: [@agoose77](https://github.com/agoose77), [@lgray](https://github.com/lgray)
- [hepdata_lib](https://github.com/HEPData/hepdata_lib), a library for getting your data into HEPData: [@clelange](https://github.com/clelange)
- [Analysis Grand Challenge](https://github.com/iris-hep/analysis-grand-challenge), a project performing performing large scale end-to-end data analysis for HEP use cases: [@oshadura](https://github.com/oshadura), [@alexander-held](https://github.com/alexander-held)

-----------------

The organization of this workshop is modeled on the [Scientific Python Developer Summit](https://github.com/scientific-python/summit-2023), but with the addition of kick-off talks.
