# 🧬 Biometric Vitamin Deficiency Diagnostic Matrix

An advanced computer-vision health informatics simulator that integrates client-side deep neural networks to extract biometric telemetry data from real-time webcam streams, mapping facial markers to potential micronutrient deficits and routing profile-optimized dietary solutions.

## 🚀 Architectural Systems
- **Computer Vision Face-API Pipeline:** Incorporates `face-api.js` running on a client-side TensorFlow.js micro-engine to initialize real-time face tracking and geometry landmark tracking natively within the browser, bypassing the need for external server-side computation.
- **Biometric Expression Extraction:** Continuously polls facial geometry confidence matrices via asynchronous intervals, automatically registering status vectors like physical exhaustion or strain without requiring manual form inputs.
- **Algorithmic Dietary Object Router:** Intercepts integrated inputs to parse a nested dietary configuration matrix (`standard`, `vegetarian`, `vegan`), dynamically stripping out lifestyle-incompatible food suggestions on the fly.
- **Cross-Layer Data Resolver:** Unifies real-time computer vision telemetry arrays with manual form-state checkbox data, feeding a consolidated data array into a conditional probability matching index.

## 🛠️ Technical Stack
- **Core AI/CV Layer:** TensorFlow.js, Face-API.js (TinyFaceDetector & FaceExpression Models)
- **Logic Engine:** Asynchronous JavaScript (Promises, SetInterval Polling Windows, ES6 Array Mapping)
- **Hardware Integration:** Web Hardware MediaDevices API (`navigator.mediaDevices.getUserMedia`)
- **Interface Layer:** HTML5 Semantic Nodes, CSS3 Fluid Grids, and View State Toggling Mechanics

## 💻 Live Production Build
Test the real-time neural network camera tracking setup directly via GitHub Pages:
👉 **[https://Sasipranvithaa.github.io/vitamindeficiency-detector/](https://Sasipranvithaa.github.io/vitamindeficiency-detector/)**
