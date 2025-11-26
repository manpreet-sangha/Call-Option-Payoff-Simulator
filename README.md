```markdown
# Options Payoff Simulator

Interactive ## F## Contributing

We welcome contributions that enhance the educational value of this simulator!

### How to Contribute
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing educational feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Contribution Guidelines
- **Educational Focus**: Ensure new features enhance learning and understanding
- **Code Clarity**: Write readable code with educational comments
- **User Experience**: Maintain the simple, intuitive interface
- **Documentation**: Update README and include screenshots for UI changes
- **Testing**: Verify features work across different browsers and devices

## Future Enhancement Ideas

- **Advanced Strategies**: Add support for spreads, straddles, and other multi-leg strategies
- **Greeks Visualization**: Display Delta, Gamma, Theta, and Vega calculations
- **Time Decay Animation**: Show how options lose time value as expiration approaches
- **Preset Scenarios**: Add "Bullish", "Bearish", and "Volatile" market scenario buttons
- **Export Functionality**: Download PNG images of charts for assignments and presentations
- **Interactive Tooltips**: Hover over chart points to see exact payoff calculations
- **Multiple Strike Comparison**: Compare different strike prices side-by-side
- **Historical Data Integration**: Use real stock price data for more realistic scenarios

## License

This project is released under the MIT License. See [LICENSE](LICENSE) for details.ment Ideas

- **Advanced Strategies**: Add support for spreads, straddles, and other multi-leg strategies
- **Greeks Visualization**: Display Delta, Gamma, Theta, and Vega calculations
- **Time Decay Animation**: Show how options lose time value as expiration approaches
- **Preset Scenarios**: Add "Bullish", "Bearish", and "Volatile" market scenario buttons
- **Export Functionality**: Download PNG images of charts for assignments and presentations
- **Interactive Tooltips**: Hover over chart points to see exact payoff calculations
- **Multiple Strike Comparison**: Compare different strike prices side-by-side
- **Historical Data Integration**: Use real stock price data for more realistic scenariosns payoff simulator for students, educators and anyone learning options strategies.

This comprehensive educational tool allows learners to explore both **call and put options** with real-time visualization of payoffs, profit/loss calculations, and key option metrics. Students can experiment with different stock prices at expiration to understand how options behave in various market conditions. The simulator is designed to be friendly and exploratory, making options concepts accessible through interactive learning.

## Features

### Core Functionality
- **Dual Option Types**: Toggle between Call and Put options with one click
- **Interactive Visualization**: Real-time payoff diagrams that update as you adjust parameters
- **Educational Formulas**: Display of intrinsic value calculations with proper mathematical notation
- **ITM/OTM/ATM Indicators**: Dynamic labels showing option moneyness status
- **Time Value Analysis**: Breakdown of premium components for better understanding

### Technical Features
- Single-file HTML simulator (no build step) that runs in any modern browser
- Fixed strike price & premium with adjustable stock price slider to explore different scenarios
- Color-coded visual elements to make key values easy to identify (strike/breakeven/current stock price)
- Crisp canvas rendering with device pixel ratio support for high-DPI displays
- Responsive design that works on desktop and mobile devices

### Educational Value
- **Call Options**: Learn when calls are profitable (ST > K + Premium)
- **Put Options**: Understand put profitability (ST < K - Premium)
- **Breakeven Analysis**: Visualize exact breakeven points for both option types
- **Risk/Reward Visualization**: See maximum loss (premium) vs. unlimited/limited profit potential
- **Professional Notation**: Proper use of S₀, ST, and K terminology

## Why This Repository

### For Students and Learners
- **Interactive Learning**: Adjust stock prices and immediately see how option payoffs change
- **Visual Understanding**: Grasp complex options concepts through interactive charts and real-time calculations
- **Both Option Types**: Compare call vs put strategies side-by-side
- **Mathematical Foundation**: See the actual formulas (max(ST-K,0) for calls, max(K-ST,0) for puts) in action

### For Educators
- **Classroom Ready**: No installation required - just open in any web browser
- **Teaching Tool**: Perfect for explaining options basics, breakeven analysis, and risk management
- **Customizable**: Easy to modify parameters for different teaching scenarios
- **Professional Presentation**: Clean, modern interface suitable for academic environments

### For Developers
- **Open Source**: Extend functionality with additional option strategies
- **Modern Web Technologies**: Built with HTML5 Canvas, CSS3, and vanilla JavaScript
- **No Dependencies**: Self-contained application with no external libraries
- **Educational Focus**: Codebase designed for clarity and educational value

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

## Screenshots

![Call Option Simulator](assets/screenshots/call%20option%20simulator%201.png)

*Interactive call and put options simulator showing real-time payoff calculations and educational formulas*

## How to Use

### Live Demo
Visit the live simulator: [https://manpreet-sangha.github.io/Options-Simulator/](https://manpreet-sangha.github.io/Options-Simulator/)

### Running Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/manpreet-sangha/Call-Option-Payoff-Simulator.git
   ```
2. Open `docs/index.html` in any modern web browser
3. No dependencies, build steps, or server required!

### Using the Simulator
1. **Choose Option Type**: Click "Call Option" or "Put Option" buttons
2. **Adjust Stock Price**: Use the slider to set stock price at expiration (ST)
3. **Observe Results**: Watch the chart update in real-time with payoff calculations
4. **Learn the Concepts**: Read the formulas and ITM/OTM/ATM indicators

### Key Parameters
- **Strike Price (K)**: Fixed at $80 for educational consistency
- **Premium**: $3 for both call and put options
- **Initial Stock Price (S₀)**: $80 (at-the-money start)
- **Stock Price Range**: $60 - $150 for comprehensive analysis

## Contact & Attribution

- **Created by**: [manpreet-sangha](https://github.com/manpreet-sangha)
- **Educational Use**: If you use this simulator in coursework, teaching, or publications, please include attribution: "Options Payoff Simulator by manpreet-sangha"
- **Issues & Support**: Use the GitHub Issues tab for bug reports and feature requests

---

*This simulator is designed as an educational tool for learning options trading concepts. It is not intended for actual trading decisions. Always consult with qualified financial advisors for investment decisions.*

```
