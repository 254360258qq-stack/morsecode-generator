# morsecode-generator
A web-based Morse code generator and translator tool for encoding/decoding text to Morse code. Live at [https://morsecode-generator.com](https://morsecode-generator.com)

---

## What is Morse Code Generator?
Morse Code Generator is a free online tool designed to simplify Morse code conversion. It enables users to encode plain text into standard Morse code and decode Morse code back to readable text, with intuitive controls and real-time feedback for both beginners and experienced users.

---

## Core Features
- **Bidirectional Conversion**: Instantly convert text to Morse code (dots `.` and dashes `-`) and Morse code back to text, supporting all standard ASCII characters.
- **Adjustable Audio Playback**: Customize Morse code audio with adjustable speed (words per minute, WPM) and tone frequency, mimicking real-world Morse code transmission.
- **Multi-Sensory Feedback**: Visualize Morse code with screen flashing and enable device vibration (mobile-compatible) for tactile learning and practice.
- **Quick Sharing Tools**: One-click copy of converted Morse code to clipboard, or share results directly via link for collaboration and learning.
- **Adaptive Design**: Fully responsive layout optimized for desktop, tablet, and mobile devices, ensuring a consistent experience across all screen sizes.
- **Theme Customization**: Toggle between light and dark modes to reduce eye strain in low-light environments or bright sunlight.

---

## Practical Applications
- Learn and practice Morse code for amateur radio (ham radio) licensing and operation.
- Create encrypted messages for recreational use, puzzles, or educational activities.
- Master Morse code for emergency communication and survival scenarios.
- Integrate Morse code learning into STEM and coding education curricula.

---

## Simple Usage Guide
1. Visit the live tool at [morse code generator](https://morsecode-generator.com)
2. **Encode Text to Morse Code**:
   - Enter your desired text in the input field.
   - Click the "Encode" button to generate corresponding Morse code.
   - Adjust playback settings (WPM/frequency) and click "Play" to hear the Morse code audio.
3. **Decode Morse Code to Text**:
   - Input Morse code using `.` (dots), `-` (dashes), and spaces (for letter separation).
   - Click "Decode" to translate Morse code back to plain text instantly.

---

## Why Choose This Tool?
- **100% Free & Unrestricted**: No registration, subscriptions, or paywalls—use the tool anytime, anywhere.
- **Lightning-Fast Performance**: Optimized codebase for fast load times and smooth operation, even on low-bandwidth connections.
- **Privacy-First Design**: All conversion logic runs locally in your browser—no data is stored or transmitted to external servers.
- **Open Source Transparency**: Full source code available on GitHub, allowing community contributions, audits, and customization.

---

## Technical Specifications
- **Frontend Framework**: Next.js (React) with Server-Side Rendering (SSR) and Static Site Generation (SSG) for enhanced performance and crawlability.
- **Styling**: Tailwind CSS (replace with your actual styling solution, e.g., CSS Modules/styled-components) for responsive, maintainable design.
- **Audio Engine**: Web Audio API for high-fidelity Morse code tone generation, integrated with Next.js client-side components.
- **Deployment**: Hosted on Vercel (Next.js official platform) with global CDN for low-latency access worldwide.
- **Browser Compatibility**: Supports all modern browsers (Chrome, Firefox, Safari, Edge) with polyfills for legacy browser compatibility.
- **Performance Optimizations**: Code splitting, lazy loading, and image optimization (Next.js built-in) for minimal load times and smooth interaction.
