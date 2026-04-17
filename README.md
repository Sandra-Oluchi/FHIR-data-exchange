# FHIR-data-exchange
This project focuses on FHIR query and how to exchange information across the health system using Postman, which accepts a JSON or XML format document

This project involved the use of RESTful APIs to be able to perform CRUD operations such as Create, Retrieve< Update, and Delete FHIR resources such as:
Patient resource, Practitioner, and Observation.

One of the operations performed was the Create operation using the Post restful Apl and the base URL and endpoint to fetch a practitioner name who was involved in treating a patient.

http://localhost:8090/fhir -  this serves as the base URL
/Practitioner  - this serves as the endpoint.

After such operations were done, the status response code: 201 was shown, indicating the resource was created.

## The outcome of this project:
Shows how clinicians can act as interoperability analysts to create resources or send bundles as well as use such for analysis.
