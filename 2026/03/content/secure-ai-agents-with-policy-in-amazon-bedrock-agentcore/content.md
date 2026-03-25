# Secure AI agents with Policy in Amazon Bedrock AgentCore

Source: [AWS Machine Learning Blog](https://aws.amazon.com/blogs/machine-learning/secure-ai-agents-with-policy-in-amazon-bedrock-agentcore/)

---

In this post, you will understand how Policy in Amazon Bedrock AgentCore creates a deterministic enforcement layer that operates independently of the agent's own reasoning. You will learn how to turn natural language descriptions of your business rules into Cedar policies, then use those policies to enforce fine-grained, identity-aware controls so that agents only access the tools and data that their users are authorized to use. You will also see how to apply Policy through AgentCore Gateway, intercepting and evaluating every agent-to-tool request at runtime.