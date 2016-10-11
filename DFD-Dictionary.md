# Data Flow Diagram Dictionary

*The definitions of all the entities, processes, databases, and data flows used in the DFD.*

## ENTITIES

**Developer:** An individual responsible for coding main software packages and preparing for the license scan

**Manager:** An individual resposnible for modifying and submitting software packages

## PROCESSES

**Managing Software Package for License Scanning:** A process that checks for OSS files in the software package

**Scan Licenses:** A process that scans for licenses that can be found

**Retrieve OSS Software Components:** A process that retrieves OSS Components based on requests from Manager and Developer

**Violations in Policies:** A process that documents violations and sends them to the Manager

**Modify OSS Policy Documents:** A process that allows the Manager to update the documents

## DATABASES

**NIST Vulnerbility Database:** Database that contains any vulnerbilities in the software package

**OSS Components Database:** Database that stores the software package information

**OSS Policy Documents Database:** Database that contains the OSS policy documents


## DATAFLOWS

**Software Package:** Collection of software files

**Software Package Name:** Name of the software package

**Known Vulnerbility Issues:** Known vulnerbility issues of the software package

**Software Package License Results:** License information for the software package

**Software Package License and Vulnerbility Results:** License information and known or documented vulnerbility issues of the software package

**OSS Software Components:** Information about the OSS software components

**OSS Software Components Request:** Stored in the OSS Software Components Database

**OSS Software Component Violations:** Documented violations in the OSS software component

**Confirm Updates on OSS Policy Docs:** Confirmation of violations done by Manager

**Update OSS Policy Docs:** Modified OSS policy documents done by Manager

