@@ -1,115 +1,266 @@
<img width="3188" height="1202" alt="frame (3)" src="https://github.com/user-attachments/assets/517ad8e9-ad22-457d-9538-a9e62d137cd7" />


# Auto Negotiation Simulator 🎯


## Basic Details
### Team Name: Avial


### Team Members
- Team Lead: Rishit Menon - TKM College of Engineering

### Project Description
Auto-Rickshaw Negotiation Simulator is a hilarious experience where you practice the fine art of haggling with Kerala auto drivers. Conquer negotiation challenges in iconic Kochi and Kerala locations, from the dreaded "Airport Mode" to the friendly "Local Uncle Mode."

### The Problem (that doesn't exist)
You're absolutely hopeless at bargaining with auto drivers—especially in unpredictable Kerala traffic, where every meter is an adventure and every fare is a fresh battle for your wallet and pride.

### The Solution (that nobody asked for)
A virtual rickshaw ride with AI-powered, personality-packed, and stubborn auto drivers. Master your negotiation tactics—try everything from pleading in pure Malayalam to hinting that your grandfather built this city, without ever stepping outside. Achieve legendary bargaining status, and unlock secret dialogue trees like "Super Angry Driver" and "Sympathetic Onlooker Auntie."

## Technical Details
## Technologies/Components Used
## For Software:
## Languages Used:
HTML5 - Structure and VR scene definition using A-Frame
CSS3 - Styling, animations, and responsive design with Flexbox/Grid
JavaScript (ES6+) - Game logic, AI integration, and interactive features
Mermaid - Architecture diagrams and workflow visualization
## Frameworks Used:
A-Frame 1.4.0 - WebVR framework for immersive 3D environments
WebVR/WebXR APIs - Native browser VR support
Web Speech API - Voice recognition and synthesis
## Libraries Used:
OpenAI API - GPT-4o-mini & GPT-3.5-turbo for dynamic AI responses
Anthropic Claude - Alternative AI provider for enhanced conversations
Ollama - Local AI model support for offline functionality
Local Storage API - Data persistence for achievements and leaderboards
## Tools Used:
Browser Dev Tools - Debugging and performance optimization
Git - Version control and project management
HTTP Server - Local development and testing environment
Console Testing - Custom debug functions and validation
Implementation
## For Software:
Installation
Clone or download the project
git clone [repository-url]
cd useless_auto

Start local HTTP server (required for VR features)
python -m http.server 8000

Alternative for Node.js users
npx http-server -p 8000

Alternative for PHP users
php -S localhost:8000


# Run
Open your browser and navigate to:
http://localhost:8000

For testing specific features:
http://localhost:8000/test.html          # Feature overview
http://localhost:8000/tutorial-test.html # Tutorial system testing
http://localhost:8000/immediate-test.html # Debug pricing issues

VR Mode:
 1. Connect VR headset (Oculus, HTC Vive, etc.)
 2. Click "Enter VR" button in browser
 3. Use hand controllers or gaze+click interaction

### Project Documentation
For Software:

# Screenshots (Add at least 3)
![Screenshot1](Add screenshot 1 here with proper name)
*Add caption explaining what this shows*

![Screenshot2](Add screenshot 2 here with proper name)
*Add caption explaining what this shows*

![Screenshot3](Add screenshot 3 here with proper name)
*Add caption explaining what this shows*

# Diagrams
<img width="410" height="876" alt="image" src="https://github.com/user-attachments/assets/9451e320-c88b-4053-8efe-2738ac69aefd" />
<img width="748" height="818" alt="image" src="https://github.com/user-attachments/assets/aa73f9f9-ce05-4800-aaf7-74ce13f83728" />
<img width="661" height="832" alt="image" src="https://github.com/user-attachments/assets/5511ce34-8c0d-4585-88dd-b5d841c0981d" />

System Architecture showing the modular design with frontend VR layer, core game logic, AI intelligence systems, feature modules, external API integrations, and data persistence layer.
AI Decision Flow demonstrating how player input is analyzed, processed through multiple AI layers, and converted into contextual driver responses with personality and cultural awareness.
Game Workflow illustrating the complete player journey from game start through location selection, negotiation rounds, AI processing, and final scoring with achievement tracking.

### Project Demo
# Video
[Add your demo video link here]
*Explain what the video demonstrates*


## Team Contributions
- Rishit Menon: Entire Project


---
Made with ❤️ at TinkerHub Useless Projects 

![Static Badge](https://img.shields.io/badge/TinkerHub-24?color=%23000000&link=https%3A%2F%2Fwww.tinkerhub.org%2F)
![Static Badge](https://img.shields.io/badge/UselessProjects--25-25?link=https%3A%2F%2Fwww.tinkerhub.org%2Fevents%2FQ2Q1TQKX6Q%2FUseless%2520Projects)
