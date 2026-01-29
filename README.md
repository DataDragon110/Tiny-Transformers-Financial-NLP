# Tiny-Transformers-Financial-NLP
CPU-optimized Transformer models for Financial Sentiment Analysis. Solves class imbalance with 9.5M parameters.  Status: ✅ Published (2025) ```markdown
Tiny Transformers for Financial Sentiment Analysis
Class Imbalance Resolution and CPU-Optimized Deployment

🎯 Overview
This repository contains the implementation of the 9.5M-parameter Tiny Transformer. The project demonstrates that small-scale models can outperform large-scale baselines in financial sentiment analysis by addressing class imbalance and achieving ultra-low latency on standard CPUs.

🚀 Key Results
Performance: Improved Macro-F1 from 26.2% to 61.6% (135% improvement).

Efficiency: 11.5ms inference latency on a single CPU core.

Robustness: Increased minority class detection (negative sentiment) from 0% to 43.5%.

📁 Structure
/src: Core Transformer architecture and class-weighted loss scripts.

/eval: Accuracy-per-parameter ratio analysis.
