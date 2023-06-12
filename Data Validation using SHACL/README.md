SHACL Online Validators:
- [SHACL Playground](https://shacl.org/playground/)
- [SHACL Play! (sparna.fr)](https://shacl-play.sparna.fr/play/validate)
- [SHACL Online Editor (liu.se)](https://www.ida.liu.se/~robke04/SHACLTutorial/)
- [SHACL Validator (europa.eu)](https://www.itb.ec.europa.eu/shacl/shacl/upload)
- [SHACL Playground by Zazuko ](https://shacl-playground.zazuko.com/)

Handson session 1:
SHAPES GRAPH
ex:WallShape a sh:NodeShape ; 	
   sh:targetClass ifcOWL:IfcWallStandardCase ; 
   sh:property [
      sh:path ifcowl:globalId_IfcRoot; 
      sh:minCount 1;
      sh:maxCount 1;
] ;

Handson session 2:
SHAPES GRAPH
ex:WallShape a sh:NodeShape ; 	
   sh:targetClass ifcOWL:IfcWallStandardCase ; 
   sh:property [
      sh:path ifcowl:globalId_IfcRoot; 
      sh:minCount 1;
      sh:maxCount 1;
] ;

DATA GRAPH
inst:IfcWallStandardCase_91
  rdf:type  ifcowl:IfcWallStandardCase;
  ifcowl:globalId_IfcRoot inst:IfcGloballyUniqueId_27659.

inst:IfcWallStandardCase_92
  rdf:type ifcowl:IfcWallStandardCase ;
  ifcowl:globalId_IfcRoot inst:IfcGloballyUniqueId_27663;
  ifcowl:globalId_IfcRoot inst:IfcGloballyUniqueId_12365.
  
  






