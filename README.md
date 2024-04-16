# LangChain Exploration for LLM Application Development

Welcome to the LangChain exploration repository(referenced from LangChain for LLM Application Development of deeplearning.ai), where we delve into adapting LangChain methodologies for LLM (Large Language Model) application development, with a specific focus on Llama2(any model) from Hugging Face. Our goal is to provide valuable insights and practical applications for individuals interested in using different styles than the chat_models module in LangChain.

What to Expect
In this repository, you'll gain hands-on experience with the following topics:

Models, Prompts, and Parsers: Learn how to call LLMs, provide prompts, and parse the response effectively.
Memories for LLMs: Explore techniques to store conversations and manage limited context space.
Chains: Create sequences of operations to streamline your LLM application development.
Question Answering over Documents: Apply LLMs to your proprietary data and use case requirements for effective document-based question answering.
Agents: Dive into the emerging development of LLMs as reasoning agents, starting with basic agent styles.

Challenges Faced:

Different Prompt Structures: Chains, Agents etc  have inbuilt prompts  which should be different for different models. Models like OpenAI and Llama require different prompt structures for optimal performance. For example, OpenAI models thrive with structured prompts like "Title: [Title], Context: [Context], Objective: [Objective], Example: [Example]", while Llama models may benefit from prompts like "[INST] <<SYS>>{system prompt}<</SYS>>{prompt}[/INST]". Understanding and adapting to these differences is crucial for achieving desired results.

Custom Pipeline Development: When working with models like Llama2 from Hugging Face, I faced issues with input generation before output, impacting the effectiveness of inbuilt output parsers in chains or agents. To address this, I've developed a custom pipeline inspired by the OpenAI pipeline, focusing on removing initial generated inputs and incorporating essential features for demonstrating concepts effectively.

Future Projects
In future iterations, I aim to delve deeper into developing custom agents or chains, exploring advanced functionalities and optimization techniques. Stay tuned for updates.



