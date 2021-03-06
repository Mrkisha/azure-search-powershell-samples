---
page_type: sample
languages:
  - powershell
name: Quickstart in REST - PowerShell
description: |
  Learn basic steps for creating, loading, and querying an Azure Cognitive Search index using the latest-version REST APIs and PowerShell cmdlets. 
products:
  - azure
  - azure-cognitive-search
urlFragment: powershell-rest-quickstart
---

# Quickstart sample for Azure Cognitive Search using REST APIs and PowerShell

![Flask sample MIT license badge](https://img.shields.io/badge/license-MIT-green.svg)

Demonstrates PowerShell cmdlets calling REST APIs to send requests to Azure Cognitive Search: create an index, load it with documents, and execute a few queries. 

This sample is a PowerShell script (.ps1) file used in [Quickstart: Create an Azure Cognitive Search index using PowerShell and the Cognitive  REST API](https://docs.microsoft.com/azure/search/search-get-started-powershell). It uses the [Invoke-WebRequest](https://docs.microsoft.com/powershell/module/microsoft.powershell.utility/invoke-webrequest?view=powershell-6) cmdlet and [Azure Cognitive Search REST APIs (api-version=2019-05-06)](https://docs.microsoft.com/rest/api/searchservice/).

## Contents

| File/folder | Description |
|-------------|-------------|
| `azure-search-quickstart.ps1` | PowerShell script, which you can run from the command line |
| `.gitignore` | Define what to ignore at commit time. |
| `CONTRIBUTING.md` | Guidelines for contributing to the sample. |
| `README.md` | This README file. |
| `LICENSE`   | The license for the sample. |

## Prerequisites

- [Windows PowerShell app](https://docs.microsoft.com/powershell/scripting/components/ise/introducing-the-windows-powershell-ise?view=powershell-6)
- [Azure Cognitive Search service](https://docs.microsoft.com/azure/search/search-create-service-portal)

## Setup

1. Clone or download this sample repository.
1. Extract contents if the download is a zip file. Make sure the files are read-write.

## Running the quickstart
1. Open the azure-search-quickstart.ps1 file in an editor
1. Replace <YOUR-SERVICE-NAME> and <YOUR-ADMIN-API-KEY> with the service and api-key details of your Azure Cognitive Search service
1. Open a PowerShell console, navigate to the file location, and run the script: `.\azure-search-quickstart.ps1`

## Next steps

You can learn more about Azure Cognitive Search on the [official documentation site](https://docs.microsoft.com/azure/search).