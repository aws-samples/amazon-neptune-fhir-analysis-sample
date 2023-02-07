## Analyzing healthcare FHIR data with Amazon Neptune

This repository contains a Jupyter Notebook to run in the [Amazon Neptune](https://aws.amazon.com/neptune/?nc1=h_ls) workbench and a sample dataset. The files are required to follow the walkthrough to [Analyze healthcare FHIR data with Amazon Neptune](https://aws-blogs-prod.amazon.com/database/?p=29731).

## Content

The __fhir-questionnaire-response-dataset.zip__ file contains 500 Turtle files of sample [FHIR QuestionnaireResponse](https://www.hl7.org/FHIR/questionnaireresponse.html) resources following the RDF specification of [FHIR](http://hl7.org/fhir/). 

The Juypter notebook __analyze-fhir-questionnaire-responses-neptune.ipynb__ can be used in the Amazon Neptune workbench to run sample SPARQL queries on a graph containing the sample dataset.

## Usage

Refer to [Analyze healthcare FHIR data with Amazon Neptune](Link TBD) for how to load the data into Neptune and information on the queries in the Jupyter notebook. 

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This project is licensed under the MIT-0 License. See the LICENSE file.

