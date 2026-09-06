# 🌿 Virtual Herbal Garden & Medicinal Plants Guide

Welcome to the **Virtual Herbal Garden**, a comprehensive and interactive web application designed to educate users about traditional medicine systems and their healing flora. Explore the secrets of Ayurveda, Unani, Siddha, Naturopathy, and Homeopathy in an engaging, visually rich, and interactive environment.

---

## 🌟 Key Features

1. **Stunning Welcome Landing (`welcome.html`)**
   - High-fidelity visual landing page built using modern CSS glassmorphism.
   - Ambient floating orbs and micro-animations to enhance user engagement.
   - Interactive typing text effect to introduce the application.

2. **Categorized Plant Guide & 3D Viewer (`start.html`)**
   - Explore plants organized by traditional medicine systems:
     * 🍃 **Ayurveda**: Tulsi, Ashwagandha, Neem, Amla, Aloe Vera
     * 🌿 **Unani**: Senna, Asrol, Banafsha, Gulab, Zanjabeel
     * 🌱 **Siddha**: Thoothuvalai, Nilavembu, Adathoda, Karisalankanni
     * 🥗 **Naturopathy**: Spinach, Carrot, Turmeric, Cucumber
     * 💊 **Homeopathy**: Arnica, Belladonna, Nux Vomica, Calendula
   - Integration with Google’s `<model-viewer>` for full 3D interaction (`.glb` models) with zoom and rotate controls directly in the browser.
   - Seamless "Add to Cart" capability stored locally using browser Storage.

3. **Interactive Voice & Handbook Quiz (`finalvoice.html`)**
   - **Diagnosis Quiz**: Put your herbal knowledge to the test by matching symptoms/uses with the correct medicinal plants.
   - **Digital Handbook**: Quickly look up plants classified by their systems and benefits.
   - **Voice Suggest Mode**: Ask or speak symptom keywords using the Web Speech API (supports Speech Recognition & Speech Synthesis) to hear matching herbal solutions spoken back to you!

4. **Interactive Shopping Cart & Checkout (`cart.html`)**
   - Live summary of your selected plants.
   - Custom quantity selectors and price calculators.
   - User delivery address and contact form validation.
   - Simulated secure order confirmation with an aesthetic confirmation pop-up.

---

## 📂 Project Structure

```text
PROJECT RTP/
│
├── welcome.html          # Application landing entrance page
├── start.html            # Main catalogue grid, categorization, & 3D viewer
├── finalvoice.html       # Voice-enabled diagnosis quiz and handbook
├── cart.html             # Shopping cart and checkout form simulator
│
└── pictures/             # Image assets, 3D glb models, & subdirectories
    ├── Aloe Vera Plant.glb
    ├── tulsi.glb
    ├── gulab.glb
    ├── neem.glb
    ├── turmeric.jpeg
    ├── (other plant images & glb directories...)
```

---

## 🚀 How to Run the Project

1. **Locally opening files**:
   - Clone or download this project directory.
   - Double-click [welcome.html](file:///C:/Users/VIGNESHWAR%20REDDY/Documents/PROJECT%20RTP/welcome.html) to run it in your browser.
   - Navigate pages using the internal links (e.g., "Explore Garden", "Take a Quiz", "View Cart").

2. **Voice Features**:
   - The interactive **Voice Suggest** feature requires Chrome or another web browser supporting the Web Speech API. Make sure to grant microphone permissions when prompted.

3. **3D Models**:
   - Make sure all `.glb` assets in `pictures/` are present to view specific models locally. In cases where the local model path is missing or has a different format, the application falls back to showing an interactive model.

---

## 🛠️ Built With

- **HTML5** & **CSS3** (Fluid layouts, Outfit & Poppins Typography, Glassmorphic styling, Grid & Flexbox)
- **JavaScript** (Vanilla JS DOM API, LocalStorage integration)
- **Model Viewer API** (Google web components for interactable 3D graphics)
- **Web Speech API** (SpeechRecognition and SpeechSynthesis)

---

*Made with 💚 by Vignesh*
