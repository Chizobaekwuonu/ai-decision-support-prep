# AI Decision-Support Explorations
This repository contains two exploratory projects completed as preparation for a research pathway in agentic AI and global health supply chains. The aim is to understand how forecasting, optimisation, and natural-language reasoning can support decision-making in complex and uncertain environments.

## 1. Time-Series Forecasting (forecasting.ipynb)
A 24-month synthetic demand dataset was used to build an ARIMA-based forecasting model.
**What I did:**
- Loaded and cleaned time-series data  
- Created train/test split  
- Fitted ARIMA(2,1,2) model  
- Compared forecast vs actual  
- Visualised demand trends  
**What I learned:**
Forecasting models handle smooth patterns well but struggle with shocks, highlighting why static models alone cannot manage volatile global health supply chains.

## 2. Natural-Language Decision Agent (decision_agent.ipynb)
A minimal decision-support prototype using the FLAN-T5 Base model.
**What I did:**
- Loaded instruction-tuned model  
- Designed decision-support prompts  
- Tested questions involving shortages, delays, and uncertain donor funding  
- Generated structured, step-by-step recommendations  
**What I learned:**
LLMs can offer rapid reasoning, but without real-time context or constraints. This reinforces the need for LLMs integrated with forecasting, optimisation, and human-in-the-loop oversight—core components of the project.

## Purpose
These exercises helped me:
- Strengthen practical analytics and Python skills  
- Build intuition around forecasting and AI-driven reasoning  
- Understand the potential and limitations of agentic AI  
- Prepare for PhD-level research for AI decision-support systems  

