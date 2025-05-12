# Integrating Cisco Secure Endpoint into Microsoft Sentinel
## Table of contents
- [Introduction](#intro)
- [API Credentials](#step1)
- [Regions](#step2)


  <a name="intro">

## Introduction
The Cisco Secure Endpoint (formerly AMP for Endpoints) data connector provides the capability to ingest Cisco Secure Endpoint audit logs and events into Microsoft Sentinel.

<a name="step1">
   
## API Credentials
Follow the below procedure to create API credentials in your Cisco Secure Endpoint account.
- Login into your Cisco Secure portal.
- Once your login is successfull, you will be directed to the Dashboard page of your organization.
- On the left hand side you will find different sections. Under these sections go to Administration, there you will find API Credentials.
- Once you land on API credentials page, you can see New API credential under Legacy API Credentials (version 0 and 1).
- Click on New API Credential, you will see a pop up to fill the details. Give any name of your choice and click on create.
- You can see the API Key details. Save these fields somewhere safe as the API credentials are not stored in plain text and can only be displayed once. If you lose the credentials you will have to generate new ones.

<a name="step2">
   
## Regions
We have 3 regions for Cisco Secure Endpoint.
- North America (NA) - https://api.amp.cisco.com
- Europe (eu) - https://api.eu.amp.cisco.com
- Asia Pacific, Japan, China (APJC) - https://api.apjc.amp.cisco.com
- You can connect to the region you prefer if you have an account as per respective region.

**NOTE:**  While connecting the connector make sure to give only the region part, like if you are connecting to APJC region then **apjc.amp** needs to given in the field provided in the context pane. Similar for europe it is **eu.amp** and for NA it is **amp**.

