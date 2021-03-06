# openSAP SAP HANA Development HANA 2.0 SPS 03 October 2018 Revision or Higher

This repository is based on the exercises of openSAP training

	HANA7 Software Development on SAP HANA (Update Q1/2019)

URL: https://open.sap.com/courses/hana7

Resolutions are stored in the following GitHub repository provided by SAP:
    
    openSAP HANA7 Course Excercise Materials and Code Snippets for HANA 2.0 SPS 03 October Revision (or later)

URL: https://github.com/SAP-samples/hana-xsa-opensap-hana7/tree/snippets_2.3.2

# Environment

This repository is developed and tested in SAP HANA Express VM in the following configuration:

SAP HANA 2.0, express edition 2.0 SPS 04 2.00.045.00.1575639312
SUSE Linux Enterprise Server for SAP Applications 12 SP2OS Kernel Version 4.4.121-92.125-default
VMware Workstation Player 16.0.0-16894299

# Prerequisites

First and most important is to activate the HXE tenant database in XS Advanced Cockpit and map it to Organization HANAexpress and Space development with default option.

In order to build the repository the following prerequisites for exercise 2.6 and 2.8 need to be met:

See install-all-prerequisites.txt
Source-URL: https://github.com/mattxdev/opensap-hana7/blob/master/install-all-prerequisites.txt

# Exercises

## Exercise 1 - Hello World

- 1.1: HTML5 Module - Hello World with Security Implementation
- 1.2: Clone a Repository from Git

## Exercise 2 - Database Artifact Development

### Database Fundamental Artefacts

- 2.1: Database Content
- 2.2: Create Tables & Views via Core Data Services
- 2.3: Create Table Data Configuration
- 2.4: Create Tables & Views via SQL DDL Design Time Artifacts
- 2.5: Create Structured Privilege & Role

### Container Handling

- 2.6: Non-Container Schemas, User Provided Services & Synonyms
- 2.7: Cross Container Services & Synonyms
- 2.8: Cross Container From Outside Our Project

### Calculation Views

- 2.9: Creating a Calculation View with a Dimension data type
- 2.10: Creating a Calculation View with a Cube data type and Star Join
- 2.11: Table Function as Data Source in Calculation View
- 2.12: Importing Calcuation Views (and other native DB objects) into the new CDS

### SQLscript

- 2.13.1: Creating A Simple Stored Procedure
- 2.13.2: Create a Scalar User Defined Function
- 2.13.3: Create a Table User Defined Function
- 2.13.4: Libraries
- 2.13.4.1: Creating User Defined Libraries
- 2.13.4.2: Leveraging Built-In Libraries
- 2.13.6: Table Manipulation
- 2.13.6.1: Table Variable Operators
- 2.13.6.2: MAP_MERGE Operator
- 2.13.6.3: MAP_REDUCE Operator
- 2.13.7.2: Breaking on Error
- 2.13.8.4: SQLScript Analyzer

## EXERCISE 3 - XSJS AND XSODATA SERVICES

- 3.1: XSJS and XSODATA
- 3.3: Exploring JavaScript Language Features
- 3.4: Creating an XSJS Service with outbound HTTP Connectivity
- 3.5: User Provided Service as SQLCC
- 3.6: Creating a Simple Odata V2 Service
- 3.7: Creating an OData V2 Service with an Entity Relationship
- 3.8: Creating an Odata V2 Service with Create Operation and XSJS Exit
 
## EXERCISE 4 – NODE.JS

Troubleshooting CDS Build on SAP HANA Express VM based on HANA 2.0 SPS04:
Errors occurring on CDS Build as well as on running node.js application fixed by changing dependency to @sap/cds to "3.21.1" or "3.21.x" in package.json in app root as well as srv subfolder

Troubleshooting Error _addUrlAsLink when running xsjs and nodejs on SAP HANA Express VM based on HANA 2.0 SPS04:
Updating of node.js-Version and other dependencies in xsjs/package.json node to 10.x, xsjs to ^5.2.0, xsjs-test to ^3.1.2, xsenv to ^2.0.0

- 4.1: Odata V4 services
- 4.2: Modules and Express
- 4.3: HANA Database Access from Node.js
- 4.4: Asynchronous Non-Blocking I/O
- 4.5: Exploring JavaScript Language Features
- 4.6: Text Bundles
- 4.7: Open Source Modules -> Excel, ZIP, XML
- 4.8: JavaScript Object Oriented
- 4.9: Web Sockets -> Chat Application
- 4.10: Odata V4 Services with Exits


## EXERCISE 5 - SAPUI5/Fiori User Interface

- 5.1: SAPUI5 as an XSA Micro-Service
- 5.2: Creating a Text Bundle
- 5.3: SAPUI5 User Interface
- 5.4: Consume XSJS Services via JQuery AJAX calls
- 5.5: Consume a Basic OData V2 Service within SAPUI5 binding the service to a Table
- 5.6: Use oData V2 Metadata to dynamically create the columns.
- 5.7: Consume an OData V2 Service with Create Option
- 5.8: OData V2 Batch Operation
- 5.9: OData V2 Deep Insert (Content-ID and Links) (Does not work due to CSRF)
- 5.10: OData V4 and Fiori Annotations (Does not show Purchase Order Column Headers)
- 5.11: Consume an OData V4 Service with Create Option
