This repository contains the project that I brought as the exam project for the Semantic Web course (42500), University of Bologna.

The project attempts to describe the basic structure and schedule of a 3x3 Summer Tournament of the FIP Circuit, active from this year (2021). 

To do so, a general ontology has been created, called FIP 3x3 Summer Tournament Ontology. This one can be used as a ABox to describe a generic tournament of the FIP 3x3 Summer Circuit.

Then, I tried to describe a specific Summer Tournament, The Canestreet, that has been played in Jesi (AN) in July 2021, describing the schedule, the teams, and the structure of it.

## How to use

Both ontologies can be accessed directly from Protegé cloning the project or simply referring the static ontology addresses.

### Open the ontologies cloning the project

If you clone the project, you can consult the entire dependency tree locally. After the clone, you can open `fip-3x3.owl` or `the-canestreet.owl` to consult the ontology. IMPORTANT: do not modify directly the catalog.xml file, as it redirects the imports to the right local locations.

### Open the ontologies without cloning

The ontologies are also available in static web locations. This means that with Protegé, you can also simply open the project with Open > Open from URL, and select the right static URL:
- https://maldins46.github.io/WS2021-ExamProjectMaldini/ontologies/fip-3x3-1.0.0.owl for the FIP 3x3 Summer Tournament Ontology;
- https://maldins46.github.io/WS2021-ExamProjectMaldini/ontologies/the-canestreet-1.0.0.owl for The Canestreet Ontology.

## Some additional notes

The import schema used into the project (i.e., position some of the imported ontologies inside the `/imports` folder, instead of referring them with the original URL) has been adopted to overcome [a well-known problem](https://stackoverflow.com/questions/57728429/importing-bbc-food-ontology-in-protege-5-5) of BBC ontologies, in which the ontologies cannot be directly referred from the original location. For this reason dependency have been copied, both in a static web space and into the `/imports` subfolder, correcting the wrong lines inside the ontologies.