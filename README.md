# 🌤️ Voice Weather Dashboard

A feature-packed weather application built with vanilla HTML/CSS/JS, featuring Web Speech voice search, persistent local storage, custom audio disaster alarms (floods/droughts/tornadoes), and historical climate data parsing.

---

### 🚀 Key Features

* **Voice-to-Text Search Engine**  
  Leverages the browser-native Web Speech API (`SpeechRecognition`) to let users query cities globally using hands-free voice commands.

* **Proactive Disaster Alarms**  
  Evaluates real-time hazard vectors from severe weather payload data. Triggers distinctive HTML5 Web Audio sirens for active tornado, flash flood, severe thunderstorm, or extreme drought warnings.

* **Persistent Cache (LocalStorage)**  
  Optimizes API quota thresholds and page load performance by storing user preferences, active dashboard configurations, and the home city cache locally.

* **Dynamic Typological Interface**  
  Replaces standard generic iconography with structural typography and layered background media that dynamically shifts configuration relative to localized meteorological classifications.

* **Weather Wisdom & Eco-Tips**  
  Features a dynamically cycling "Eco-Tip of the Day" panel, focused on localized green action items, resource conservation, and sustainability.

---

### 🤖 Future AI Framework Expansion

* **Predictive Climate Queries**  
  Planned implementation using the Google Gemini API coupled with a 5-year historical climate endpoint (`WeatherAPI`). This allows users to request micro-level historical probability analysis (e.g., *"Will it rain on 10 August?"*) parsed from physical multi-year trend patterns rather than simple short-term linear forecasts.

---

### 🛠️ Tech Stack & Architecture

* **Frontend Architecture** - HTML5 (Semantic Structure), CSS3 (Modern Flexbox/Grid, Glassmorphic Styling)
* **Core Logic Engine** - Vanilla JavaScript (ES6+ Asynchronous Fetch, Event-driven Logic)
* **Web APIs Integrated** - Web Storage API (`localStorage`), Web Speech API (`webkitSpeechRecognition`), Web Audio API
* **External Endpoints** - OpenWeatherMap API

---

### 📋 How to Run Locally

1. **Clone the repository** down to your local system:
   ```bash
   git clone https://github.com
   ```

2. **Navigate into the directory** structure:
   ```bash
   cd Voice-Weather-Dashboard-
   ```

3. **Launch the application**:  
   Open `index.html` directly in any modern web browser to execute.
