<h3> Crash course in preparation for the LIDA Webinar: Building a Python Data Pipeline for Pricing Data </h3>
The workflow uses pricing data retrieved directly from the Azure API and illustrates how this information can be prepared for a tool that calculates Azure service costs.

- Crash course  - Azure section from [The 2026 FREE Data Analyst Bootcamp by Alex The Analyst](https://www.youtube.com/watch?v=cnjhHZNJEDk)
<h4>Part 01: Exploring Storage accounts in Azure </h4>
  <p> 
    <li> Alot of companies store data in Storage - it is a flexible way to store data.</li>
    <li> Possible to upgrade to data lake </li> 
  </p>
 - <P> Store upto 500TB of data in the cloud. Use a general-purpose storage account to store object data, use a NoSQL data store, define and use queues for message processing, and set up file shares in the cloud. Use the Blob storage account and the hot or cool access tiers to optimize your costs based on how frequently your object data is accessed.  </P>
 <p>Create storage account- for Region make sure to add the region where you or the client will be based in to have faster results </p>
 <p>Redundancy - The cloud will back up the storage so that incase any server is disrupted there will be access to the files. This option will choose the method of back up as per the level of data protection  </p>
-<p>Once created >> Storage browser >> Blob container </p></P>
 <p>Blob containers are used for structured , semi structured or unstructured data</p>
 <p>Select the blob container needed >> upload >> Select required access tier (Hot, Cool, Cold, Archive) depending on how often you will use the data </p>
 -<p>There is also access to Data Lakes through settings >> Data Lakes Gen 2 upgrade </p>
 -<p>Access control (IAM) - to give other people access +Add >> role assignment or co-admin assignment >> Select function, members</p>
 -<h5> Using SQL in Azure </h5>
 <p>Databases >> SQL Databases >> Create >> Resourse group, Database name >> Create server - Choose Authentication method MS Entra admin or SQL auth depending on the case >> set admin for Entra method >> SQL elastic pool (way to manage resources) - NO >> Workload environment - Development (Production will be faster ) >> review cost and create </p> 
 <P> Once deployment is completed  >> Go to resource >> Configure access to connect to SQL Databse <b>OR</b> Start developing >> Open Azure data Studio. Donwnload.</P>
 -<p>Once Azure Data Studio is dowloaded >> connect the server >> Servers -> Connection -> details -> go back to Azure and copy the server name, </p>
