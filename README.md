```markdown
# Call-Option-Payoff-Simulator

Interactive call option payoff simulator for students, educators and anyone learning options.

This project is designed to be a friendly, exploratory simulator so learners can experiment with strike, premium and stock-at-maturity scenarios and see payoff results immediately. Contributions are welcome — whether you add features, improve visuals, add exercises, or provide test cases and presets that make learning more engaging.

Features
- Single-file HTML simulator (no build step) that runs in any modern browser.
- Fixed strike & premium (purchase parameters) with an adjustable S(T) slider to explore payoffs.
- Color-coded visual elements to make key values easy to spot (strike/profit/stock).
- Crisp canvas rendering (handles device pixel ratio).

Why this repo
- For students and learners: tweak values, observe payoff, and learn risk/reward intuitively.
- For instructors: add exercises, scenarios and questions.
- For contributors: extend to support multiple option types (puts), add Greeks, time decay visualization, or server-side scenario sharing.

Contributing
- Fork the repository, create a topic branch, and open a pull request.
- Add clear descriptions to PRs and include screenshots or animated GIFs for UI changes.
- If adding code, include simple integration steps in the README and keep the UI accessible.

Suggested issues to start with
- Add preset scenario buttons (Bullish / Bearish / Volatile).
- Export image / download PNG of chart.
- Add hover tooltips to show exact payoff numbers for any price.
- Add a “compare two strikes” mode.

License
This project is released under the MIT License. See LICENSE for details.

Screenshots
Add screenshots to `assets/screenshots/` and reference them here. Example in README after you add images:

![Simulator screenshot 1](assets/screenshots/screenshot1.png)
![Simulator screenshot 2](assets/screenshots/screenshot2.png)

How to run locally
1. Clone the repo (after you create it on GitHub) and open `call-option-payoff.html` in your browser:
   - `git clone https://github.com/<your-username>/Call-Option-Payoff-Simulator.git`
   - Open `call-option-payoff.html` in Chrome/Firefox/Edge.
2. No dependencies or build steps required.

Developer setup (optional)
- If you want to maintain versions, use `git` and push to GitHub as shown in the instructions I provide.

Contact & attribution
- Created by: manpreet-sangha
- If you use this project in educational material or publications, please include attribution: "Call-Option-Payoff-Simulator by manpreet-sangha".

```