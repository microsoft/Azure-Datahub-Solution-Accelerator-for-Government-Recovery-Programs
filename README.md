---
page_type: sample
languages:
- python
products:
- azure-synapse-analytics
- power-bi
---



![DatahubforGovernment](./Deployment/img/DatahubforGovernment.png)

# Azure Datahub Solution Accelerator for Government Recovery Programs
Governments run many programs in parallel and track metrics around each program's initiatives, success, budget, and more simultaneously.  Measuring the success and status of programs internally and increasing the transparency of that information externally is a challenge that many governments are looking to solve.

This solution enables governments (local and/or state) to bring program data into one location, visualize key information in a dashboard, and then share the information with stakeholders.


## Prerequisites
To use this solution accelerator, you will need access to an [Azure subscription](https://azure.microsoft.com/free/). While not required, a prior understanding of Azure Synapse Analytics and Power BI will be helpful.


For additional training and support, please see:

1. [Azure Synapse Analytics](https://azure.microsoft.com/en-us/services/synapse-analytics/) 
2. [Power BI](https://docs.microsoft.com/en-us/power-bi/)

## Getting Started
Start by deploying the required resources to Azure. The button below will deploy Azure Synapse Analytics, Azure Data Lake Storage and its related resources:

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmicrosoft%2FAzure-Datahub-Solution-Accelerator-for-Government-Recovery-Programs%2Fmain%2FDeployment%2Fdeploy.json)


* Go to the [Deployment guide](./Deployment/Deployment.md) to set up your Azure resources for this solution.  

## Architecture

The architecture diagram below details what you will be building for this Solution Accelerator.

![Government Data Hub](./Deployment/img/GovernmentDataHubSAArchitecture.png "Government Data Hub")

## Power BI Dashboards

The summary dashboard shows the main problem areas that are faced by a region and the list of programs the government is running to address those problems. 

![Government Recovery Programs Overview](./Deployment/img/GovDataHubOverview.png "Government Recovery Programs Overview")

The Rent and Utility Relief detail dashboard shows the metrics about the program and the program's participants. 

![Government Recovery Programs Detail Page](./Deployment/img/GovDataHubRentRelief.png "Government Recovery Programs Rent Relief")

The Small Business Innovation Assistance detail dashboard shows the metrics about the program and the program's participants. 

![Government Recovery Programs Detail Page](./Deployment/img/GovDataHubSmallBusiness.png "Government Recovery Programs Small Business")

The Daycare Grant Program detail dashboard shows the metrics about the program and the program's participants. 
![Government Recovery Programs Detail Page](./Deployment/img/GovDataHubDaycare.png "Government Recovery Programs Daycare")

## License
MIT License

Copyright (c) Microsoft Corporation.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE


## Contributing
This project welcomes contributions and suggestions.  Most contributions require you to agree to a Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks
This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft trademarks or logos is subject to and must follow [Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general). Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship. Any use of third-party trademarks or logos are subject to those third-party's policies.

## Data Collection
The software may collect information about you and your use of the software and send it to Microsoft. Microsoft may use this information to provide services and improve our products and services. You may turn off the telemetry as described in the repository. There are also some features in the software that may enable you and Microsoft to collect data from users of your applications. If you use these features, you must comply with applicable law, including providing appropriate notices to users of your applications together with a copy of Microsoft's privacy statement. Our privacy statement is located at https://go.microsoft.com/fwlink/?LinkID=824704. You can learn more about data collection and use in the help documentation and our privacy statement. Your use of the software operates as your consent to these practices.

