# Azure_Document_Intelligence
This repository contains a Jupyter Notebook that demonstrates how to utilize Azure's Document Intelligence and Blob Storage services for automated document analysis and processing. The notebook walks through the installation of necessary packages, setting up Azure credentials, and performing operations like document analysis using Azure's form Recognizer.


# Azure Document Intelligence

This repository contains a Jupyter Notebook that demonstrates the use of Azure Cognitive Services, specifically focusing on Azure's Document Intelligence capabilities. The notebook is designed to help users automate the analysis and processing of documents, including extraction of structured information like invoices, receipts, and more.

## Features

- **Azure Form Recognizer:** Utilize Azure's powerful form recognizer API to analyze documents.
- **Azure Blob Storage Integration:** Seamlessly upload and manage documents in Azure Blob Storage.
- **Automated Document Processing:** Automatically extract structured data from various document formats.

## Prerequisites

Before you begin, ensure you have the following:

- An active [Azure subscription](https://azure.microsoft.com/en-us/free/).
- Azure Cognitive Services API key and endpoint.
- Azure Blob Storage account credentials.

## Installation

To get started with the notebook, install the required Python packages:

```bash
pip install azure-storage-blob azure-identity
pip install azure-ai-formrecognizer
