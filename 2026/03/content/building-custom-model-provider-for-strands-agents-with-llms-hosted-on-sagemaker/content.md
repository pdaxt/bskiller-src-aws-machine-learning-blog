# Building custom model provider for Strands Agents with LLMs hosted on SageMaker AI endpoints

Source: [AWS Machine Learning Blog](https://aws.amazon.com/blogs/machine-learning/building-custom-model-provider-for-strands-agents-with-llms-hosted-on-sagemaker-ai-endpoints/)

---

This post demonstrates how to build custom model parsers for Strands agents when working with LLMs hosted on SageMaker that don't natively support the Bedrock Messages API format. We'll walk through deploying Llama 3.1 with SGLang on SageMaker using awslabs/ml-container-creator, then implementing a custom parser to integrate it with Strands agents.