# Competitor Monitoring Workflow

**Goal:** Automate the tracking of competitor moves to stay ahead without daily manual checking.

---

## 🔄 Workflow Steps

1. **Setup Monitoring Tools**
   - **Google Alerts:** Set up alerts for "[Competitor Name] launched", "[Competitor Name] pricing", "[Competitor Name] hiring".
   - **Visualping.io (Free Tier):** Monitor competitor's "Pricing" and "Careers" pages for visual changes.

2. **Weekly Aggregation (Friday)**
   - Check Gmail folder "Competitive Intel".
   - Check Visualping dashboard.

3. **AI Synthesis**
   - **Prompt:** "Here are 5 news snippets about [Comp A] and [Comp B] from this week. Summarize the strategic implications in 3 bullet points."
   - Paste the snippets into ChatGPT/Perplexity.

4. **Update Research Hub**
   - Add a new entry in Notion: "Weekly Intel - [Date]".
   - Tag with `Competitor Update`.
   - If a major shift is detected (e.g., new pricing), trigger a **Competitor Deep Dive**.

5. **Flash Report**
   - If critical (e.g., they launched a clone of our feature), post a "Red Alert" in the team Slack/Teams channel immediately.

---

## 🛠️ Tool Configuration
- **Visualping:** Set check frequency to "Daily".
- **Google Alerts:** Set "Deliver to" -> "RSS Feed" (optional) or dedicated email label.
