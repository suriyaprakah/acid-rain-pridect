# 🌧️ Acid Rain Predictor v2

**AI-Powered Real-Time Acid Rain Detection & Analysis System**

A cutting-edge environmental web application that predicts acid rain pH levels using real-time weather and air quality data combined with Claude AI analysis.

## 🚀 Features

✅ **Real-Time pH Prediction** - Linear regression model with SO₂, NO₂, PM2.5 analysis
✅ **Claude AI Analysis** - FREE local AI analysis + optional premium Claude API integration
✅ **7-Day Forecast** - Predictive pH trends with automated analysis
✅ **Interactive Chat** - Ask Claude AI about acid rain impacts (requires API key)
✅ **Live Weather Data** - Integrated with Open-Meteo API for accurate readings
✅ **Beautiful UI** - Dark-themed, responsive design with real-time visualizations
✅ **No Backend Required** - 100% client-side, runs in any modern browser

## 📊 How It Works

1. **Search** any city (e.g., Chennai, Mumbai, Delhi)
2. **Get Results** instantly:
   - Current pH level and classification
   - Temperature, Humidity, Wind Speed
   - Pollutant levels (PM2.5, NO₂, SO₂)
   - AI-powered analysis & recommendations
3. **View Forecast** - 7-day predicted pH trends
4. **Chat with AI** - Ask questions about results (optional)

## 🔬 AI Model

**Linear Regression Formula:**
```
pH = 7.5
    - (NO₂ × 0.12)
    - (PM2.5 × 0.025)
    - (SO₂ × 0.018)         ★ Primary acid rain cause
    + (Humidity × 0.006)
    - (Temperature × 0.012)
    + (Wind Speed × 0.04)
```

**Acid Rain Threshold:** pH < 5.6

## 💡 Two AI Analysis Modes

### 🟢 FREE Local Analysis
- No API key needed
- Instant results
- Environmental assessment & recommendations
- Works offline

### ⭐ Claude AI Analysis (Optional)
- Premium insights from Claude Sonnet 4.6
- Deeper environmental impact analysis
- Health implications
- Actionable recommendations
- Requires free API key from [Anthropic](https://console.anthropic.com)

## 🌐 Live Demo

Open `acid-rain-predictor-v2.html` in any modern browser:
- Chrome, Firefox, Safari, Edge (all supported)
- No installation required
- Full offline capability (except API calls)

## 🔑 Getting Claude API Key (Optional)

1. Go to [Anthropic Console](https://console.anthropic.com)
2. Sign up for free account
3. Get $5 monthly free credits
4. Create API key
5. Paste in app when prompted

## 📁 Project Structure

```
acid-rain-predictor-v2/
├── acid-rain-predictor-v2.html    (Complete HTML app)
└── README.md                       (This file)
```

## 🛠️ Technologies Used

- **Frontend:** HTML5, CSS3, Vanilla JavaScript
- **APIs:**
  - Open-Meteo (Weather & Air Quality)
  - Nominatim (Reverse Geocoding)
  - Anthropic Claude (Optional AI)
- **Libraries:** Chart.js (Data Visualization)
- **Design:** Dark theme, responsive, accessible

## 📈 Acid Rain Classification

| pH Level | Classification | Health Impact |
|----------|-----------------|---------------|
| < 3.5 | 🔴 Extremely Critical | Immediate danger |
| 3.5 - 4.0 | 🔴 Extremely Acidic | Severe risk |
| 4.0 - 4.5 | 🟠 Strongly Acidic | High risk |
| 4.5 - 5.6 | 🟡 Acid Rain | Moderate risk |
| 5.6 - 6.5 | 🟢 Normal Rain | Safe (natural) |
| > 6.5 | 🔵 Alkaline | Excellent |

## 🌍 Main Pollution Sources

- **SO₂** (Sulphur Dioxide): Power plants, industrial burning
- **NO₂** (Nitrogen Dioxide): Vehicle emissions, factories
- **PM2.5**: Fine particle pollution from combustion

## 🚀 Deployment

### GitHub Pages (Free)
1. Create GitHub repo
2. Enable GitHub Pages in Settings
3. Access via: `https://yourusername.github.io/acid-rain-predictor-v2/`

### Netlify / Vercel (Alternative)
- Drag & drop `acid-rain-predictor-v2.html`
- Instant hosting with custom domain

## 📱 Browser Support

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🔐 Privacy

- No data sent to servers (except for API calls)
- No tracking or analytics
- All processing happens in your browser
- API keys stored locally only

## 📝 License

MIT License - Free to use and modify

## 🤝 Contributing

Got ideas? Found a bug? Feel free to fork and improve!

---

**Made with ❤️ for environmental awareness**

*Last Updated: April 15, 2026*
