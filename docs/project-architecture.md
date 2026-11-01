# Project Architecture

## Overview

The AICTE Smart FDR Compliance & Intelligence Portal follows a proposed multi-layer architecture designed to manage FDR documents, automate document processing and support compliance monitoring.

## 1. Presentation Layer
**Technology:** React.js / Next.js

- Institution dashboard
- AICTE officer dashboard
- FDR document upload interface
- Application status tracking
- Compliance monitoring dashboard

## 2. Backend Layer
**Technology:** Node.js

- User authentication
- Application management
- Document processing requests
- FDR record management
- API communication

## 3. AI Processing Layer
**Technologies:** Azure OpenAI, Azure AI Search, Azure Document Intelligence

- OCR-based document extraction
- Document information analysis
- Automated validation support
- AI-generated summaries
- Natural-language compliance assistance

## 4. Database Layer
**Technology:** PostgreSQL

Proposed records:
- User details
- Institution details
- FDR information
- Application status
- Renewal records
- Release requests

## 5. Cloud Storage Layer
**Technology:** Azure Blob Storage

- Uploaded FDR PDF storage
- Document retrieval
- Secure document management

## System Workflow

Institution → FDR Upload → AI Document Extraction → Automated Validation → Officer Review → Approval / Rejection → Expiry Monitoring → Renewal / Release Request

## Architecture Status

This document describes the proposed system architecture. Actual implementation and integrations will be added during development.<img width="1536" height="1024" alt="AICTE Smart FDR Portal Architecture" src="https://github.com/user-attachments/assets/06695fbb-9f8d-4cf0-9d25-87d23cdc4902" />
<img width="1536" height="1024" alt="AICTE Smart FDR Portal Architecture" src="https://github.com/user-attachments/assets/8eaaef4b-5ea8-4883-95e7-119ace9d5370" />
