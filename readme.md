# PlantUML DSL - An xtext based DSL for PlantUML

This project aims at develop a DSL for PlantUML.

PlantUML (https://plantuml.com) is a very sucessfull tool for building UML based diagrams.

We have been using this tool with success in several contexts, particularly in classes (undergraduate and graduate levels) at ISEP (https://www.isep.ipp.pt).

The tool is very useful by enabling the use of diagrams as code. With this kind of tool it becomes very simple to do control version of diagrams, as we usually do with code.

However, the tool is limited by not using a formal grammar. Without a grammar it is difficult, for instance, to verify the syntax of a diagram or check if it matches the source code.

This projet aims at providing a DSL for PlantUML.

We such a tool, we should be able to:
 - check the sintax of diagrams;
 - check if a diagram references elements that exist in the source code;
 - provide metrics for the diagrams, such as code coverage;

This work is based on the following related projects:
  - [Plantuml](https://github.com/atb/atb-plantuml)
  - [Plantuml Eclipse Plugin](https://github.com/atb/atb-plantuml-eclipse)
  - [Plantuml Ericsson](https://github.com/atb/atb-plantuml-ericsson)
  - [Plantuml Parser](https://github.com/atb/plantuml-parser)
  - [Plantuml Code Generator](https://github.com/atb/plantuml-code-generator)
