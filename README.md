# 🔥 Codeforces Profile Analyzer

Analyze and compare Codeforces profiles using beautiful charts and insightful visualizations. This tool helps competitive programmers track their progress, identify strengths and weaknesses, and compare with friends!

## 🚀 Features

- 🔍 **Single User Analysis**
  - Rating graph (contest performance over time)
  - Verdict distribution (AC, WA, TLE, etc.)
  - Problems solved by:
    - Difficulty rating
    - Tags (DP, greedy, etc.)
    - Index (A, B, C...)
    - Programming language

- ⚔️ **Versus Mode (Two-User Comparison)**
  - Side-by-side profile comparison
  - Rating graph comparison
  - Common contest participation
  - Comparative problem-solving stats

- 📊 Interactive and responsive charts using `react-chartjs-2` (Chart.js)

## 🛠️ Tech Stack

- **Frontend:** React.js (functional components + hooks)
- **Routing:** React Router
- **UI Library:** Material-UI
- **HTTP Requests:** Axios
- **Charts:** react-chartjs-2 (Chart.js)
- **Data Source:** [Codeforces Public REST API](https://codeforces.com/apiHelp)

## 📦 Installation

```bash
git clone https://github.com/your-username/codeforces-analyzer.git
cd codeforces-analyzer
npm install
npm start

