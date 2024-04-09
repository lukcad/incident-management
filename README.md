# incident-management

## Overview

Welcome to great examples from SAP about managing incidents that we can really meet in our business life.

So lets consider this project as a great example to study SAP CAP for development on local machine using:

* VS code studio as development tool.
* [caplukcadhf](https://github.com/lukcad/caplukcadhf) as a development container.
* SAP BTP as a hana and xsuaa services for hybrid environment of our solution.

## Goal

  Using steps below you can transform this project which was done by SAP BTP by SAP BAS to your local project which will work by VS code by described steps below.
  Finally you will be able run this project in VS Code by two servers:

  - CDS server:

    		cds w

	or

      		cds w --profile hybrid

 - Router server:

  		cds bind --exec -- npm start --prefix app/router


   Locally in VS code you will be able to work with applicaiton via router server using endpoint:

   		http://localhost:5000
  

			
## Steps to go:

![image](https://github.com/lukcad/incident-management/assets/22641302/63c7daf5-a530-4a24-8803-1ffb6eb91df3)

  


## Learn More

Learn more at https://cap.cloud.sap/docs/get-started/.
