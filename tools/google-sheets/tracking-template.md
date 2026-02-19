# Google Sheets Tracking Template

**Purpose:** Track time spent and calculate ROI of the research automation.

---

## 📊 Columns Structure

| Column | Description | Formula (if any) |
| :--- | :--- | :--- |
| **Request ID** | Unique identifier (e.g., RES-001) | - |
| **Topic** | Brief description | - |
| **Requester** | Person or Department | - |
| **Manual Time Est.** | Est. hours if done manually | - |
| **Actual Time (AI)** | Actual hours spent using this system | - |
| **Time Saved** | Difference in hours | `=D2-E2` |
| **Cost Savings** | Time Saved * Hourly Rate | `=F2*500` (assuming ₹500/hr) |

## 📈 Dashboard Ideas
- **Total Hours Saved per Month** (Bar Chart)
- **Top Requesting Departments** (Pie Chart)
