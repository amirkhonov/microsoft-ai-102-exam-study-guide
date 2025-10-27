# Implement Computer Vision Solutions (15–20%)

This domain covers building computer vision solutions using Azure AI Vision, Custom Vision, and video processing services.

## 📚 Official Microsoft Documentation

### Azure AI Vision
- [What is Azure AI Vision?](https://learn.microsoft.com/en-us/azure/ai-services/computer-vision/overview)
- [Azure AI Vision capabilities](https://learn.microsoft.com/en-us/azure/ai-services/computer-vision/overview)
- [Azure AI Vision Image Analysis](https://learn.microsoft.com/en-us/azure/ai-services/computer-vision/overview-image-analysis)

### Azure Custom Vision
- [What is Custom Vision?](https://learn.microsoft.com/en-us/azure/ai-services/custom-vision-service/overview)
- [Custom Vision capabilities](https://learn.microsoft.com/en-us/azure/ai-services/custom-vision-service/overview)
- [Custom Vision migration guide](https://aka.ms/custom-vision-migration)

### Video Processing
- [Azure AI Video Indexer overview](https://learn.microsoft.com/en-us/azure/azure-video-indexer/video-indexer-overview)
- [Azure AI Video Indexer capabilities](https://learn.microsoft.com/en-us/azure/azure-video-indexer/video-indexer-overview)

## 🎯 Key Topics

## Analyze images
- **Select visual features to meet image processing requirements**: [Azure AI Vision Image Analysis](https://learn.microsoft.com/en-us/azure/ai-services/computer-vision/overview-image-analysis), [Image Analysis capabilities](https://learn.microsoft.com/en-us/azure/ai-foundry/responsible-ai/computer-vision/image-analysis-transparency-note#capabilities)
- **Detect objects in images and generate image tags**: [Object detection with Azure AI Vision](https://learn.microsoft.com/en-us/azure/ai-services/computer-vision/overview-image-analysis), [Image Analysis 4.0](https://learn.microsoft.com/en-us/azure/ai-services/computer-vision/whats-new#october-2022)
- **Include image analysis features in an image processing request**: [Azure AI Vision features](https://learn.microsoft.com/en-us/azure/ai-services/computer-vision/overview), [Tutorial: Vision with Azure AI services](https://learn.microsoft.com/en-us/azure/synapse-analytics/machine-learning/tutorial-computer-vision-use-mmlspark)
- **Interpret image processing responses**: [Image Analysis API](https://learn.microsoft.com/en-us/azure/ai-services/computer-vision/how-to/call-analyze-image-40), [Image Analysis response format](https://learn.microsoft.com/en-us/azure/ai-services/computer-vision/overview-image-analysis?tabs=4-0)
- **Extract text from images using Azure AI Vision**: [OCR for images](https://learn.microsoft.com/en-us/azure/ai-services/computer-vision/concept-ocr), [Azure AI Vision OCR](https://learn.microsoft.com/en-us/azure/ai-services/computer-vision/overview-ocr)
- **Convert handwritten text using Azure AI Vision**: [Handwritten text extraction](https://learn.microsoft.com/en-us/azure/ai-services/computer-vision/overview-ocr), [Handwritten text support](https://learn.microsoft.com/en-us/azure/ai-services/computer-vision/whats-new#february-2022)

## Implement custom vision models
- **Choose between image classification and object detection models**: [Image classification with Custom Vision](https://learn.microsoft.com/en-us/azure/ai-services/custom-vision-service/getting-started-build-a-classifier), [Object detection with Custom Vision](https://learn.microsoft.com/en-us/azure/ai-services/custom-vision-service/get-started-build-detector)
- **Label images**: [Label images for Custom Vision](https://learn.microsoft.com/en-us/azure/ai-services/custom-vision-service/getting-started-build-a-classifier#upload-and-tag-images), [Image labeling best practices](https://learn.microsoft.com/en-us/azure/ai-services/custom-vision-service/getting-started-build-a-classifier)
- **Train a custom image model, including image classification and object detection**: [Train Custom Vision models](https://learn.microsoft.com/en-us/azure/ai-services/custom-vision-service/getting-started-build-a-classifier#train-the-classifier), [Model training process](https://learn.microsoft.com/en-us/windows/ai/windows-ml/tutorials/image-classification-train-model)
- **Evaluate custom vision model metrics**: [Evaluate Custom Vision models](https://learn.microsoft.com/en-us/azure/ai-services/custom-vision-service/getting-started-build-a-classifier#evaluate-the-classifier), [Model evaluation](https://learn.microsoft.com/en-us/windows/ai/windows-ml/tutorials/image-classification-train-model#evaluate-and-test)
- **Publish a custom vision model**: [Deploy Custom Vision models](https://learn.microsoft.com/en-us/azure/ai-services/custom-vision-service/getting-started-build-a-classifier), [Publish trained models](https://learn.microsoft.com/en-us/azure/ai-services/custom-vision-service/getting-started-build-a-classifier)
- **Consume a custom vision model**: [Use trained models](https://learn.microsoft.com/en-us/azure/ai-services/custom-vision-service/use-prediction-api), [Custom Vision prediction API](https://learn.microsoft.com/en-us/azure/ai-services/custom-vision-service/use-prediction-api)
- **Build a custom vision model code first**: [Custom Vision SDK](https://learn.microsoft.com/en-us/azure/ai-services/custom-vision-service/quickstarts/image-classification), [Custom Vision REST API](https://learn.microsoft.com/en-us/azure/ai-services/custom-vision-service/use-prediction-api)

## Analyze videos
- **Use Azure AI Video Indexer to extract insights from a video or live stream**: [Azure AI Video Indexer overview](https://learn.microsoft.com/en-us/azure/azure-video-indexer/video-indexer-overview), [Observed people detection](https://learn.microsoft.com/en-us/azure/azure-video-indexer/observed-matched-people-insight), [Video Indexer insights](https://learn.microsoft.com/en-us/azure/azure-video-indexer/insights-overview)
- **Use Azure AI Vision Spatial Analysis to detect presence and movement of people in video**: [Spatial Analysis overview](https://learn.microsoft.com/en-us/azure/ai-services/computer-vision/intro-to-spatial-analysis-public-preview), [Spatial Analysis operations](https://learn.microsoft.com/en-us/azure/ai-services/computer-vision/spatial-analysis-operations), [Video Analysis capabilities](https://learn.microsoft.com/en-us/azure/architecture/data-guide/ai-services/image-video-processing#services)

## 🛠️ Hands-on Learning

### Microsoft Learn Modules
- [Classify images with the Custom Vision service](https://learn.microsoft.com/en-us/training/modules/classify-images/)
- [Image classification with custom Azure AI Vision models](https://learn.microsoft.com/en-us/training/modules/custom-model-ai-vision-image-classification/)
- [Analyze video with Azure AI Video Indexer](https://learn.microsoft.com/en-us/training/modules/analyze-video/)

### Quickstarts
- [Quickstart: Azure AI Vision client library](https://learn.microsoft.com/en-us/azure/ai-services/computer-vision/quickstarts-sdk/image-analysis-client-library-40)
- [Quickstart: Build an image classification model with Custom Vision](https://learn.microsoft.com/en-us/azure/ai-services/custom-vision-service/getting-started-build-a-classifier)
- [Quickstart: Azure AI Video Indexer](https://learn.microsoft.com/en-us/azure/azure-video-indexer/video-indexer-overview)

### Tutorials
- [Tutorial: Vision with Azure AI services](https://learn.microsoft.com/en-us/azure/synapse-analytics/machine-learning/tutorial-computer-vision-use-mmlspark)
- [Tutorial: Train your model with Custom Vision](https://learn.microsoft.com/en-us/windows/ai/windows-ml/tutorials/image-classification-train-model)
- [Tutorial: Azure AI Video Indexer enabled by Arc](https://learn.microsoft.com/en-us/azure/azure-video-indexer/arc/azure-video-indexer-enabled-by-arc-overview)

## 📖 Additional Resources
- [Azure AI Vision pricing](https://azure.microsoft.com/en-us/pricing/details/cognitive-services/computer-vision/)
- [Azure Custom Vision pricing](https://azure.microsoft.com/en-us/pricing/details/cognitive-services/custom-vision-service/)
- [Azure AI Video Indexer pricing](https://azure.microsoft.com/en-gb/pricing/details/video-indexer/)
- [Choose an Azure AI image and video processing technology](https://learn.microsoft.com/en-us/azure/architecture/data-guide/ai-services/image-video-processing)
- [Study guide for Exam AI-102: Designing and Implementing a Microsoft Azure AI Solution](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/ai-102)