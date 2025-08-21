# Pricing Intelligence AI

🤖 **AI-driven pricing and inventory intelligence system using LangChain, LangGraph, and Gemini**

## Current Status: Phase 1 - Foundation

**Phase 1 Focus:**
- ✅ Basic LangChain agent with Gemini integration
- ✅ Simple tool ecosystem (inventory, competitor, calculator)
- ✅ Direct Python testing (no web framework)
- ✅ API key authentication (simple setup)
- ✅ Foundation for advanced phases

## Quick Start

### Prerequisites
- Python 3.11+
- Google AI Studio API key

### Get Google AI API Key
1. Go to [Google AI Studio](https://makersuite.google.com/app/apikey)
2. Create new API key
3. Copy key to `.env` file

### Installation (When You Have Your Laptop)
```bash
git clone https://github.com/YOURUSERNAME/pricing-intelligence-ai.git
cd pricing-intelligence-ai

# Create virtual environment
python -m venv venv
source venv/bin/activate  # Linux/Mac

# Install dependencies
pip install -r requirements.txt

# Copy environment template
cp .env.template .env
# Edit .env and add your API key
