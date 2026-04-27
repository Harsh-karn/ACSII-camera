<div align="center">
<img width="1200" height="475" alt="ASCII-CAM Banner" src="https://github.com/user-attachments/assets/0aa67016-6eaf-458a-adb2-6e31a0763ed6" />

# 🟢 ASCII-CAM v1.0
### **[LIVE DEMO](https://ascii-cam.vercel.app/)** | **Built by [HARSH KARN](https://github.com/Harsh-karn)**

---

**ASCII-CAM** is a high-fidelity, real-time camera-to-ASCII art converter with built-in Cyberpunk neural analysis. It transforms your standard webcam feed into a liquid-smooth digital terminal experience, utilizing cutting-edge AI for subject isolation and scene assessment.

</div>

## 🚀 Key Features

### 👁️ **Neural Analysis (Powered by Gemini 3.1)**
The "Scan & Analyze" protocols utilize the Gemini 3.1 Flash model to assess the subject. It provides:
- **Robotic Scene Assessment**: Detailed 2-sentence analysis of the subject.
- **Threat Level Check**: Automated risk assessment (LOW to CRITICAL).
- **Identifier Tags**: Metadata extraction for identifying subject attributes.

### 👤 **Subject Focus Mode (ResNet50)**
Unlike standard filters, ASCII-CAM uses the **ResNet50** Deep Learning architecture (via TensorFlow.js BodyPix) to isolate the human subject from the background. 
- **Digital Silhouette**: Toggles between "Full Frame" and "Subject Only" rendering.
- **High Precision**: Advanced neural masking ensures only the person is converted to code.

### 📼 **Cinematic Rendering**
- **Temporal Smoothing**: A custom low-pass filter eliminates ASCII jitter, resulting in a "liquid" movement feel.
- **Color Profiles**: Toggle between **Matrix Green**, **Retro Amber**, **B&W**, and **Full Color** modes.
- **Adjustable Density**: Four distinct character sets (Simple, Complex, Binary, Blocks) for varying levels of abstraction.

## 🛠️ Technology Stack

- **Frontend**: React + TypeScript + Vite
- **UI/Styling**: TailwindCSS + Lucide Icons
- **Computer Vision**: TensorFlow.js / BodyPix (ResNet50)
- **Neural Engine**: Google Generative AI (Gemini 1.5/3.1)
- **Sound Design**: Custom Cyberpunk SFX system

## 💻 Local Setup

### Prerequisites
- Node.js (v18+)
- A [Google AI Studio](https://aistudio.google.com/) API Key

### Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/Harsh-karn/ACSII-camera.git
   cd ACSII-camera
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```

3. **Configure Environment**:
   Create a `.env` file in the root directory:
   ```env
   GEMINI_API_KEY=your_api_key_here
   ```

4. **Launch Development Server**:
   ```bash
   npm run dev
   ```
   *The app will be accessible at `http://localhost:3000`*

## 📜 Deployment

The project is optimized for deployment on **Vercel**.
- **Important**: When deploying, ensure you add `GEMINI_API_KEY` to the Vercel "Environment Variables" settings.

## 🛡️ License

This project is developed by **HARSH KARN**. Feel free to use and adapt this for your own cyberpunk simulations.

---
<div align="center">
  <sub>TERMINAL_ID: 884-X | STATUS: CONNECTED</sub>
</div>
