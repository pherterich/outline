Proposal to run a BoF on Notebooks at RDA Helsinki
TL;DR

A proposal is being put together to run a BoF session on Notebooks (i.e. discussions on Jupyter and myBinder but if this is too narrow a scope please say so) at RDA Helsinki which will run from 23rd-25th of October. The deadline for the proposal is the 27th June.

If you are interested in getting involved, attending the meeting or have suggestions for discussion topics, then please either email

Hugh dot Shanahan at rhul dot ac dot uk or do a pull request on this document.
Introduction

Notebooks, specifically Jupyter notebooks (but also notebooks based on Rmarkdown) are generating a great deal of excitement and are potentially a significant step forward in terms of reproducibility, education, code documentation and academic publishing. A recent paper found nearly 1.2 Million unique notebooks just going through github.

More recently the deployment of sites such as JupyterHub, myBinder and EGI notebooks mean that notebooks can be deployed on a cloud and hence obviates issues with installed libraries. One potential result of this is that it would represent the easiest pathway for users to use cloud computing resources for research which could transform the use of such resources. It is important that frameworks such as EOSC become more aware of such initiatives at a policy level.
Proposal logistics

Details of how to apply for a BoF can found here. The application is itself relatively short though it's worth looking carefully at the criteria that are set. It's important to make sure it matches the RDA's mission and that it's not simply a set of talks but that there's room for discussion.
Possible discussion points for BoF

The following are a set of possible topics that could be discussed at the BoF. There probably is time to discuss
Notebook citation

Given the profusion of notebooks it is clear that a system of enabling the citation of notebooks needs to be implemented. In many respects this represents an opportunity as the infrastructure behind notebooks is comparatively new and hence potentially easily adapted to follow citations guidelines for the Force 11 software citation implementation group and the software source code Interest Group citation group in the RDA. How to provide DOI's easily for notebooks represents part of this challenge.
Integration of notebooks with data services.

Notebooks have a very simple directory mechanism with all the files of interest being in the same folder as the notebook. As notebooks are used to access large data sets, there need to be mechanisms to either access specific data storage mechanisms (such as the EGI data store) or to provide more general mechanisms for accessing data sets through PID's as an example.
Deploying notebooks on large Scientific computational platforms.

Using notebooks on, for example, platforms with access to multiple CPU's presents more challenges.
Long-term preservation

At present long term storage of notebooks is carried out with repositories such as Zenodo. On the other hand there isn't a mechansim to ensure that the notebooks will continue to run in the long term. Solutions to solve this problem are essential.
Influencing policy

The EGI already successfully deployed a notebook solution. Can the functionality of Binder be similarly deployed? How do notebooks fit into the EOSC vision and other similar platforms? If not what steps can be made to influence thinking in this area.
Software engineering and notebooks

A valid criticism of notebooks are that it encourages poor software engineering practice such as TDD or encapsulating the notebooks into libraries. Some of this stems from the fact that notebook editors are nowhere near as developed as other IDE's but the first concerns are genuine. What steps can be taken to improve this situation?
Interested parties

Hugh Shanahan, Royal Holloway, University of London

Martin Fenner, DataCite

Tim Head, MyBinder, Project Jupyter

Neil Chue Hong, Software Sustainability Institute

Rosie Higman, University of Manchester

Jez Cope, The British Library

Patricia Heterich, University of Birmingham

Gergely Sipos snd Enol Fernández, EGI

Christine Kirkpatrick, National Data Service

Rob Quick, Indiana University

Brian Matthews, STFC

Frank Schluenzen, DESY
