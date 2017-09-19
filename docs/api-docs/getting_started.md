---
layout: default
title: API Basics
nav: basics
---

### Getting Started

The current version of the API lives at ```https://api.gsa.gov/operations/signature/Packages/```.

- TODO One example of a way to use it.
- TODO Another example of a way to use it.

#### Versions

| Version | Date | Changes
| ------------- | -------------|
| ```version 1``` | 1/1/2095 | TODO Initial deployment
| ```version 2``` | 3/1/2096 | TODO Changed data structure to fit congressional mandate
| ```version 3``` | 3/1/2099 | TODO Request pattern changed for new requirements

#### Endpoints

| Endpoint | What it does |
| ------------- | -------------|
| ```/package/Document/{packageId} {orgName} {documentId}``` | Retrieves a Document from Package
| ```/package/retrieve/{packageId} {orgName}``` | Retrieves Package Documents
| ```/Packages/CreateWithDocumentLayout``` | Creates a Package from a document layout and returns success or failure response
| ```/Packages/CreateWithDocumentLayoutMultipart``` | Creates Package from a document layout using multipart file transfer and returns success or failure response
| ```/Packages/Create``` | Creates Package and returns success or failure response
| ```/Packages/CreateMultiPart``` | Creates Package using multipart file transfer and returns success or failure response

<body id="basics"></body>
