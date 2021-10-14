# Project Title
Analisi chimica di campioni biologici - Chemical analysis of biological samples

# Project Description
The system handles the requests for chemical analysis submitted by the citizen or a technical delegate to the regional analysis laboratories, allowing the laboratories to record the analisys results. The system is set up for the payment of the submitted requests with the payment system of the public administration PagoPA through another project of CSI Piemonte, which can be provided on request.

# Getting Started
The AGRICHIM product is composed of the following components:
- [AGRCFO](https://github.com/regione-piemonte/agrichim-agrcfo) (front office web application that allows the registration and submission of the required analyzes)
- [AGRCBO](https://github.com/regione-piemonte/agrichim-agrcbo) (back office web application that allows the regional laboratories the registration of the analyzes results)
- [AGRICHIMDB](https://github.com/regione-piemonte/agrichim-agrichimdb) (script for creating and maintaining the proprietary DB)
- [AGRICHIMDB](https://github.com/regione-piemonte/agrichim-agrichimpl) (script for defining stored procedures and functions)

# Prerequisites
The prerequisites for installing the components are as follows:
## Software
- [JDK 8](https://www.apache.org)
- [Apache 2.4](https://www.apache.org)
- [RedHat JBoss 6.4 GA](https://developers.redhat.com)  
- [PostgreSQL 9.2](https://www.oracle.com)  

- All libraries listed in the BOM.csv file must be accessible to build the project. The libraries are published on http://repart.csi.it, but for simplicity they have been included in the /lib of each individual component, with the exception of the weblogic-client-3.1.0.jar library, which is used by the components AGRCFO and AGRCBO must be downloaded independently from the Oracle website.

# Versioning
Git is used for managing the source code. For versioning management, reference is made to the [Semantic Versioning](https://semver.org) methodology.

# Copyrights
(C) Copyright 2021 Regione Piemonte

# License
This so
This software is distributed under the EUPL-1.2 license.
See the files EUPL v1_2 IT-LICENSE.txt and EUPL v1_2 EN-LICENSE.txt for more details.
