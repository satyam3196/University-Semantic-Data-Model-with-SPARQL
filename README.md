# University Ontology

This project focuses on the development of an ontology for university data using the Protégé-OWL editor. The ontology is a comprehensive semantic data model that incorporates skills in Description Logic (DL) and SWRL (Semantic Web Rule Language) to create an engaging and educational experience.

## Objective
The objective of this project is to build an ontology that represents university data by sourcing information from DBPedia (primary source) and Wikidata (secondary source). The ontology includes appropriate relationships between classes and the incorporation of data and object properties.

## Files Included
The following files are included in the project:

### Ontology Files
1. `file.ttl`: This file contains the basic ontology (T-Box) without any populated data.
2. `Ontology.ttl`: This file contains the populated ontology with data populated from DBPedia.
3. `Updated_ontology.ttl`: This file contains the updated ontology, which includes data from the original ontology file (`Ontology.ttl`) as well as a CSV file created via a query from the Wikidata query service.
4. `SWRL_ontology.ttl`: This file contains the populated ontology with SWRL rules.

### CSV file
- `Query.csv`: This file contains the query generated from the Wikidata query service, which includes universities from the state of Wisconsin, USA.

### Python files
1. `pythonfile.py`: This Python script is used to populate `file.ttl` with data from DBPedia using SPARQL queries and Python.
2. `pythonfile(BonusTask).py`: This Python script is used to merge data from `Query.csv` to the ontology, demonstrating the addition of external data to the ontology.

### Project Report
- `Project_Report.pdf`: This file contains the project report providing detailed information about the project, including the methodology, challenges faced, and insights gained.

## Running the Code
Follow these steps to run the code and interact with the ontology:

1. To view the T-Box, upload the `file.ttl` file into Protégé.
2. For the basic task, upload the `Ontology.ttl` file to display both the T-Box and A-Box.
3. For the Bonus Task 1, upload the `Updated_ontology.ttl` file to examine the DBPedia data, which now includes data from Wikidata as well.
4. For the Bonus Task 2, upload the `SWRL_ontology.ttl` file, which contains the SWRL rules.

## Acknowledgements
The successful completion of this project was made possible through the following resources:

- Professor's lab sessions, lecture slides, and example ontologies.
- Various online resources that provided valuable guidance.

## Conclusion
This project has expanded the knowledge in the field of ontologies and demonstrated the practical application of Description Logic and SWRL skills. The developed ontology provides a structured representation of university data, leveraging data from multiple sources and incorporating logical rules for inference and reasoning.

Please refer to the attached [Project_Report.pdf](Project_Report.pdf) for a detailed overview of the project, including the methodology, challenges faced, and insights gained.
