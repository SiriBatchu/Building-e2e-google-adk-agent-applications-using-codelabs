# 🧠 Interactive Lead Generation Agent

An **intelligent, agentic lead generation system** that learns from real investment behaviors of successful companies to predict and identify new potential leads in emerging markets.  
The agent mimics a human research process—analyzing past patterns and applying them to future predictions—while remaining fully interactive with the user.

---

## ⚙️ Core Concept: Agentic Learning + Prediction

The system operates in two phases, combining **machine intelligence** with **guided user interaction**:

### 1. Pattern Discovery (Learning)
- The agent studies companies that have recently invested in a chosen market.  
- It identifies *pre-investment signals*—specific activities or behaviors that occurred before those investments (e.g., partnerships, hiring trends, expansions).  
- From these, it extracts common success patterns that characterize profitable market entries.

### 2. Lead Generation (Prediction)
- After user approval of the discovered patterns, the agent applies them to current market data.  
- It searches for new companies now showing similar signals, predicting which are most likely to invest next.

---

## 💬 Interactive Workflow

The process is highly conversational and user-driven:

1. **Intent Extraction** – User defines the goal (e.g., “Find fintech leads in Thailand”).  
   → `intent_extractor_agent` identifies the target **industry** and **country**.  
2. **Pattern Discovery Scope** – User specifies how many successful companies to analyze (1–10).  
3. **Pattern Review** – The agent summarizes the learned patterns for user approval.  
4. **Lead Generation Scope** – After confirmation, the user chooses how many new leads to generate (1–10).  
5. **Final Report** – The `lead_generation_agent` delivers a detailed, sourced report of predicted high-potential leads.

---

## 🚀 Key Features

- Agentic, multi-phase workflow combining reasoning, memory, and interaction.  
- Adaptive learning from historical investment data.  
- User-guided research loops for transparency and control.  
- Predictive identification of emerging investment opportunities.
