# 52°North Triturus WorldViz
README file for the [52°North Triturus WorldViz library][1]

52°North Triturus WorldViz supports the development of thematic 3-D visualizations at world scale.
Regarding the traditional visualization pipeline, the framework focuses the 
mapping step, i.e. the transformation between geo-objects and abstract 
visualization-objects. Thus, WorldViz allows to generate concrete scene descriptions,
e.g. X3D documents, from geo-data, thereby keeping the "cartographic" mapping process 
configurable. 

WorldViz is based on the existing 52°North Triturus module and shall offer various 
world visualizations, e.g. globes (limited to world-scale), potato-like globe 
deformations depending on thematic data, feature-space scenes, visualization of geo-object relations
(connections maps in 3-d space) as well as planar map-projections in 3-d space.
WorldViz will offer scene export facilities for various concrete scene descriptions 
(presumably for X3D, X3DOM, KML). 

The framework will be used to set-up the experiental space ENE ("Erlebnisraum
Nachhaltige Entwicklung") at Bochum University of Applied Science (Hochschule Bochum). 
Both the ENE and this framework are open to anyone who is interested. You are very welcome to 
participate or to bring in innovative visualization ideas. 

## Basic functionality:
* Readers for thematic world data (XML-based ENE data) and shape geometries
* Simple scene export (e.g., X3D/X3DOM scene descriptions)
* Generation of globe representations at world-scale
* ... 

## Characteristics
* Development platform: Java (Windows and Linux/Unix)
* Visualization pipeline (filter, mapper, renderer) as reference model
* Abstraction of concrete (geo-)datasources and scene description environments through interfaces

## Development goals
The community's vision is to establish a creative surrounding, which allows efficient and sustainable development of innovative software solutions in the context of 3d geovisualization at world scale.

## Installation
...

Note that 52°North Triturus WorldViz requires the 52°North Triturus library (JAR).

## License information
This program is free software; you can redistribute it and/or modify it
under the terms of the Apache License version 2.0.

For further information please refer to 'LICENSE'-file

## Additional documents and links
This sections lists documents that lead to a deeper understanding of the Triturus library and give additional information.

* White Paper of Triturus: http://52north.org/images/stories/52n/communities/3D/triturus%20white%20paper.pdf 
* 52°North 3D Community Wiki: https://wiki.52north.org/bin/view/V3d/ 
* Triturus Wiki: https://wiki.52north.org/bin/view/V3d/Triturus 

## Contributing
You are interesting in contributing the 52°North Triturus and you want to pull your changes to the 52°North 
repository to make it available to all?

In that case we need your official permission and for this purpose we have a so called contributors license agreement (CLA) in place. With this agreement you grant us the rights to use and publish your code under an open source license.

A link to the contributors license agreement and further explanations are available here: 

    http://52north.org/about/licensing/cla-guidelines

## Support and Contact
You can get support in the community mailing list and forums:

    http://52north.org/resources/mailing-lists-and-forums/

If you encounter any issues with the software or if you would like to see
certain functionality added, let us know at:

 - Benno Schmidt (b.schmidt@52north.org)
 - Christian Danowski (christian.danowski@hs-bochum.de)
 - Martin May (m.may@52north.org)

The 3D Community

52°North Inititative for Geospatial Open Source Software GmbH, Germany

--
[1]: http://52north.org/communities/3d/triturus
