# AI Agent Frerai
<div align="center">
  <img src="https://github.com/Frerai-Agent/INFO/blob/main/images/logo.jpg" alt="Logo" width="200" height="200">
</div>

[![GitHub license](https://img.shields.io/github/license/ParisNeo/lollms-webui)](https://github.com/Frerai-Agent/INFO/blob/main/LICENSE)
[![Follow me on X](https://img.shields.io/twitter/follow/agentFrerai?style=social)](https://x.com/agentFrerai)
[![Website](https://img.shields.io/badge/-INSTAGRAM-aa00ff?style=for-the-badge)](https://frerai.com/)

___
### About
Agent Frerai Core: Automate Web Tasks with LLM Power
Agent Lens Core is a lightweight yet powerful tool designed to automate complex web tasks using LLMs like OpenAI's GPT-4. With support for Playwright and seamless integration with LangChain-compatible models, this package makes web task automation more accessible, efficient, and intelligent.

:star: Key Features
Effortless Automation: Automate web tasks such as searching flights, booking tickets, or extracting data.
Powerful LLM Integration: Works with LangChain-compatible models like GPT-4, Claude, and others.
Playwright Support: Enhance automation workflows with Playwright for browser-based operations.
Customizable Settings: Easily adapt to different tasks by specifying goals and models.

### DEMO
Prompt: Find flights on kayak.com from Zurich to Beijing from 25.12.2024 to 02.02.2025.
<br>![Demo](https://github.com/Frerai-Agent/INFO/blob/main/images/demo.gif)

___
#### :rocket:Getting Started
1. Installation
Install the core package:

pip install agent_lens_core
[Download](https://github.com/Frerai-Agent/INFO/blob/main/agent_frerai_core-0.1.1.tar.gz)

+ (Optional) Install Playwright for browser automation:

playwright install
2. Add API Keys
Create a .env file in your project root and add your API key:

``OPENAI_API_KEY=<your_openai_api_key>``
3. Spin Up Your Agent
Here’s an example to get started:

> <h3>python</h3> 
> <br> from langchain_openai import ChatOpenAI from agent_lens_core 


+ import Agent
+ import asyncio
````
async def main():
    agent = Agent(
        task="Find a one-way flight from Bali to Oman on 12 January 2025 on Google Flights. Return me the cheapest option.",
        llm=ChatOpenAI(model="gpt-4o"),
    )
    result = await agent.run()
    print(result)

asyncio.run(main())
````
___

### Accurancy
![Accurancy](https://github.com/Frerai-Agent/INFO/blob/main/images/accurancy.jpg)

#### :books:Documentation
Check out the documentation for more details on:

Supported LLMs
Custom task configurations
Advanced Playwright integration
+ :wrench: Use Cases
  + Web scraping and data extraction
  + Automating travel planning tasks
  + Dynamic interactions with web platforms
  + Enhanced AI-driven workflows for businesses
+ :hammer: Contributions
  
We welcome your feedback, contributions, and ideas! Feel free to submit issues or pull requests to improve Agent Lens Core.

#### :scroll: License
This project is licensed under the MIT License. See the LICENSE file for details.

Automate smarter with Agent Lens Core — your gateway to intelligent web task automation!
___
<div align="center">
  <img src="https://github.com/Frerai-Agent/INFO/blob/main/images/logo.jpg" alt="Logo" width="200" height="200">
</div>

> AgentFrerai 2025


