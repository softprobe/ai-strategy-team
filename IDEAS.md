
# IDEAS

## Open Source Claude Code

Project name: Softprobe AI Data Engineer

Claude Code is a powerful AI OS. It's AI based goal-driven, todo list based task break-down and orchestration is powerful. 
It's not just useful for programming. We have seem many use cases such as generating presentation decks. 

More importantly, Softprobe is aim to build an AI based ETL product for enterprise. ETL itself is essentially a programming
problem, which analyzes source JSON schema, design a data warehouse table schema, and write Python code to convert JSON into
tabluar format. This process will be interactive process between AI agents and human users.

We could build the product direct from Claude Code SDK. However, having an in-house developed Claude Code give us full control.
We could also gain traction by open source this product.

Readings: 
- 国外大神逆向了 Claude Code，发现它好用的秘密藏在反常识的 Agent 设计里（附完整 System Prompt) https://mp.weixin.qq.com/s/aL3Yu8chabvu-9iu7As4zQ
- Google Agent Development Kit (ADK): https://google.github.io/adk-docs/tutorials/agent-team/
- OpenCode: https://github.com/sst/opencode
- Aider: https://github.com/Aider-AI/aider
- AgentGPT: https://github.com/reworkd/AgentGPT
- AutoGen: https://github.com/microsoft/autogen

## Pathway to the future: Every Business Has Its Own Specialized AI Model

The current mainstream AI models such as ChatGPT and Gemini are stateless and capable of doing everthing. This is expensive and not
the most effective way. Just like humans are expert of something via learning and practice, every business is likely to train an expert
model specifically for their own business. Or let the general AI model to learn from their operations. 

Finetuning or training a model requires lots of training data. Softprobe's data collection can potentially provide data samples for AI 
model training. And Softprobe's AI Data Engineer can potentially can turn those raw JSON messages into structed, AI labeled or synthetic 
training data for businesses. 

So there could be a long-term strategy approach: 

1. HTTP JSON message recording
2. AI Data Engineer, or AI ETL
3. Enterprise model traning service

## Bookcast

Generate 15 minutes podcast from books.

- Value: "Help me understand books quickly"  
- Source code path: /Users/bill/src/book

