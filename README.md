# DocSort

DocSort is an intelligent document processing and routing platform designed to automate the classification and distribution of uploaded documents.

The system accepts documents from users, extracts relevant content, classifies the document based on its context, identifies the appropriate department, and routes the document accordingly. The platform is designed primarily for administrative and government-oriented document workflows.

---

## 1. Project Overview

In traditional document management systems, documents are often reviewed and manually forwarded to the appropriate department. This process can be time-consuming and may result in incorrect routing or delays.

DocSort aims to automate this workflow by introducing a document processing pipeline:

## flow chart

![flow chart](<./asset/flowchart.png>)

---

## 2. Objectives

The primary objectives of DocSort are:

- Automate document classification.
- Extract useful information from uploaded documents.
- Identify the appropriate department for each document.
- Reduce manual document routing.
- Maintain document processing and routing status.
- Provide role-based access to users and departments.
- Maintain an audit trail of important system activities.
- Provide a scalable architecture for future deployment.

---

## 3. Core Features

### Document Upload

Users can upload supported documents through the web application.

The backend performs:

- File type validation.
- File size validation.
- File naming and storage management.
- Request validation.
- Authentication and authorization checks.

### Text Extraction

The system extracts textual information from documents.

Possible processing methods include:

- PDF text extraction.
- OCR for scanned documents.
- Text cleaning.
- Text normalization.

### Document Classification

The extracted text is passed to a classification component that determines the document category.