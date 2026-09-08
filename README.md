# Purchase-Requisition-Approval
## Project Overview

The **Purchase Requisition Approval** project is developed using **SAP ABAP RESTful Application Programming Model (RAP)**.

The purpose of this project is to create and manage Purchase Requisition (PR) information in an SAP system. The application allows users to create, view, update, and delete purchase requisition records through a **Fiori Elements user interface**.

The project demonstrates how a business application can be developed using the RAP programming model with CDS Views, Behavior Definitions, Service Definitions, and OData V4 Service Bindings.

## Business Purpose

A Purchase Requisition is used to request materials or services required by a department or business unit.

In this application, users can maintain important PR information such as:

- PR Number
- Requester
- Department
- Required Date
- Material
- Quantity
- Approval Status
- Approved By
- Approval Date

The application provides a simple way to maintain and track Purchase Requisition records and their approval status.



## Technologies Used

- SAP ABAP
- SAP RAP (RESTful Application Programming Model)
- ABAP CDS
- ABAP Cloud
- Eclipse ADT
- SAP Fiori Elements
- OData V4
- SAP HANA Database
- Managed RAP BO

## Development Environment

The project was developed using:

**Eclipse ADT (ABAP Development Tools)**

The application uses the RAP framework to expose business data through an OData V4 service and provide a Fiori Elements-based UI.

# Project Architecture

The overall architecture of the project is:


Database Table
      |
      v
CDS Root View
      |
      v
Behavior Definition
      |
      v
Projection CDS View
      |
      v
Projection Behavior
      |
      v
Service Definition
      |
      v
Service Binding
      |
      v
OData V4
      |
      v
Fiori Elements UI
##Project Outcome
The final result is a working Purchase Requisition Approval Form where business users can enter PR information, save the form, maintain approval details, and manage the resulting records through the Fiori Elements interface.
