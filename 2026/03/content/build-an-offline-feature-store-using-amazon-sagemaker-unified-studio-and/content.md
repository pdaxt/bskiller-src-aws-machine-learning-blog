# Build an offline feature store using Amazon SageMaker Unified Studio and SageMaker Catalog

Source: [AWS Machine Learning Blog](https://aws.amazon.com/blogs/machine-learning/build-an-offline-feature-store-using-amazon-sagemaker-unified-studio-and-sagemaker-catalog/)

---

This blog post provides step-by-step guidance on implementing an offline feature store using SageMaker Catalog within a SageMaker Unified Studio domain. By adopting a publish-subscribe pattern, data producers can use this solution to publish curated, versioned feature tables - while data consumers can securely discover, subscribe to, and reuse them for model development.