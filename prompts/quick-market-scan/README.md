# Quick Market Scan - Usage Guide

## 📋 Overview
The **Quick Market Scan** is designed for the initial phase of research where speed and breadth are more important than depth. It provides a "bird's-eye view" of a market landscape.

## ⚙️ Configuration
- **Tool:** Perplexity Pro (Focus: "All" or "Writing" mode does not apply here; use "Internet" search focus) or ChatGPT-4 with browsing enabled.
- **Model:** GPT-4 or Claude 3 Opus (for better reasoning).

## 🚀 Execution Steps
1. Copy the prompt from `prompt.md`.
2. Replace the `[bracketed_placeholders]` with your specific research parameters.
3. Run the prompt.
4. **Review & Verify:** Check the sources provided (at least 2-3) to ensure data is not hallucinated.

## ✅ Success Criteria
A successful run must meet the following conditions:
- [ ] **Completeness:** All 5 sections of the Output Structure are populated.
- [ ] **Accurate Sourcing:** At least 3 distinct, verifiable sources are cited.
- [ ] **Relevance:** Data is from within the last 12 months (unless historical context was requested).
- [ ] **Actionability:** The "Executive Summary" provides clear direction or insight, not just generic statements.

## ⚠️ Troubleshooting
- **Issue:** Results are too generic.
  - **Fix:** Add a constraint: "Focus specifically on the [REGION] market" or "Ignore [A_SPECIFIC_COMPETITOR]".
- **Issue:** Sources are outdated.
  - **Fix:** Explicitly add "Search only for reports published in 2024-2025" to the prompt constraints.
