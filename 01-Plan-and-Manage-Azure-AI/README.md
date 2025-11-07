# Plan and Manage Azure AI Solution (20–25%)

This domain covers the foundational aspects of planning, creating, deploying, and managing Azure AI solutions using Azure AI Foundry services.

## 📚 Official Microsoft Documentation

### Azure AI Foundry Overview
- [What is Azure AI Foundry?](https://learn.microsoft.com/en-us/azure/ai-foundry/what-is-azure-ai-foundry)
- [Azure AI Foundry rollout across my organization](https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/planning)
- [Quickstart: Set up your first AI Foundry resource](https://learn.microsoft.com/en-us/azure/ai-services/multi-service-resource)

### Resource Management
- [Azure AI Foundry resource types](https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/resource-types)
- [Role-based access control in Azure AI Foundry](https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/rbac-azure-ai-foundry)
- [Plan and manage costs for Azure AI Foundry](https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/costs-plan-manage)

## 🎯 Key Topics

## Select the appropriate Azure AI Foundry services
- **Select the appropriate service for a generative AI solution**: [Explore Azure AI Foundry Models](https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/foundry-models-overview), [What is Azure AI Foundry?](https://learn.microsoft.com/en-us/azure/ai-foundry/what-is-azure-ai-foundry)
- **Select the appropriate service for a computer vision solution**: [Azure AI Vision](https://learn.microsoft.com/en-us/azure/ai-services/computer-vision/overview), [Choose an Azure AI image and video processing technology](https://learn.microsoft.com/en-us/azure/architecture/data-guide/ai-services/image-video-processing)
- **Select the appropriate service for a natural language processing solution**: [Azure AI Language](https://learn.microsoft.com/en-us/azure/ai-services/language-service/overview), [Natural language support for Azure AI services](https://learn.microsoft.com/en-us/azure/ai-services/language-support)
- **Select the appropriate service for a speech solution**: [Azure AI Speech](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/overview), [Speech Service capabilities](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/overview)
- **Select the appropriate service for an information extraction solution**: [Azure AI Document Intelligence](https://learn.microsoft.com/en-us/azure/ai-services/document-intelligence/overview), [Azure AI Content Understanding](https://learn.microsoft.com/en-us/azure/ai-services/content-understanding/overview)
- **Select the appropriate service for a knowledge mining solution**: [Azure AI Search](https://learn.microsoft.com/en-us/azure/search/search-what-is-azure-search)

## Plan, create and deploy an Azure AI Foundry service
- **Plan for a solution that meets Responsible AI principles**: [Responsible AI in Azure AI Foundry](https://learn.microsoft.com/en-us/azure/ai-foundry/responsible-ai/openai/overview), [Responsible AI in Azure workloads](https://learn.microsoft.com/en-us/azure/well-architected/ai/responsible-ai)
- **Create an Azure AI resource**: [Create an Azure AI Foundry resource](https://learn.microsoft.com/en-us/azure/ai-services/multi-service-resource), [Create and deploy an Azure OpenAI resource](https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/create-resource)
- **Choose the appropriate AI models for your solution**: [Azure AI Foundry model catalog](https://ai.azure.com/catalog/publishers), [Azure AI Foundry Models](https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/how-to/quickstart-create-resources)
- **Deploy AI models using the appropriate deployment options**: [Deploy models in Azure AI Foundry](https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/deployments-overview), [Deploy a model](https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/create-resource#deploy-a-model)
- **Install and utilize the appropriate SDKs and APIs**: [Azure AI services SDKs](https://learn.microsoft.com/en-us/azure/ai-services/reference/sdk-package-resources?pivots=programming-language-csharp), [Azure AI Foundry API and SDKs](https://learn.microsoft.com/en-us/azure/ai-services/reference/sdk-package-resources?context=%2Fazure%2Fai-foundry%2Fcontext%2Fcontext&pivots=programming-language-python)
- **Determine a default endpoint for a service**: [Azure AI Model Inference API](https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/concepts/endpoints?source=recommendations&tabs=python), [Endpoints and keys](https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/concepts/endpoints?tabs=python)
- **Integrate Azure AI Foundry Services into a continuous integration and continuous delivery (CI/CD) pipeline**: [Continuous integration and deployment](https://learn.microsoft.com/en-us/azure/ai-services/what-are-ai-services#development-options), [CI/CD pipelines](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/cloud-scale-analytics/manage#ci-cd-pipelines)
- **Plan and implement a container deployment**: [Azure AI services containers](https://learn.microsoft.com/en-us/azure/ai-services/cognitive-services-container-support)

## Manage, monitor, and secure an Azure AI Foundry Service
- **Monitor an Azure AI resource**: [Monitor your Generative AI applications](https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/monitor-applications)
- **Manage costs for Azure AI Foundry Services**: [Plan and manage costs for Azure AI Foundry](https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/costs-plan-manage), [Azure AI services pricing](https://azure.microsoft.com/en-gb/pricing/details/cognitive-services/#pricing)
- **Manage and protect account keys**: [Azure AI services authentication](https://learn.microsoft.com/en-us/azure/ai-services/authentication), [Customer-managed keys for encryption with Azure AI Foundry (Foundry projects)](https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/encryption-keys-portal)
- **Manage authentication for an Azure AI Foundry Service resource**: [Authentication in Azure AI services](https://learn.microsoft.com/en-us/azure/ai-services/authentication), [Azure AI Foundry security](https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/planning#securing-the-ai-foundry-environment)

## Implement AI solutions responsibly
- **Implement content moderation solutions**: [Azure AI Content Safety](https://learn.microsoft.com/en-us/azure/ai-services/content-safety/), [Content Safety in Azure AI Foundry](https://learn.microsoft.com/en-us/azure/ai-foundry/ai-services/content-safety-overview)
- **Configure responsible AI insights, including content safety**: [Content filtering in Azure AI Foundry](https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/content-filtering)
- **Implement responsible AI, including content filters and blocklists**: [Configure content filters](https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/content-filters), [Content filter configurability](https://learn.microsoft.com/en-us/azure/ai-foundry/openai/concepts/content-filter-configurability)
- **Prevent harmful behavior, including prompt shields and harm detection**: [Prompt Shields](https://learn.microsoft.com/en-us/azure/ai-services/content-safety/concepts/jailbreak-detection), [Prompt shields content filtering](https://learn.microsoft.com/en-us/azure/ai-foundry/openai/concepts/content-filter-prompt-shields)
- **Design a responsible AI governance framework**: [Responsible AI governance framework](https://learn.microsoft.com/en-us/azure/ai-foundry/responsible-ai/openai/overview), [Govern Azure platform services for AI](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/ai/platform/governance)

## 🛠️ Hands-on Learning

### Microsoft Learn Modules
- [Prepare for Azure AI development](https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/)
- [Course AI-102T00-A: Develop AI solutions in Azure](https://learn.microsoft.com/en-us/training/courses/ai-102t00)

### Quickstarts
- [Quickstart: Set up your first AI Foundry resource (Azure portal)](https://learn.microsoft.com/en-us/azure/ai-services/multi-service-resource)
- [Quickstart: Create an Azure OpenAI resource](https://learn.microsoft.com/en-us/azure/ai-foundry/openai/how-to/create-resource)
- [Quickstart: Use Prompt Shields](https://learn.microsoft.com/en-us/azure/ai-services/content-safety/quickstart-jailbreak)

### Tutorials
- [Create and configure Azure AI Foundry Models resources](https://learn.microsoft.com/en-us/azure/ai-foundry/foundry-models/how-to/quickstart-create-resources)
- [Configure content filters in Azure AI Foundry](https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/content-filtering)

## 📖 Additional Resources
- [Azure AI services documentation](https://learn.microsoft.com/en-us/azure/ai-services/)
- [Azure AI Foundry portal](https://ai.azure.com/)
- [Azure AI services pricing](https://azure.microsoft.com/en-us/pricing/details/cognitive-services/)
- [Study guide for Exam AI-102: Designing and Implementing a Microsoft Azure AI Solution](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/ai-102)
