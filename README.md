# DataOps Starter Kit


### Contents

1. [What is DataOps](#what-is-dataops)
2. [DataOps Landscape](#dataops-landscape) 
3. [DataOps Lifecycle - Conceptual View](#dataops-lifecycle)
4. [DataOps Starter Kit Overview](#starter-kit-overview)
5. [DataOps Foundation Approach and How-to Guides](#dataops-foundation-approach)
6. [DataOps Starter Kit Roadmap](#starter-kit-roadmap)
7. [Contributors](#dataops-contributors)

### What is DataOps?<a class="anchor" id="what-is-dataops">

DataOps (data operations) is the orchestration of people, processes, and technology to deliver trusted, business-ready data to data citizens, operations, applications and artificial intelligence (AI) fast. IBM DataOps (formerly known as Unified Governance and Integration) enables agile data collaboration driving speed and scale of operations and analytics throughout the data lifecycle. IBM Cloud Pak for Data, an all-in-one cloud-native data and AI platform, enables you to take advantage of a broad set of DataOps capabilities and integrate them quickly into applications to accelerate innovation. From solutions that facilitate governing data lakes to application development to ensuring regulatory compliance.

**DataOps Starter Kit for data governance using Watson Knowledge Catalog feature**

Data governance is the overall management of data availability, relevancy, usability, integrity and security in an enterprise. It helps organizations manage their information knowledge and answer questions, such as:

+ What data do we have?
+ What do we know about our information?
+ Where does different datasets come from?
+ Does this data adhere to company policies and rules?
+ What is the quality of our data?

This starter kit provides a prescriptive way to approach data governance initiatives in any organization from setting up foundational capability including governance organizational structure (People), governance workflows (Processes) and curation of data assets using automated features and functions (Technology).

### DataOps Landscape<a class="anchor" id="dataops-landscape">

![](Images/GovernedDataOpsAssets_v3.x.jpg)

DataOps as initiatives drives multiple focused business outcomes. The organization's priorities would typically dictate the starting points for a DataOps initiative. The DataOps Foundation is a requirement for any of the other intititives as they all rely on a strong foundation and Enterprise Catalog with metadata that help drive the rest of the requirements. 

#### Governance Foundation
This asset provides the starting point for DataOps and Data Governance. A solid technical platform combined with people and processes is key to any further work on any of the below focus areas. The DataOps Foundation asset provides best practices and technical details on how to build and operate an Enterprise Catalog using Watson Knowledge Catalog on Cloud Pak for Data 3.5. The typical discussion points revolve around metadata management for source systems on relational database systems, Data Virtualization on Cloud Pak for Data and file systems, how to import and maintain metadata, how to discover data, how to build and maintain a Business Glossary and the workflows surrounding those processes.

#### Shop for Data and Self-service
To simplify the Shop for Data and self-service use cases, there are additional measures to take. This asset provides a starting point for enriching the Enterprise Catalog with the necessary metadata in order to further simplify the searching for, exploration and understanding data and how to continue working with data with Cloud Pak for Data.

#### Governed Virtual Data Lake
Deploying a Data Virtualization layer on Cloud Pak for Data simplifies access to data and makes it possible to start working with data without moving it upfront. It also provides a secure layer integrated with Watson Knowledge Catalog that enforces centrally created and maintained Data Protection Rules. This enables any client to connect to Cloud Pak for Data in a secure way, masking and denying access to sensitive data. The asset includes best practices and examples of how to set up DataOps principles for Data Virtualization in combination with the Enterprise Catalog.

#### Regulatory Compliance
Another typical focus area in DataOps and Data Governance is the capability to uncover where sensitive data is stored. This asset includes creating data classes that identify sensitive data, running data profiling jobs to find it and reporting the results for further analysis.

#### Data Quality
This asset contains best practices and technical details on the end-to-end flow for Enterprise Data Quality on Cloud Pak for Data. It includes how to define Data Quality metrics using Watson Knowledge Catalog, how to run Data Quality jobs and how to report the Data Quality exceptions.


### DataOps Lifecycle<a class="anchor" id="dataops-lifecycle">

![](Images/DataOps_Lifecycle.png)

This starter kit provides a framework and guidelines for end-end journey of DataOps initiatives. Each use case of entry points for DataOps initiative includes these phases:
+	Scoping the DataOps initiative. Start with understanding of the goals and current landscape and then prioritize a minimum viable product ( a MVP) that can be achieved within time available/allocated
+	Identify and setup foundational artifacts required for a given MVP sprint ( an iteration of a build cycle)+	Build the supporting processes, workflows required to achieve the MVP goal
+	Validate and iterate as needed to refine the processes and artifacts to reach desired level of accuracy/completeness
+	Publish the results for consumption by end-users and groups

+	Measure the effectiveness of the initiative through periodic KPI/reports 




### DataOps Starter Kit Overview<a class="anchor" id="starter-kit-overview">

![](Images/Screen%20Shot%202020-07-09%20at%2012.18.54%20PM.png)

The DataOps Starter kit made up of setup of documents that describe the framework to approach the initiative along with samples and procedures. Many initiative will need only WKC assembly installed but some may need additional features installed such Data Virtualization, DataStage and Regulatory Accelerator.



### DataOps Foundation Approach and How-to Guides<a class="anchor" id="dataops-foundation-approach">

The catalog foundation initiative can be achieved using a 7 step framework.Each step of the initiative is captured in the following documents:

1. DataOps Assessment and Initial Scope
2. Define Governance Workflow:[Create and Activate Governance Workflows](How-to_Guides/1.%20Create%20and%20Activate%20Governance%20Workflows)
3. Create Initial Governance Artifacts: [Initial Glossary Import](How-to_Guides/2.%20Initial%20Glossary%20Import)
4. Run Quick Scan to Preview Available Assets:[Run and Review Quick Scan](How-to_Guides/3.%20Run%20and%20Review%20Quickscan)
5. Refine and Enrich Governance Artifacts:[Review and Enrich Glossary](How-to_Guides/4.%20Review%20and%20Enrich%20Glossary)
6. Run Auto Discovery for Initial Auto-assignments: [Auto Discovery and Review](How-to_Guides/5.%20Auto-Discovery%20and%20Review)
7. Review and Refine Cataloged Data Assets: [Adjustring Auto Discovery Results](How-to_Guides/6.%20Adjusting%20Auto%20Discovery%20Results) & [Validation of Auto Discovery with Addditional Assets](How-to_Guides/7.%20Validation%20of%20Auto%20Discovery%20with%20Additional%20Data%20Assets)


### DataOps Starter Kit Roadmap<a class="anchor" id="starter-kit-roadmap">

This starter kit currently includes Catalog Foundation initiative. This git will be updated with following focus areas in next few weeks:

1. **Wave 1:** Data Catalog Foundation
2. **Wave 2:** Enterprise Data Compliance Goal
3. **Wave 3:** Data Quality
4. **Wave 4:** Business Lineage
5. **Wave 5:** Self-Service Data

### Contributors<a class="anchor" id="dataops-contributors">
    
+ [Mallika Razdan](https://www.linkedin.com/in/mallika-razdan-766672b4/)
+ [David Aspegren](https://www.linkedin.com/in/davidaspegren/)
+ [Sanjay Srivastava](https://www.linkedin.com/in/sanjay-srivastava-8901142b/)
+ [Sandip Mahajan](https://www.linkedin.com/in/sandip-mahajan-25071982/)
+ [Prakash Raja](https://www.linkedin.com/in/prakash-raja-a3b76615)
+ [Vishwanath(Vish) Kamat](https://www.linkedin.com/in/vishwanathkamat/)


