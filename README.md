# SSCV2-Datasphere-Integration
This repo is related to a series of two SAP Community articles on how to establish an event driven data integration between Sales and Service Cloud V2 (SSC2) and SAP Datasphere, using SAP Cloud Integration as a middleware for event queueing, data transformation and protocol adaptation. 

[Event-Driven Data Integration from SAP Sales and Service Cloud V2 to SAP Datasphere (Part 1 of 2)](https://community.sap.com/t5/crm-and-cx-blogs-by-sap/event-driven-data-integration-from-sap-sales-and-service-cloud-v2-to-sap/ba-p/14003914)

[Event-Driven Data Integration from SAP Sales and Service Cloud V2 to SAP Datasphere (Part 2 of 2)](https://community.sap.com/t5/crm-and-cx-blogs-by-sap/event-driven-data-integration-from-sap-sales-and-service-cloud-v2-to-sap/ba-p/14046866)

It stores the required artefacts that are needed to setup the end to end scenarios as described in the community articles.
Two zip files are provided in the "artefacts" folder:
* SCV2 to DataSphere - Standard Events.zip
  * Contains the iFlow definition for the integration scenario
  * The zip file can be directly uploaded to an integration package on SAP Cloud Integration, to create the iFlow definition there
* SAP Datasphere: DDL statements for table creation
  * Contains one individual DDL file for each table to be created - the statements specified per file can directly be copied into the SQL console of Hana Cloud for execution
