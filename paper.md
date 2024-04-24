---
title: 'HeuDiConv — flexible DICOM conversion into structured directory layouts'
tags:
  - Python
  - neuroscience
  - standardization
  - DICOM
  - BIDS
  - open science
  - FOSS
authors:
 - name: Yaroslav O. Halchenko  # 626 commits, issues: opened 81 participated in 146
   orcid: 0000-0003-3456-2493
   affiliation: 1
 - name: Mathias Goncalves  # 287 commits, issues: opened 16 participated in 98
   orcid: 0000-0002-7252-7771
   affiliation: 2
 - name: Satrajit Ghosh  # 77 commits, issues: opened 16 participated in 62
   orcid: 0000-0002-5312-6729
   affiliation: 3
 - name: Pablo Velasco  # 113 commits, issues: opened 6 participated in 22
   orcid: 0000-0002-5749-6049
   affiliation: 4
 - name: Matteo Visconti di Oleggio Castello  # 88 commits, issues: opened 2 participated in 1
   orcid: 0000-0001-7931-5272
   affiliation: 5
 - name: Taylor Salo  # 76 commits, issues: opened 11 participated in 4
   orcid: 0000-0001-9813-3167
   affiliation: 6
 - name: John T. Wodder II  # 58 commits, issues: opened 2 participated in 4
   orcid: 
   affiliation: 1
 - name: Michael Hanke  # 32 commits, issues: opened 10 participated in 6
   orcid: 0000-0001-6398-6370
   affiliation: 7, 8
 - name: Patrick Sadil  # 18 commits, issues: opened 3 participated in 2
   orcid: 0000-0003-4141-1343
   affiliation: 22
 - name: Krzysztof Jacek Gorgolewski  # 4 commits, issues: opened 7 participated in 10
   orcid: 0000-0003-3321-7583
   affiliation: 24
 - name: Horea-Ioan Ioanas   # 17 commits, issues: opened 1 participated in 1
   orcid: 0000-0001-7037-2449
   affiliation: 1
 - name: Chris Rorden  # 0 commits, issues: opened 1 participated in 17
   orcid: 0000-0002-7554-6142
   affiliation: 9
 - name: Timothy J. Hendrickson  # 0 commits, issues: opened 10 participated in 4
   orcid: 0000-0001-6862-6526
   affiliation: 10, 11
 - name: Michael Dayan  # 12 commits, issues: opened 1 participated in 2
   orcid: 0000-0002-2666-0969
   affiliation: 12
 - name: Sean Dae Houlihan  # 12 commits, issues: opened 0 participated in 0 # First: Sean Dae; Last: Houlihan
   orcid: 0000-0001-5003-9278
   affiliation:  1, 13
 - name: James Kent  # 8 commits, issues: opened 3 participated in 0
   orcid: 0000-0002-4892-2659
   affiliation: 14
 - name: Ted Strauss  # 0 commits, issues: opened 8 participated in 0
   orcid: 0000-0002-1927-666X
   affiliation: 15
 - name: John Lee  # 2 commits, issues: opened 5 participated in 1
   orcid: 0000-0001-5884-4247
   affiliation: 16
 - name: Isaac To  # 7 commits, issues: opened 0 participated in 0
   orcid: 0000-0002-4740-0824
   affiliation: 1
 - name: Christopher J. Markiewicz  # 4 commits, issues: opened 1 participated in 2
   orcid: 0000-0002-6533-164X
   affiliation: 2
 - name: Darren Lukas  # 4 commits, issues: opened 1 participated in 2
   orcid: 0009-0003-6941-0833
   affiliation: 17
 - name: Ellyn R. Butler  # 0 commits, issues: opened 4 participated in 2
   orcid: 0000-0001-6316-6444
   affiliation: 23
 - name: Todd Thompson  # 0 commits, issues: opened 5 participated in 0
   orcid: 
   affiliation: 13
 - name: Maite Termenon  # 0 commits, issues: opened 5 participated in 0
   orcid: 0000-0001-8102-5135
   affiliation: 18, 19
 - name: David V. Smith  # 0 commits, issues: opened 4 participated in 1
   orcid: 0000-0001-5754-9633
   affiliation: 20
 - name: Austin Macdonald  # 2 commits, issues: opened 1 participated in 1 + 1 commit in paper repo
   orcid: 0000-0002-8124-807X
   affiliation: 1
 - name: David N. Kennedy  # Benevolent leader of ReproNim who holds the umbrella and was brave to try a number of times
   orcid: 0000-0002-9377-0797
   affiliation: 21
affiliations:
 - name: Center for Open Neuroscience, Department of Psychological and Brain Sciences, Dartmouth College, Hanover, NH, USA
   index: 1
 - name: Department of Psychology, Stanford University, CA, USA
   index: 2
 - name: McGovern Institute, Massachusetts Institute of Technology, Cambridge, MA, USA
   index: 3
 - name: Flywheel Exchange LLC, Minneapolis, MN, USA
   index: 4
 - name: University of California, Berkeley, Berkeley, CA, USA
   index: 5
 - name: Perelman School of Medicine, University of Pennsylvania, Philadelphia, PA, USA
   index: 6
 - name: Institute of Neuroscience and Medicine, Brain & Behaviour (INM-7), Research Center Jülich, Jülich, Germany
   index: 7
 - name: Institute of Systems Neuroscience, Medical Faculty, Heinrich Heine University Düsseldorf, Düsseldorf, Germany
   index: 8
 - name: Department of Psychology, University of South Carolina, Columbia, SC, USA
   index: 9
 - name: Masonic Institute for the Developing Brain, University of Minnesota, Minneapolis, MN, USA
   index: 10
 - name: Minnesota Supercomputing Institute, University of Minnesota, Minneapolis, MN, USA
   index: 11
 - name: Human Neuroscience Platform, Fondation Campus Biotech Geneva, Geneva, Switzerland
   index: 12
 - name: Department of Brain and Cognitive Sciences, Massachusetts Institute of Technology, Cambridge, MA, USA
   index: 13
 - name: Department of Psychology, University of Texas at Austin, Austin, TX, USA
   index: 14
 - name: McConnell Brain Imaging Centre, McGill University, Montreal, QC, Canada
   index: 15
 - name: Data Science and Sharing Team, National Institute of Mental Health, Bethesda, MD, USA
   index: 16
 - name: Institute for Glycomics, Griffith University, QLD, Australia
   index: 17
 - name: Biomedical Engineering Department, Faculty of Engineering, Mondragon University, Mondragon, Spain
   index: 18
 - name: BCBL, Basque center on Cognition, Brain and Language, San Sebastian, Spain
   index: 19
 - name: Department of Psychology and Neuroscience, Temple University, Philadelphia, PA, USA
   index: 20
 - name: Departments of Psychiatry and Radiology, University of Massachusetts Chan Medical School, Worcester, MA, USA
   index: 21
 - name: Department of Biostatistics, Johns Hopkins Bloomberg School of Public Health, Baltimore, MD, USA
   index: 22
 - name: Department of Psychology, Northwestern University, Evanston, IL, USA
   index: 23
 - name: Emeritus of Department of Psychology, Stanford University, CA, USA
   index: 24

date: 6 July 2023
bibliography: paper.bib

---

# Summary

In order to support efficient processing, data must be formatted according to standards prevalent in the field, and widely supported among actively developed analysis tools.
The Brain Imaging Data Structure (BIDS) [@GAC+16] is an open standard designed for computational accessibility, operator legibility, and a wide and easily extendable scope of modalities — and is consequently used by numerous analysis and processing tools as the preferred input format in many fields of neuroscience.
HeuDiConv (Heuristic DICOM Converter) enables flexible and efficient conversion of spatially reconstructed neuroimaging data from the DICOM format (quasi-ubiquitous in biomedical image acquisition systems, particularly in clinical settings) to BIDS, as well as other file layouts.
HeuDiConv provides a multi-stage operator input workflow (discovery, manual tuning, conversion) where manual tuning step is optional and thus the entire conversion can be seamlessly integrated into a data processing pipeline.
HeuDiConv is written in Python, and supports the DICOM specification for input parsing, and the BIDS specification for output construction.
The support for these standards is extensive, and HeuDiConv can handle complex organization scenarios such as arise for specific data types (e.g., multi-echo sequences, or single-band reference volumes).
In addition to generating valid BIDS outputs, additional support is offered for custom output layouts.
This is obtained via a set of built-in fully functional or example heuristics expressed as simple Python functions.
Those heuristics could be taken as a template or as a base for developing custom heuristics, thus providing full flexibility and maintaining user accessibility.
HeuDiConv further integrates with DataLad [@datalad], and can automatically prepare hierarchies of DataLad datasets with optional obfuscation of sensitive data and metadata, including obfuscating patient visit timestamps in the git version control system.
As a result, given its extensibility, large modality support, and integration with advanced data management technologies, HeuDiConv has become a mainstay in numerous neuroimaging workflows, and constitutes a powerful and highly adaptable tool of potential interest to large swathes of the neuroimaging community.


# Statement of need

Neuroimaging is an empirical research area which relies heavily on efficient data acquisition, harmonization, and processing.
Neuroimaging data sourced from medical imaging equipment, and in particular magnetic resonance imaging (MRI) scanners, can be exported in numerous formats, among which DICOM (Digital Imaging and Communications in Medicine) is most prominent.
DICOM data are often transmitted to PACS (Picture Archiving and Communication Systems) servers for archiving or further processing.
Unlike in clinical settings, where data are interfaced with directly from PACS in the DICOM format, in neuroimaging research, tools typically require data files in the NIfTI [@nifticlib] format which directly stores images as 3D or 4D objects and restricts metadata to the most useful attributes.
Tools such as `dcm2niix` [@Li_2016] can be used to convert DICOM files into NIfTI files, and can extract metadata fields not covered by the NIfTI header into sidecar `.json` files.
However, the scope of such tools is limited, as it does not extend to organizing multiple NIfTI files for different subjects and possibly scanning sessions within a study.

HeuDiConv was created in 2014 to provide flexible tooling so that labs may rapidly and consistently convert collections of DICOM files into collections of NIfTI files in customizable file system hierarchies.
As manual file renaming and metadata reorganization is tedious and error prone, automation is preferable, and this is a consistent focus of HeuDiConv.

Since the inception of HeuDiConv in 2014, the BIDS standard [@GAC+16] was established.
BIDS standard formalizes data file hierarchies and metadata storage in a fashion which, due to its community-driven nature, is both highly optimized and widely understood by analysis tools.
Since then, DICOM conversion to NIfTI files contained within a BIDS hierarchy has emerged as the most frequent use-case for HeuDiConv.

# State of the field

Conversion of data to BIDS is acknowledged to remain one of the challenges [@PMA+arXiv2024:bids-past] which lead to the proliferation of converters to BIDS (see [https://bids.neuroimaging.io/benefits#converters](https://bids.neuroimaging.io/benefits#converters)).
As BIDS grows and evolves, so do the requirements for conversion tools.
New converters are being developed, and existing ones are being updated to accommodate new data types and modalities.
HeuDiConv is one of the most widely used converters, and its use stats keep growing (see \autoref{fig:usage}.
It is actively maintained and developed to keep up with the latest BIDS standards and community needs.
Although it could be used without any knowledge of Python programming, it is designed to be extensible and customizable, and to allow for the development of custom heuristics to handle specific data types and modalities.
Unlike GUI- or Web-UI based tools, such as EZ-BIDS [@ezbids], which might be easier for novices to use, HeuDiConv is designed to be used in a command-line environment, and is thus well-suited for integration into automated data processing pipelines.

# Overview of HeuDiConv functionality

HeuDiConv has been developed to implement logic commonly used across labs (grouping DICOMs, extracting metadata, converting individual sequences, populating standard BIDS files, etc.) while allowing individual groups to customize **how** files should be organized and named while driving custom decisions through the conventions and desires of those individual groups.
Such decision making is implemented in *HeuDiConv heuristics*, which are implemented as Python modules following some minimalistic specified interfaces documented in HeuDiConv documentation (https://heudiconv.readthedocs.io/en/latest/heuristics.html).
HeuDiConv, if instructed to operate in BIDS mode (`--bids` flag) with a heuristic providing base naming instructions, and helpers to organize the files in the hierarchy defined by the BIDS standard.
It also ensures files are named according to the BIDS specifications, including complex composite recordings such as those associated with multi-echo sequences.

![**HeuDiConv automates the keystone conversion step in reproducible data handling, without compromising operator flexibility.** The showcased set-up depicts a 2-machine infrastructure, with heudiconv operating on the same machine as subsequent analysis steps for data in a standardized and shareable representation. For more advanced usage at institutions with dedicated infrastructure, HeuDiConv can operate on an additional third machine, interfacing between the depicted two, and dedicated to data repositing, versioning, and backup.](figs/environment.pdf)


![**HeuDiConv conversion and layout is controlled via heuristics (custom or provided built-ins) either with manual tune up of proposed filenames or fully automated.** The heudiconv application can be used with the `-c none` parameter to generate by heuristic a list of filenames for the user to edit, before invoking the conversion to be performed via the `-c dcm2niix` option to use the `dcm2niix` tool. The process is idempotent, and specifying the `-c dcm2niix` option can automatically convert without seeking user tune up of proposed filenames.](figs/workflow.pdf)

## Exemplar heuristics

### Convertall

The [convertall heuristic](https://github.com/nipy/heudiconv/blob/v0.12.2/heudiconv/heuristics/convertall.py) is the simplest heuristic which expresses no knowledge or assumptions about anything and can be used as a template to develop new heuristics or to establish initial mapping for manual naming of the sequences in the "manual curation" step.

### StudyForrest phase 2

The [studyforrest_phase2 heuristic](https://github.com/nipy/heudiconv/blob/v0.12.2/heudiconv/heuristics/studyforrest_phase2.py) is a small sample heuristic developed for the StudyForrest [@studyforrest] project, and demonstrates custom conversion into BIDS dataset.

### ReproIn

The [ReproIn heuristic](https://github.com/nipy/heudiconv/blob/v0.12.2/heudiconv/heuristics/reproin.py) was initially developed at the Dartmouth Brain Imaging Center (DBIC) to automate data conversion into BIDS for any neuroimaging study performed using the center's facilities.
The core principle behind ReproIn is the reduction of operator interaction required to obtain BIDS datasets for acquired data.
It is achieved by ensuring that reference MRI sequences on the instrumentation are organized and named in a consistent and flexible way, such that upon usage in any experimental protocol they will encode the information required for fully automatic conversion and repositing of the resulting data.

In case of correct specification and absent operator errors, such as mis-typed subject or session IDs, it can be fully automated, and work is ongoing to make such deployments turnkey. Visit ReproIn project page [http://reproin.repronim.org](http://reproin.repronim.org) to discover more.

To try it out, one can download sample [`reproin_dicom.zip`](https://datasets.datalad.org/repronim/heudiconv-reproin-example/reproin_dicom.zip) and use the following command:

```bash
heudiconv --files reproin_dicom.zip -f reproin --bids -o bids_datasets 
```

to produce a BIDS dataset in the `bids_datasets/output/Patterson/Coben/` sub-directory. 
This demonstrates ability to automate conversion using ReproIn for all studies in the center.
[Tutorials section](https://heudiconv.readthedocs.io/en/latest/tutorials.html) in the HeuDiConv documentation provides more examples across for different scenarios. 

# Adoption and usage

As a citeable resource [RRID:SCR_017427](https://scicrunch.org/resolver/RRID:SCR_017427), Heudiconv has already [6 mentions in papers](https://scicrunch.org/resolver/SCR_017427/mentions?q=&i=rrid:scr_017427) at time of writing.
There is a growing number of downloads from PyPI and uses of HeuDiConv (see \autoref{fig:usage}).
Over 40 BIDS datasets were converted over to BIDS with HeuDiConv at Dartmouth Brain Imaging Center (DBIC), using the ReproIn heuristic developed there.
HeuDiConv was found to be used for PET data conversion [@JZC+21:PET], shared as OpenNeuro ds003382 [@openneuro.ds003382.v1.0.0].
Moreover, the HeuDiConv approach inspired the development of `fw-heudiconv` (FlywheelTools: Software for HeuDiConv-Style BIDS Curation On Flywheel) [@TCB+21:fw-heudiconv].

![**\label{fig:usage}Downloads experienced an initial sharp rise after the ReproNim HeuDiconv training event at OHBM in mid 2018, and have subsequently followed a positive trend along with the usage — exceeding 1000 sessions per week — in the data collection interval.** Depicted are weekly download and confirmed session estimates, averaged per month, with a 95% confidence interval. User session estimates for July and August 2022 are linearly extrapolated from the nearest neighbour. Download counts are sourced from PyPI, the Python community repository; whereas user session counts are sourced from Etelemetry, an infrastructure for verifiable research impact, which end-users can disable to protect privacy.](figs/usage.pdf)


# External dependencies

HeuDiConv uses specialized tools and libraries:

- [`datalad`](https://datalad.org) [@datalad] ([RRID: SCR_003931](https://scicrunch.org/resolver/RRID:SCR_003931)) enables managing produced datasets as version controlled repositories.
- [`dcm2niix`](https://github.com/rordenlab/dcm2niix) [@Li_2016] is used for the conversion from DICOM to NIfTI and initial versions of sidecar .json files,
- [`etelemetry`](https://github.com/sensein/etelemetry-client) and [`filelock`](https://github.com/tox-dev/py-filelock) are used as supplementary utilities,
- [`neurodocker`](https://github.com/ReproNim/neurodocker) [@zenodo:neurodocker] ([RRID:SCR_017426](https://scicrunch.org/resources/data/record/nlx_144509-1/SCR_017426/resolver?q=dcm2niix&l=dcm2niix&i=rrid:scr_017426)) is used to produce `Dockerfile` from which docker images are built,
- [`nipype`](https://nipype.readthedocs.org/) [@nipype] ([RRID:SCR_002502](https://scicrunch.org/resources/data/record/nlx_144509-1/SCR_002502/resolver)) to interface `dcm2niix` and extra metadata invocations,
- [`pydicom`](https://pydicom.github.io/) [@zenodo:pydicom] ([RRID:SCR_002573](https://scicrunch.org/resources/data/record/nlx_144509-1/SCR_002573/resolver)) and [`dcmstack`](https://github.com/moloney/dcmstack) for DICOM analysis and extraction of extra metadata to place to BIDS sidecar files,
- [`pytest`](https://pytest.org) formalizes unit and integration testing.

# Acknowledgments

We would like to extend our gratitude to
Matthew Brett,
Jörg Stadler,
Russell Poldrack,
Sin Kim,
Dan Lurie,
and Henry Braun
for notable contributions to the codebase, bug reports, recommendations, and promotion of HeuDiConv.

HeuDiConv development was primarily done under the umbrella of the NIH funded Nipype [1R01EB020740-01](https://reporter.nih.gov/search/ZZFBbUBAxE2obl72ByIn0Q/project-details/9053094), ReproNim [1P41EB019936-01A1](https://projectreporter.nih.gov/project_info_details.cfm?aid=8999833&map=y) and [2P41EB019936-06A1](https://projectreporter.nih.gov/project_info_details.cfm?aid=10334133&map=y) (PI: Kennedy).


# References
