# SSCV2-Datasphere-Integration
This repository is related to a series of two SAP Community articles on how to establish an event driven data integration between Sales and Service Cloud V2 (SSC2) and SAP Datasphere, using SAP Cloud Integration as a middleware for event queueing, data transformation and protocol adaptation. 

The articles can be accessed through the following links:

[Event-Driven Data Integration from SAP Sales and Service Cloud V2 to SAP Datasphere (Part 1 of 2)](https://community.sap.com/t5/crm-and-cx-blogs-by-sap/event-driven-data-integration-from-sap-sales-and-service-cloud-v2-to-sap/ba-p/14003914)

[Event-Driven Data Integration from SAP Sales and Service Cloud V2 to SAP Datasphere (Part 2 of 2)](https://community.sap.com/t5/crm-and-cx-blogs-by-sap/event-driven-data-integration-from-sap-sales-and-service-cloud-v2-to-sap/ba-p/14046866)

The artefacts that are needed to setup the end-to-end integration scenarios as described in these articles are provided in the "artefacts" folder of this repository:

* "SCV2 to DataSphere - Standard Events.zip"
  * Contains the iFlow definition for the integration scenario
  * The zip file can be directly uploaded to an integration package on SAP Cloud Integration, to create the iFlow definition there

* "DDL statements for table creation.zip"
  * Contains one individual DDL file for each table to be created
  * The statements specified per file can directly be copied into the SQL console of the Hana Cloud DB of SAP Datasphere and executed from there
