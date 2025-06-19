# Certificate Manager Agent

## Overview

The **Certificate Manager Agent** is an AI-powered tool designed to manage and analyze certification data. It processes certification records from Excel files, converts them into a compatible format, and enables intelligent querying and comparison of certification offerings from various providers. The project integrates Azure AI Agent Service, Bing Search, and other tools to provide actionable insights.

## Features

- **Data Processing**: Converts Excel certification data into Markdown format for compatibility with Azure AI Agent Service.
- **Intelligent Querying**: Enables querying certification data using Azure AI Agent Service.
- **External Data Comparison**: Compares internal certification data with external sources using Bing Search.
- **Insights Extraction**: Highlights discrepancies and provides actionable insights.
- **Secure Environment**: Uses `.env` files to manage sensitive information like API keys and connection strings.


## Setup Instructions

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd certificate_manager_agent

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Configure environment variables:
- Create a `.env` file based on the provided `.env.example`.
- Add the following variables:
    - `PROJECT_CONNECTION_STRING`: URL for Azure AI Agent Service Project.
    - `AZURE_OPENAI_DEPLOYMENT`: Name of the Azure AI Agent Service model deployment.
    - `BING_CONNECTION_NAME`: Name of the Bing connection.
