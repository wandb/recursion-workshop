# Recursion Workshop

This repository contains onboarding materials for the **Recursion** team to learn and experiment with **Weights & Biases (W&B) Weave**.

## Overview

These examples walk through how to:
- Track experiments and datasets using **W&B**.
- Visualize model performance interactively with **Weave**.
- Build simple data apps (like `pdf_summarizer`) that integrate W&B for tracking, visualization, and sharing.

## Structure

- `intro-workshop/` – Walkthrough notebook  
- `pdf_summarizer/` – Example Streamlit app that summarizes PDF content and logs results to Weave
- `wandb/` – Local W&B data directory (auto-created during runs).  

## Getting Started

1. Clone the repo:
   ```bash
   git clone https://github.com/wandb/recursion-workshop.git
   cd recursion-workshop

## Setup

Create a `.env` file with your API keys:

```env
OPENAI_API_KEY=your_openai_api_key
ANTHROPIC_API_KEY=your_anthropic_api_key
WANDB_API_KEY=your_wandb_api_key
WANDB_ENTITY=your_wandb_team_name
