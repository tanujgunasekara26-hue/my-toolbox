<html>
<body>
<!--StartFragment--><html><head></head><body><h1>🧰 My Toolbox</h1>
<blockquote>
<p><strong>21 Professional Desktop Tools in One Windows Application</strong></p>
</blockquote>
<p>A comprehensive, feature-rich desktop application built with Python and PySide6, bringing together everyday productivity, creativity, and system management tools — all in a single, elegant interface.</p>
<p><img src="https://img.shields.io/badge/version-2.0-blue" alt="Version">
<img src="https://img.shields.io/badge/python-3.14-blue" alt="Python">
<img src="https://img.shields.io/badge/PySide6-6.11.1-green" alt="PySide6">
<img src="https://img.shields.io/badge/license-MIT-green" alt="License">
<img src="https://img.shields.io/badge/platform-Windows%2010%2B-blue" alt="Windows"></p>
<hr>
<h2>✨ What's Inside?</h2>
<p>My Toolbox packs <strong>21 professional tools</strong> across seven categories, all accessible from a clean, modern dashboard with <strong>5 beautiful themes</strong>:</p>
<h3>🤖 AI Writing</h3>
<ul>
<li><strong>AI Chatbot</strong> — Chat with Cerebras AI for questions, brainstorming, and help</li>
<li><strong>AI Writing Tools</strong> — Grammar checking, tone adjustment, summarization, paraphrasing</li>
</ul>
<h3>📊 Conversion &amp; Calculation</h3>
<ul>
<li><strong>Calculator</strong> — Safe, AST-based math expression evaluator</li>
<li><strong>Unit Converter</strong> — 7 categories: length, weight, temperature, speed, area, volume, data</li>
<li><strong>Currency Converter</strong> — Live exchange rates from 40+ currencies (Frankfurter API)</li>
</ul>
<h3>🔐 Utilities</h3>
<ul>
<li><strong>Password Generator</strong> — Customizable secure passwords with strength meter</li>
<li><strong>Text Tools</strong> — Case conversion, word count, text analysis</li>
<li><strong>Developer Tools</strong> — JSON formatter, color converter, regex tester</li>
</ul>
<h3>⏱️ Productivity</h3>
<ul>
<li><strong>Notes</strong> — Plaintext note-taking with save/load and character count</li>
<li><strong>Timer</strong> — Countdown with circular visual progress ring</li>
<li><strong>Stopwatch</strong> — Precision timing with lap/split tracking</li>
<li><strong>Productivity Tools</strong> — Pomodoro timer, to-do lists, habit tracker</li>
</ul>
<h3>🖼️ Media &amp; Files</h3>
<ul>
<li><strong>QR Generator</strong> — Create QR codes from text or URLs</li>
<li><strong>QR Scanner</strong> — Scan codes from images or live webcam</li>
<li><strong>PDF Tools</strong> — Merge, split, extract, and watermark PDFs</li>
<li><strong>Image Tools</strong> — Resize, crop, convert formats, apply effects</li>
</ul>
<h3>💼 Business &amp; Learning</h3>
<ul>
<li><strong>Business Tools</strong> — Invoice generator, expense tracker</li>
<li><strong>Financial Tools</strong> — Loan calculator, investment analyzer</li>
<li><strong>Educational Tools</strong> — Flashcard maker, study timer, quizzes</li>
</ul>
<h3>🖥️ System &amp; Nostalgia</h3>
<ul>
<li><strong>System Info</strong> — Monitor CPU, RAM, storage, network in real-time</li>
<li><strong>Retro Windows</strong> — Vintage Windows XP/Vista sounds, wallpapers, and sample media</li>
</ul>
<hr>
<h2>📥 Installation</h2>
<h3>Pre-built Executable (Recommended)</h3>
<ol>
<li>Download the latest <code>.exe</code> from <a href="https://github.com/yourusername/my-toolbox/releases">Releases</a></li>
<li>Run <code>MyToolbox-Setup.exe</code> and follow the prompts</li>
<li>Launch from Start Menu or Desktop shortcut</li>
<li>Select a theme and start using all 21 tools</li>
</ol>
<h3>Run from Source</h3>
<p><strong>Prerequisites:</strong> Python 3.14, pip</p>
<pre><code class="language-bash"># Clone the repo
git clone https://github.com/yourusername/my-toolbox.git
cd my-toolbox

# Install dependencies
pip install -r requirements.txt --break-system-packages

# Run the app
python main.py
</code></pre>
<hr>
<h2>🚀 Getting Started</h2>
<ol>
<li><strong>Launch My Toolbox</strong> — Open the app from Start Menu or your desktop</li>
<li><strong>Pick a Theme</strong> — Choose from 5 built-in light/dark variants (settings menu)</li>
<li><strong>Explore Tools</strong> — Click any tool card on the dashboard to get started</li>
<li><strong>Read Docs</strong> — Visit <a href="https://claude.ai/chat/website/documentation.html">documentation.html</a> or the in-app Help menu for detailed guides</li>
</ol>
<h3>Set Up AI Features (US Only)</h3>
<p>The AI Chatbot and AI Writing Tools require a <strong>Cerebras API key</strong>:</p>
<ol>
<li>Sign up at <a href="https://cloud.cerebras.ai/">cloud.cerebras.ai</a></li>
<li>Generate an API key</li>
<li>Add it as an environment variable: <code>CEREBRAS_API_KEY=your-key-here</code></li>
<li>Restart My Toolbox</li>
</ol>
<p><strong>Note:</strong> AI features are restricted to users in the United States due to API export restrictions.</p>
<hr>
<h2>💻 System Requirements</h2>
<ul>
<li><strong>OS:</strong> Windows 10 or later</li>
<li><strong>CPU:</strong> Intel Core i5 (2nd Gen) or better</li>
<li><strong>RAM:</strong> 8GB minimum</li>
<li><strong>Storage:</strong> 500MB free space</li>
<li><strong>Internet:</strong> Required for AI, Currency Converter, and some other features</li>
<li><strong>Architecture:</strong> 64-bit recommended</li>
</ul>
<hr>
<h2>🏗️ Tech Stack</h2>

Technology | Purpose
-- | --
Python 3.14 | Core application language
PySide6 6.11.1 | Qt-based GUI framework
OpenCV | QR scanning, image processing
NumPy | Numerical computations
psutil | System monitoring
Requests | HTTP API calls (currency, AI)
Cerebras API | AI chatbot & writing tools
Frankfurter API | Live currency exchange rates


<hr>
<h2>📦 Project Structure</h2>
<pre><code>my-toolbox/
├── main.py                 # Entry point
├── home.py                 # Dashboard/home page
├── about.py                # About &amp; version info
├── calculator.py           # Math evaluator
├── currency_converter.py    # Live currency rates
├── qr_scanner.py           # QR scanning with OpenCV
├── timer.py                # Countdown timer
├── stopwatch.py            # Precision stopwatch
├── password_generator.py    # Secure password generation
├── unit_converter.py        # Multi-category converter
├── notes.py                # Note-taking
├── xp_apps_launcher.py     # Retro Windows experience
├── data/                   # Local storage (notes, etc.)
├── website/                # HTML documentation &amp; landing page
├── requirements.txt        # Python dependencies
├── README.md               # This file
└── LICENSE                 # MIT License
</code></pre>
<hr>
<h2>🎨 Features Highlight</h2>
<p>✅ <strong>21 Professional Tools</strong> — Everything you need, in one place<br>
✅ <strong>5 Beautiful Themes</strong> — Light and dark variants<br>
✅ <strong>Zero Telemetry</strong> — No tracking, no analytics, no ads<br>
✅ <strong>Free &amp; Open Source</strong> — MIT licensed, inspect the code anytime<br>
✅ <strong>AI-Powered</strong> — Cerebras API integration for smarter writing<br>
✅ <strong>Offline-Ready</strong> — Most tools work without internet<br>
✅ <strong>Lightweight</strong> — ~50MB on disk, fast startup<br>
✅ <strong>User-Friendly</strong> — Intuitive interface, built-in help</p>
<hr>
<h2>🔒 Privacy &amp; Security</h2>
<ul>
<li><strong>No Data Collection</strong> — Your data stays on your machine</li>
<li><strong>No Account Required</strong> — Run completely offline (except AI/currency tools)</li>
<li><strong>No Telemetry</strong> — Zero analytics or tracking</li>
<li><strong>Local Storage Only</strong> — Notes and preferences stored locally in plaintext</li>
<li><strong>API Transparency</strong> — See exactly what's sent to Cerebras and Frankfurter</li>
</ul>
<p>For details, see <a href="https://claude.ai/chat/website/privacy.html">Privacy Policy</a>.</p>
<hr>
<h2>🐛 Known Issues</h2>
<ul>
<li><strong>Windows SmartScreen Warning</strong> — Freshly built executables sometimes trigger false positives. Click "More info" → "Run anyway"</li>
<li><strong>AI Features US-Only</strong> — Geographic restriction enforced by Cerebras API</li>
<li><strong>Antivirus Alerts</strong> — May occur with new builds; use the official GitHub releases</li>
</ul>
<p>See the full <a href="https://claude.ai/chat/website/report.html">Known Issues</a> list in the app.</p>
<hr>
<h2>🤝 Contributing</h2>
<p>We welcome contributions! Here's how:</p>
<ol>
<li><strong>Fork</strong> the repository</li>
<li><strong>Create a branch</strong> for your feature: <code>git checkout -b feature/amazing-tool</code></li>
<li><strong>Commit changes</strong> with clear messages: <code>git commit -m "Add amazing-tool"</code></li>
<li><strong>Push to your fork</strong> and <strong>open a Pull Request</strong></li>
</ol>
<h3>Areas We Need Help With:</h3>
<ul>
<li>🐛 Bug reports and fixes</li>
<li>📝 Documentation improvements</li>
<li>🎨 UI/UX enhancements</li>
<li>🌐 New tool ideas</li>
<li>🔄 Performance optimization</li>
<li>🌍 Translation/localization</li>
</ul>
<p>See <a href="https://claude.ai/chat/CONTRIBUTING.md">CONTRIBUTING.md</a> (coming soon) for detailed guidelines.</p>
<hr>
<h2>📚 Documentation</h2>
<ul>
<li><strong><a href="https://claude.ai/chat/website/documentation.html">In-App Help</a></strong> — Complete user guides and troubleshooting</li>
<li><strong><a href="https://claude.ai/chat/website/features.html">Features</a></strong> — What makes My Toolbox special</li>
<li><strong><a href="https://claude.ai/chat/website/tools.html">Tools</a></strong> — Detailed breakdown of all 21 tools</li>
<li><strong><a href="https://claude.ai/chat/website/index.html">Website</a></strong> — Landing page and marketing site</li>
</ul>
<hr>
<h2>📝 License</h2>
<p>My Toolbox is licensed under the <strong>MIT License</strong> — see <a href="https://claude.ai/chat/LICENSE">LICENSE</a> for details.</p>
<p><strong>Important Note:</strong> This software includes assets belonging to Microsoft Corporation (Windows XP/Vista sounds, wallpapers) for personal, non-commercial use only. Windows® is a registered trademark of Microsoft Corporation.</p>
<hr>
<h2>👨‍💻 About the Developer</h2>
<p><strong>Tanuj</strong> from Sri Lanka 🇱🇰</p>
<p>Passionate about creating useful, no-nonsense tools and exploring retro computing. Built My Toolbox to bring together the everyday utilities everyone needs, wrapped in a modern, beautiful interface.</p>
<ul>
<li>🌐 <strong>Portfolio:</strong> <a href="https://your-website.com/">your-website.com</a></li>
<li>💼 <strong>LinkedIn:</strong> <a href="https://linkedin.com/in/yourprofile">your-linkedin</a></li>
<li>🐦 <strong>Twitter:</strong> <a href="https://twitter.com/yourhandle">@yourhandle</a></li>
</ul>
<hr>
<h2>🙏 Credits &amp; Acknowledgments</h2>
<ul>
<li><strong>PySide6</strong> — For the excellent Qt Python bindings</li>
<li><strong>OpenCV &amp; NumPy</strong> — Computer vision and numerical computing</li>
<li><strong>psutil</strong> — System monitoring library</li>
<li><strong>Cerebras</strong> — AI API integration</li>
<li><strong>Frankfurter</strong> — Open currency exchange rate API</li>
<li><strong>The Python Community</strong> — For amazing open-source libraries</li>
</ul>
<hr>
<h2>💬 Questions? Issues? Ideas?</h2>
<ul>
<li>🐛 <strong>Found a bug?</strong> — <a href="https://claude.ai/chat/website/report.html">Report it here</a></li>
<li>📚 <strong>Need help?</strong> — Check <a href="https://claude.ai/chat/website/documentation.html">Documentation</a></li>
<li>💡 <strong>Have a feature idea?</strong> — Open a GitHub Issue</li>
<li>💬 <strong>Want to contribute?</strong> — See <a href="https://claude.ai/chat/da5c92b9-075f-4e22-8b74-4145c423a449#-contributing">Contributing</a></li>
</ul>
<hr>
<h2>🚀 Roadmap (Future Plans)</h2>
<ul>
<li>[ ] macOS &amp; Linux support (via source installation)</li>
<li>[ ] Portable version (no installer needed)</li>
<li>[ ] Plugin/extension system</li>
<li>[ ] Cloud sync for notes (optional, privacy-first)</li>
<li>[ ] More AI features (image generation, code review)</li>
<li>[ ] Dark mode improvements</li>
<li>[ ] Performance optimizations</li>
<li>[ ] Localization (multiple languages)</li>
</ul>
<hr>
&lt;div align="center"&gt;
<p><strong>Made with ❤️ in Sri Lanka 🇱🇰</strong></p>
<p><a href="https://github.com/yourusername/my-toolbox">⭐ Star on GitHub</a> if you find this useful!</p>
<p><a href="https://github.com/yourusername/my-toolbox/releases">Download Now</a> · <a href="https://your-website.com/">View Website</a> · <a href="https://claude.ai/chat/website/documentation.html">Read Docs</a></p>
&lt;/div&gt;</body></html><!--EndFragment-->
</body>
</html># 🧰 My Toolbox

> **21 Professional Desktop Tools in One Windows Application**

A comprehensive, feature-rich desktop application built with Python and PySide6, bringing together everyday productivity, creativity, and system management tools — all in a single, elegant interface.

![Version](https://img.shields.io/badge/version-2.0-blue)
![Python](https://img.shields.io/badge/python-3.14-blue)
![PySide6](https://img.shields.io/badge/PySide6-6.11.1-green)
![License](https://img.shields.io/badge/license-MIT-green)
![Windows](https://img.shields.io/badge/platform-Windows%2010%2B-blue)

---

## ✨ What's Inside?

My Toolbox packs **21 professional tools** across seven categories, all accessible from a clean, modern dashboard with **5 beautiful themes**:

### 🤖 AI & Writing
- **AI Chatbot** — Chat with Claude AI for questions, brainstorming, and help
- **AI Writing Tools** — Grammar checking, tone adjustment, summarization, paraphrasing

### 📊 Conversion & Calculation
- **Calculator** — Safe, AST-based math expression evaluator
- **Unit Converter** — 7 categories: length, weight, temperature, speed, area, volume, data
- **Currency Converter** — Live exchange rates from 40+ currencies (Frankfurter API)

### 🔐 Utilities
- **Password Generator** — Customizable secure passwords with strength meter
- **Text Tools** — Case conversion, word count, text analysis
- **Developer Tools** — JSON formatter, color converter, regex tester

### ⏱️ Productivity
- **Notes** — Plaintext note-taking with save/load and character count
- **Timer** — Countdown with circular visual progress ring
- **Stopwatch** — Precision timing with lap/split tracking
- **Productivity Tools** — Pomodoro timer, to-do lists, habit tracker

### 🖼️ Media & Files
- **QR Generator** — Create QR codes from text or URLs
- **QR Scanner** — Scan codes from images or live webcam
- **PDF Tools** — Merge, split, extract, and watermark PDFs
- **Image Tools** — Resize, crop, convert formats, apply effects

### 💼 Business & Learning
- **Business Tools** — Invoice generator, expense tracker
- **Financial Tools** — Loan calculator, investment analyzer
- **Educational Tools** — Flashcard maker, study timer, quizzes

### 🖥️ System & Nostalgia
- **System Info** — Monitor CPU, RAM, storage, network in real-time
- **Retro Windows** — Vintage Windows XP/Vista sounds, wallpapers, and sample media

---

## 📥 Installation

### Pre-built Executable (Recommended)
1. Download the latest `.exe` or (installer file) from [[Releases](https://github.com/yourusername/my-toolbox/releases)](https://github.com/yourusername/my-toolbox/releases)
2. Run `MyToolbox-Setup.exe` and follow the prompts
3. Launch from Start Menu or Desktop shortcut
4. Select a theme and start using all 21 tools

### Run from Source
**Prerequisites:** Python 3.14, pip

```bash
# Clone the repo
git clone https://github.com/tanujgunasekara26-hue/my-toolbox.git
cd my-toolbox

# Install dependencies
pip install -r requirements.txt --break-system-packages

# Run the app
python main.py
```

---

## 🚀 Getting Started

1. **Launch My Toolbox** — Open the app from Start Menu or your desktop
2. **Pick a Theme** — Choose from 5 built-in light/dark variants (settings menu)
3. **Explore Tools** — Click any tool card on the dashboard to get started
4. **Read Docs** — Visit [[documentation.html](https://claude.ai/chat/website/documentation.html)](./website/documentation.html) or the in-app Help menu for detailed guides

### Set Up AI Features (US Only)
The AI Chatbot and AI Writing Tools require a **Cerebras API key**:
1. Sign up at [[cloud.cerebras.ai](https://cloud.cerebras.ai/)](https://cloud.cerebras.ai)
2. Generate an API key
3. Add it as an environment variable: `CEREBRAS_API_KEY=your-key-here`
4. Restart My Toolbox

**Note:** AI features are restricted to users in the United States due to API export restrictions.

---

## 💻 System Requirements

- **OS:** Windows 10 or later
- **CPU:** Intel Core i5 (2nd Gen) or better
- **RAM:** 4GB minimum
- **Storage:** 500MB free space
- **Internet:** Required for AI, Currency Converter, and some other features
- **Architecture:** 64-bit recommended

---

## 🏗️ Tech Stack

| Technology | Purpose |
|-----------|---------|
| **Python 3.14** | Core application language |
| **PySide6 6.11.1** | Qt-based GUI framework |
| **OpenCV** | QR scanning, image processing |
| **NumPy** | Numerical computations |
| **psutil** | System monitoring |
| **Requests** | HTTP API calls (currency, AI) |
| **Cerebras API** | AI chatbot & writing tools |
| **Frankfurter API** | Live currency exchange rates |

---

## 📦 Project Structure

```
my-toolbox/
├── main.py                 # Entry point
├── home.py                 # Dashboard/home page
├── about.py                # About & version info
├── calculator.py           # Math evaluator
├── currency_converter.py    # Live currency rates
├── qr_scanner.py           # QR scanning with OpenCV
├── timer.py                # Countdown timer
├── stopwatch.py            # Precision stopwatch
├── password_generator.py    # Secure password generation
├── unit_converter.py        # Multi-category converter
├── notes.py                # Note-taking
├── xp_apps_launcher.py     # Retro Windows experience
├── data/                   # Local storage (notes, etc.)
├── website/                # HTML documentation & landing page
├── requirements.txt        # Python dependencies
├── README.md               # This file
└── LICENSE                 # MIT License
```

---

## 🎨 Features Highlight

✅ **21 Professional Tools** — Everything you need, in one place  
✅ **5 Beautiful Themes** — Light and dark variants  
✅ **Zero Telemetry** — No tracking, no analytics, no ads  
✅ **Free & Open Source** — MIT licensed, inspect the code anytime  
✅ **AI-Powered** — Cerebras API integration for smarter writing  
✅ **Offline-Ready** — Most tools work without internet  
✅ **Lightweight** — ~50MB on disk, fast startup  
✅ **User-Friendly** — Intuitive interface, built-in help  

---

## 🔒 Privacy & Security

- **No Data Collection** — Your data stays on your machine
- **No Account Required** — Run completely offline (except AI/currency tools)
- **No Telemetry** — Zero analytics or tracking
- **Local Storage Only** — Notes and preferences stored locally in plaintext
- **API Transparency** — See exactly what's sent to Cerebras and Frankfurter

For details, see [[Privacy Policy](https://claude.ai/chat/website/privacy.html)](./website/privacy.html).

---

## 🐛 Known Issues

- **Windows SmartScreen Warning** — Freshly built executables sometimes trigger false positives. Click "More info" → "Run anyway"
- **AI Features US-Only** — Geographic restriction enforced by Cerebras API
- **Antivirus Alerts** — May occur with new builds; use the official GitHub releases

See the full [[Known Issues](https://claude.ai/chat/website/report.html)](./website/report.html) list in the app.

---

## 🤝 Contributing

We welcome contributions! Here's how:

1. **Fork** the repository
2. **Create a branch** for your feature: `git checkout -b feature/amazing-tool`
3. **Commit changes** with clear messages: `git commit -m "Add amazing-tool"`
4. **Push to your fork** and **open a Pull Request**

### Areas We Need Help With:
- 🐛 Bug reports and fixes
- 📝 Documentation improvements
- 🎨 UI/UX enhancements
- 🌐 New tool ideas
- 🔄 Performance optimization
- 🌍 Translation/localization

See [[CONTRIBUTING.md](https://claude.ai/chat/CONTRIBUTING.md)](./CONTRIBUTING.md) (coming soon) for detailed guidelines.

---

## 📚 Documentation

- **[[In-App Help](https://claude.ai/chat/website/documentation.html)](./website/documentation.html)** — Complete user guides and troubleshooting
- **[[Features](https://claude.ai/chat/website/features.html)](./website/features.html)** — What makes My Toolbox special
- **[[Tools](https://claude.ai/chat/website/tools.html)](./website/tools.html)** — Detailed breakdown of all 21 tools
- **[[Website](https://claude.ai/chat/website/index.html)](./website/index.html)** — Landing page and marketing site

---

## 📝 License

My Toolbox is licensed under the **MIT License** — see [[LICENSE](https://claude.ai/chat/LICENSE)](./LICENSE) for details.

**Important Note:** This software includes assets belonging to Microsoft Corporation (Windows XP/Vista sounds, wallpapers) for personal, non-commercial use only. Windows® is a registered trademark of Microsoft Corporation.

---

## 👨‍💻 About the Developer

**Tanuj** from Sri Lanka 🇱🇰

Passionate about creating useful, no-nonsense tools and exploring retro computing. Built My Toolbox to bring together the everyday utilities everyone needs, wrapped in a modern, beautiful interface.

- 🌐 **Portfolio:** [[your-website.com](https://your-website.com/)](https://your-website.com)
- 💼 **LinkedIn:** [[your-linkedin](https://linkedin.com/in/yourprofile)](https://linkedin.com/in/yourprofile)
- 🐦 **Twitter:** [[@yourhandle](https://twitter.com/yourhandle)](https://twitter.com/yourhandle)

---

## 🙏 Credits & Acknowledgments

- **PySide6** — For the excellent Qt Python bindings
- **OpenCV & NumPy** — Computer vision and numerical computing
- **psutil** — System monitoring library
- **Cerebras** — AI API integration
- **Frankfurter** — Open currency exchange rate API
- **The Python Community** — For amazing open-source libraries

---

## 💬 Questions? Issues? Ideas?

- 🐛 **Found a bug?** — [[Report it here](https://claude.ai/chat/website/report.html)](./website/report.html)
- 📚 **Need help?** — Check [[Documentation](https://claude.ai/chat/website/documentation.html)](./website/documentation.html)
- 💡 **Have a feature idea?** — Open a GitHub Issue
- 💬 **Want to contribute?** — See [[Contributing](https://claude.ai/chat/da5c92b9-075f-4e22-8b74-4145c423a449#-contributing)](#-contributing)

---

## 🚀 Roadmap (Future Plans)

- [ ] macOS & Linux support (via source installation)
- [ ] Portable version (no installer needed)
- [ ] Plugin/extension system
- [ ] Cloud sync for notes (optional, privacy-first)
- [ ] More AI features (image generation, code review)
- [ ] Dark mode improvements
- [ ] Performance optimizations
- [ ] Localization (multiple languages)

---

<div align="center">

**Made with ❤️ in Sri Lanka 🇱🇰**

[[⭐ Star on GitHub](https://github.com/yourusername/my-toolbox)](https://github.com/yourusername/my-toolbox) if you find this useful!

[[Download Now](https://github.com/yourusername/my-toolbox/releases)](https://github.com/yourusername/my-toolbox/releases) · [[View Website](https://your-website.com/)](https://your-website.com) · [[Read Docs](https://claude.ai/chat/website/documentation.html)](./website/documentation.html)

</div>
