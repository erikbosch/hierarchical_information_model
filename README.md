# COVESA Hierarchical Information Model (HIM)

[![License](https://img.shields.io/badge/License-MPL%202.0-blue.svg)](https://opensource.org/licenses/MPL-2.0)

## Governance

<!-- Give a short rationale for the repository -->

This repository contains the COVESA Hierarchical Information Model (HIM) - an initiative from COVESA to create a model
that can be used to define information (see below) representing any domain. 
[VSS](https://github.com/COVESA/vehicle_signal_specification) is an example of one domain that is planned to be possible to model in HIM.

<!-- Give a short description of which group/project in COVESA that manages this repository and link to their wiki -->

This repository is managed by the [COVESA Data Expert Group](https://wiki.covesa.global/display/WIK4/Data+Expert+Group).

## HIM Overview

The information of a domain that is described using HIM is represented in a graph made up of a tree structure with parent-child relationships,
as shown in Figure 1.
![HIM graph structure](pics/him_graph_structure.png?raw=true)<br>
*Figure 1. HIM graph structure<br>

HIM does not have the ambition to define the content of any domain,
it stops at defining the rules for how a hierarchical representation of a domain is to be expressed.
This rule set aims at being domain agnostic and can thus be used to define the taxonomies for different domains.

Another ambition of HIM s that it shall support definition of taxonomies of different types of information,
and not only the type here called "resource data".
HIM currently supports the following "information types":
- Resource data: Information defining the data that a resource produces or consumes.
- Service data: Information defining the details of a "service" in the form of a procedure (name, iput, output).
- Type definition data: Information defining complex/composite data types that are used by the other information types.

What is not an ambition of HIM is to define how the information is transported between agents,
which is left to projects defining transport protocols, interfaces, and the like.

## HIM documentation

The HIM rule sets documentation will be found on [this link](TBD).
As a site that can host the documentation is not yet available,
the alternative in order to get an easy-to-read rendering of the markup formatted text is:
1. Clone the repo
2. Install [HUGO](https://gohugo.io/getting-started/).
3. In a terminal window, go to the hierarchical_information_model/docs-gen/ diretory
4. Start the HUGO server: $ hugo server
5. Copy the link that the HUGO server presents in the terminal window, and paste it into a browser tab.

## HIM origin

The HIM model traces its roots to the COVESA 
[Vehicle Signal Specification (VSS)](https://github.com/COVESA/vehicle_signal_specification) project.

When the adoption of the VSS data model started to take off, 
also requests for additional data and other functionality started to be asked for. 
Instead of trying to accomodate all of these requests in the single tree that defined the VSS domain, 
it was decided that an extended model was to be developed, the Hierarchical Information Model.


<!-- For status and roadmap of this repository please visit ... -->

*(There should for each COVESA repository be a page on COVESA wiki giving information on roadmaps, meetings, maintainers and so on...)*


