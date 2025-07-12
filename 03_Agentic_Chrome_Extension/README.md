# EAG-Session-03 Assignment - Agentic LLM based Chrome Extension

**Assignment Overview**

Make a simple Agentic AI Chrome Plugin!

- In the first assignment, you made a simple Chome Plugin
- In the second assignment, you added LLM to it 
- In this, third assignment, you need to make a Chrome Agentic AI Plugin!
- Now the expectation is:
    - You ask your LLM something it cannot do (or would hallucinate, or would internally call its own Agent, which Gemini can do!), for example:
        - Calculations: Calculate the sum of exponential values of the first 6 Fibonacci Numbers
        - External Tool/Framework Use: Find the top OTT series this week and send them to me on Telegram/Email
        - Continuous Monitoring: Track the price of a Stock (or Temperature) and update me as soon as it crosses X value
        - Multi-step Research: Find the news about a particular stock and link it with its price changes (e.g. search news about Ola in the last 1 month and news date, then see how the stock moved on those dates, and then link this data)
    - So to achieve this assignment you must:
        - call your LLM multiple times:
            - Query→LLM Response→Tool Call:Tool Result→Query→LLM Response→Tool Call:Tool Result→Query→LLM Response→Result
        - Each time your Query stores "ALL" past interaction
            - Query1→LLM Response→Tool Call:Tool Result→Query2→LLM Response→Tool Call:Tool Result→Query3→LLM Response→Result
    - Keep things very simple. 
- Submission: A YouTube video that shows how your Agent works on your Chrome Plugin AND copy-paste your LLM logs.

Todo
- add logs
- add multistep

**Link for Assignment**

- [Ajith Assist](https://github.com/ajithvcoder/Ajith-Assist/tree/feature_agentic_1.0)