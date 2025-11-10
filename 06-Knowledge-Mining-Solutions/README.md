# Implement Knowledge Mining and Information Extraction Solutions (15–20%)

This domain covers building knowledge mining and information extraction solutions using Azure AI Search, Azure AI Document Intelligence, and Azure AI Content Understanding services.

## 📚 Official Microsoft Documentation

### Azure AI Search
- [What is Azure AI Search?](https://learn.microsoft.com/en-us/azure/search/search-what-is-azure-search)
- [Azure AI Search features](https://learn.microsoft.com/en-us/azure/search/search-features-list)
- [Vector search in Azure AI Search](https://learn.microsoft.com/en-us/azure/search/vector-search-overview)

### Azure AI Document Intelligence
- [What is Azure AI Document Intelligence?](https://learn.microsoft.com/en-us/azure/ai-services/document-intelligence/overview)
- [Document Intelligence models](https://learn.microsoft.com/en-us/azure/ai-services/document-intelligence/model-overview)
- [Document Intelligence Studio](https://documentintelligence.ai.azure.com/)

### Azure AI Content Understanding
- [What is Azure AI Content Understanding?](https://learn.microsoft.com/en-us/azure/ai-services/content-understanding/overview)
- [Azure AI Content Understanding capabilities](https://learn.microsoft.com/en-us/azure/ai-services/content-understanding/overview)
- [Azure AI Content Understanding terminology](https://learn.microsoft.com/en-us/azure/ai-services/content-understanding/glossary)

## 🎯 Key Topics

## Implement an Azure AI Search solution
- **Provision an Azure AI Search resource, create an index, and define a skillset**: [Create an Azure AI Search solution](https://learn.microsoft.com/en-us/azure/search/search-create-service-portal), [Create search indexes](https://learn.microsoft.com/en-us/azure/search/search-create-index-portal), [Create skillsets](https://learn.microsoft.com/en-us/azure/search/cognitive-search-defining-skillset)
- **Create data sources and indexers**: [Create indexers](https://learn.microsoft.com/en-us/azure/search/search-how-to-create-indexers), [Indexer data sources](https://learn.microsoft.com/en-us/azure/search/search-indexer-overview)
- **Implement custom skills and include them in a skillset**: [Custom skills in Azure AI Search](https://learn.microsoft.com/en-us/azure/search/cognitive-search-custom-skill-web-api), [Add custom skills to enrichment pipeline](https://learn.microsoft.com/en-us/azure/search/cognitive-search-custom-skill-interface)
- **Create and run an indexer**: [Create and run indexers](https://learn.microsoft.com/en-us/azure/search/search-how-to-create-indexers), [Indexer execution](https://learn.microsoft.com/en-us/azure/search/search-indexer-overview)
- **Query an index, including syntax, sorting, filtering, and wildcards**: [Query Azure AI Search](https://learn.microsoft.com/en-us/azure/search/search-query-overview), [Search syntax](https://learn.microsoft.com/en-us/azure/search/query-lucene-syntax)
- **Manage Knowledge Store projections, including file, object, and table projections**: [Knowledge store projections](https://learn.microsoft.com/en-us/azure/search/knowledge-store-projection-overview), [Create knowledge store](https://learn.microsoft.com/en-us/azure/search/knowledge-store-concept-intro#create-a-knowledge-store)
- **Implement semantic and vector store solutions**: [Semantic search in Azure AI Search](https://learn.microsoft.com/en-us/azure/search/semantic-search-overview), [Vector search in Azure AI Search](https://learn.microsoft.com/en-us/azure/search/vector-search-overview)

## Implement an Azure AI Document Intelligence solution
- **Provision a Document Intelligence resource**: [Create Document Intelligence resource](https://learn.microsoft.com/en-us/azure/ai-services/document-intelligence/quickstarts/get-started-sdks-rest-api), [Document Intelligence resource setup](https://learn.microsoft.com/en-us/azure/ai-services/document-intelligence/quickstarts/get-started-sdks-rest-api)
- **Use prebuilt models to extract data from documents**: [Prebuilt models in Document Intelligence](https://learn.microsoft.com/en-us/azure/ai-services/document-intelligence/model-overview), [Document Intelligence invoice model](https://learn.microsoft.com/en-us/azure/ai-services/document-intelligence/prebuilt/invoice)
- **Implement a custom document intelligence model**: [Custom models in Document Intelligence](https://learn.microsoft.com/en-us/azure/ai-services/document-intelligence/how-to-guides/compose-custom-models), [Train custom models](https://learn.microsoft.com/en-us/azure/ai-services/document-intelligence/train/custom-model)
- **Train, test, and publish a custom document intelligence model**: [Train custom models](https://learn.microsoft.com/en-us/azure/ai-services/document-intelligence/train/custom-model), [Model lifecycle management](https://learn.microsoft.com/en-us/azure/ai-services/document-intelligence/how-to-guides/compose-custom-models)
- **Create a composed document intelligence model**: [Composed models](https://learn.microsoft.com/en-us/azure/ai-services/document-intelligence/train/composed-models), [Create composed models](https://learn.microsoft.com/en-us/azure/ai-services/document-intelligence/how-to-guides/compose-custom-models)

## Extract information with Azure AI Content Understanding
- **Create an OCR pipeline to extract text from images and documents**: [Content extraction in Content Understanding](https://learn.microsoft.com/en-us/azure/ai-services/content-understanding/overview), [OCR pipeline creation](https://learn.microsoft.com/en-us/azure/ai-services/content-understanding/tutorial/build-rag-solution)
- **Summarize, classify, and detect attributes of documents**: [Field extraction in Content Understanding](https://learn.microsoft.com/en-us/azure/ai-services/content-understanding/overview), [Document analysis](https://learn.microsoft.com/en-us/azure/ai-services/content-understanding/document/overview)
- **Extract entities, tables, and images from documents**: [Content extraction capabilities](https://learn.microsoft.com/en-us/azure/ai-services/content-understanding/overview), [Entity extraction](https://learn.microsoft.com/en-us/azure/ai-services/content-understanding/document/overview)
- **Process and ingest documents, images, videos, and audio with Azure AI Content Understanding**: [Create a multimodal analysis solution with Azure AI Content Understanding](https://learn.microsoft.com/en-us/training/modules/analyze-content-ai/), [Content Understanding capabilities](https://learn.microsoft.com/en-us/azure/ai-services/content-understanding/overview)

## 🛠️ Hands-on Learning

### Microsoft Learn Modules
- [Implement knowledge mining with Azure AI Search](https://learn.microsoft.com/en-us/training/paths/implement-knowledge-mining-azure-cognitive-search/)
- [Develop AI information extraction solutions in Azure](https://learn.microsoft.com/en-us/training/paths/ai-extract-information/)
- [Get started with AI-powered information extraction in Azure](https://learn.microsoft.com/en-us/training/modules/ai-information-extraction/)
- [Introduction to AI-powered information extraction concepts](https://learn.microsoft.com/en-us/training/modules/introduction-information-extraction/)
- [Fundamentals of Azure AI Document Intelligence](https://learn.microsoft.com/en-us/training/modules/analyze-receipts-form-recognizer/)

### Quickstarts
- [Quickstart: Create an Azure AI Search solution](https://learn.microsoft.com/en-us/azure/search/search-create-service-portal)
- [Quickstart: Get started with Document Intelligence](https://learn.microsoft.com/en-us/azure/ai-services/document-intelligence/quickstarts/get-started-sdks-rest-api)
- [Quickstart: Get started with Content Understanding](https://learn.microsoft.com/en-us/azure/ai-services/content-understanding/quickstart/use-rest-api)

## 📖 Additional Resources
- [Azure AI Search documentation](https://learn.microsoft.com/en-us/azure/search/)
- [Azure AI Document Intelligence documentation](https://learn.microsoft.com/en-us/azure/ai-services/document-intelligence/)
- [Azure AI Foundry documentation](https://learn.microsoft.com/en-us/azure/ai-foundry/)
- [Azure AI services pricing](https://azure.microsoft.com/en-gb/pricing/details/cognitive-services/)
- [Azure-Samples GitHub](https://github.com/Azure-Samples)