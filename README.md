# Chat-with-your-Cyber-Threat-Intelligence-data-with-Azure-OpenAI
Chat with your Cyber Threat Intelligence data with Azure OpenAI

Use case description.
The goal is to develop a chatbot using Azure OpenAI to engage in conversations with your intelligence data sourced from Microsoft Defender Threat Intelligence (MDTI). I've leveraged SharePoint Online as a document repository to programmatically and automatically ingest MDTI articles, indicators, and threat actor profiles. This automation harnesses MDTI APIs invoked by Azure Logic App.
By utilizing an Azure OpenAI instance and deploying a GPT-4 model, I've created a straightforward web application for conversing with the gathered threat intelligence data. Please note that this is a specific use case that involves the availability of MDTI (which can be enabled for trial, as described here). Alternatively, or to expand the use case, you can incorporate intelligence data from any source, such as OSINT, cybersecurity vendors, community sources, email data, national CERTs, and more.
The strength of Large Language Models (LLMs) lies in their proficiency with unstructured data and files in multiple formats. Particularly with Azure OpenAI, you can be assured of secure data management, ensuring that data is not shared with any external parties and aligning with privacy regulations and international standards

To upload this playbook in Azure please follow the below instructions:
- From the Azure portal menu, in the search box, type Template, and then select Templates
- Select +Add and give it a Name and Description
- copy and paste the json file in the previous folder in the ARM template layout.
- click add
- your logic app is created and ready to be deployed


Thank you!

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fformat81%2FMicrosoftSentinel-AzureOpenAI-IR-helper-playbook%2Fmain%2Fazuredeploy.json" target="_blank">
    <img src="https://aka.ms/deploytoazurebutton"/>
</a>
<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fformat81%2FMicrosoftSentinel-AzureOpenAI-IR-helper-playbook%2Fmain%2Fazuredeploy.json" target="_blank">
<img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazuregov.png"/>
</a>


