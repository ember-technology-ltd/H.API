# H.API Getting started Guide

The Heritage Gateway provides three distinct options for data submission/retreavel of HGR standard compliant records into the gateway, offering these three approaches caters to both technical and non-technical users. 

The first approach, the Direct API Submission, requires some Technical Resource to be deployed on the partners side to write an integration which will upload HGR standard compliant data directly into the system though a RESTFul API. This approach allows for files to be submitted from any system that can accomodate an API request from the system. 

The second approach, External API Harvesting, operates as an automated retrieval process, fetching HGR compliant records from external sources at scheduled intervals. This method involves the partner providing Historic England with access to the HGR compliant data through an API that we can then use to fetch the data on an agreed schedule. If you have an API available already then all you need to do is send us details of that API. 

The third approach, FTP Server Access, offers a more traditional route, resembling a familiar file-sharing system. Here, partners, irrespective of technical expertise, can upload HGR compliant data files onto the server periodically. It’s a simple and effective means for data contribution and can be done either manually, by non-technical users, or using a technical reource to develop functionality into  your existing system to send the HGR standard compliant data automatically on scheduled intervals. 

Together, these varied approaches cater to diverse user preferences and provides options for an easy integration of HGR Standard Compliant records into the Gateway. 

## Direct API Submission

Full details of the available API are contained here https://github.com/ember-technology-ltd/H.API/blob/master/FileUploadDocumentation.md.  To get access to the API you need to be setup with an account on the gatway, this can be requested by sending an email to the email address heritagegateway@HistoricEngland.org.uk containing your name, organisation and reason for the access request. 

### Instructions 

#### Access the API Documentation:
+	Visit the provided Historic England API documentation here https://github.com/ember-technology-ltd/H.API/.
+	Read through the guidelines, endpoints, and data submission procedures outlined in the documentation.

#### Obtain Access Credentials:
+	Contact Historic England's support team or designated personnel to acquire your access credentials through XXXXXX@XXXX@XXXX 
+	Follow the outlined procedure to authenticate and obtain an access token required for data submission.

#### Prepare Your Data:
+	Organize your data according to the specified format detailed in the API documentation.
+	Ensure your data structure aligns with the provided example or schema.

#### Submit Your Data:
+	Use tools like cURL or Postman to interact with the API endpoints.
+	Authenticate using the obtained access token and follow the documented steps to submit your prepared data.

### Verify Submission:
+	Check the API response for confirmation of successful submission.
+	Confirm that your data is accessible and accurately represented within the system.

## External API Harvesting:

#### Identify the External API:
+	Locate and access the external API that contains the necessary data.
+	Review the API documentation thoroughly to understand available endpoints and data retrieval methods.

### Determine Data Retrieval Intervals:
+ Plan and set intervals (e.g., hourly, daily) for gathering data from the external API.
Consider scheduling tools or scripting languages (like Python) for automated data retrieval.

### Develop Integration:
+	Use programming languages or tools to create a script that interacts with the external API endpoints.
+	Write code to fetch, process, and store the retrieved data at your specified intervals.

### Test and Monitor:
+	Execute the integration to ensure it fetches data accurately and consistently.
+	Monitor the process regularly to detect any issues and ensure continuous and error-free data retrieval.

## FTP Server Access for File Uploads:

### Get Started Guide:
+	Access the Provided FTP Server:
+	Gather the FTP server details, including the URL, username, and password, provided by Historic England.
+	Use an FTP client application (e.g., FileZilla) or a web browser supporting FTP access to connect to the server.

### Prepare Your Data Files:
+	Organize your data into the required file formats specified by Historic England.
+	Ensure your files comply with any specified formatting guidelines or file naming conventions.

### Upload Your Data:
+	Open your FTP client and enter the server details (host, username, password) to establish a connection.
+	Navigate to the designated folder or directory and upload your prepared data files using the FTP client interface.

### Confirmation and Monitoring:
+	Verify successful file uploads by checking the uploaded files' presence in the specified folder on the server.
+	Monitor the upload process periodically to ensure continuous and error-free submission of data files.

