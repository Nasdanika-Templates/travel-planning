# Travel Planning

This is a [Draw.io Site](https://nasdanika-templates.github.io/drawio-site/) template repository for travel planning and documentation.

[TOC levels=6]

## Demos

Below is a list of sites created from this template:

* [Patagonia Trip](https://nasdanika-demos.github.io/patagonia-trip/).

## Steps

* Follow the Draw.io Site instructions to create a repository from this template.
* Open ``Travel.xml`` library in Draw.io.
* Use library elements to plan/document your trip. Follow instructions in element tooltips and use the existing diagram elements as examples.

### Local generation

To generate sites locally install [Nasdanika CLI] - download from the [releases](https://github.com/Nasdanika/cli/releases) page.
On Windows you can download the Windows package with a bundled JDK, unzip it to the project directory and then use ``generate-site.bat``.
Linux users can create a script based on ``generate-site.bat``. If you do - submit a pull request and I'll add it to this repository!

### Collaborative planning

There are several approaches for collaborative planning which can be used together:

* One diagram, multiple text files. People collaborate on text files, the diagram is edited "sequentially".
* Multiple "federated" diagrams. For example, the top-level diagram with major destinations, diagram files for destinations referenced from the top-level diagram. A single site is generated from the diagram set.
* Multiple federated sites. For example, the top-level site with major destinations, sub-sites for destinations referenced by the top-level site. This approach can be used if, say, several groups have an overlapping travel segment.

## Resources

* [Travel as code](https://medium.com/nasdanika/travel-as-code-eaf0d3738cc1) Medium story.