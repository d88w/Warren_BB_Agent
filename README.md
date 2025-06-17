# 📈 Warren BB – Value-Growth Investment Advisor AI Agent

This notebook implements a long-term investment advisor agent modeled on the combined principles of Warren Buffett, Benjamin Graham, Charlie Munger, Peter Lynch, Philip Fisher, Chuck Akre, T. Rowe Price Jr., and Terry Smith.

The agent is capable of reasoning through financial data, applying timeless investing principles, and fetching real-time stock metrics via API to support grounded analysis — just like a disciplined value-growth investor would.

⸻

🧠 Core Features
- Value + Growth Investing Principles
  - Grounded in the philosophies of Graham, Buffett, Munger, and other legendary investors. All answers are backed by cited investor quotes or paraphrased principles.
- Live Financial Data
  - Uses the Finnhub API to retrieve real-time stock prices, P/E ratios, FCF yield, and ROIC.
- OpenAI-powered Reasoning
  - Integrated with OpenAIAgent from LlamaIndex to interpret questions, invoke tools, and respond as an intelligent financial advisor.

⸻

🚀 How It Works
1. ✅ System Prompt: A curated prompt simulates an agent trained by the greatest investors of all time.
2. 🔧 Tool: fetch_stock_data(): Fetches live financial metrics for a given stock ticker from Finnhub.
3. 🤖 Agent: Uses FunctionTool from LlamaIndex to enable the tool, and responds to queries like “Is AAPL a compounder?” with real data and cited logic.

⸻

🛠 Setup Instructions
1. Install dependencies:
  - pip install openai llama-index requests

2. Add API Keys:
  - In the notebook, replace:
  - os.environ['OPENAI_API_KEY'] = 'your-openai-api-key'
  - FINNHUB_API_KEY = 'your-finnhub-api-key'

3. Run Example:
  - The agent is pre-configured to handle:
  - agent.chat("Evaluate AAPL as a long-term compounder.")

4. Example Use Cases
  - “What would Buffett think of Tesla?”
  - “Analyze Google’s moat and valuation.”
  - “Fetch and interpret the financials of NVDA.”
  - “Which metrics would Graham use to analyze this?”

⸻

📚 Cited Investors

This agent reasons using quotes and principles from:
- Benjamin Graham
- Warren Buffett
- Charlie Munger
- Philip Fisher
- Peter Lynch
- Chuck Akre
- T. Rowe Price Jr.
- Terry Smith

Each recommendation will include reference to their core ideas where applicable.

⸻

🧾 License & Attribution

This project uses OpenAI and Finnhub APIs.
Built using LlamaIndex.
