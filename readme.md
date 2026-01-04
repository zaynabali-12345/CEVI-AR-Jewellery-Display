# Luxury Jewellery Display – WebAR Concept

An interactive high-end jewellery showcase built using the **A-Frame WebXR framework**.  
The project presents a luxury “jewellery box” experience where users can explore and interact with multiple ring designs in a visually rich 3D environment.

---

## ✨ Features

- **Physically Based Rendering (PBR)** for realistic metallic rings
- **Dynamic lighting** with ambient, directional, and point lights
- **Three unique ring models** displayed inside a jewellery box
- **Smooth focus interaction**:
  - Click a ring to bring it forward
  - Scale-up animation for inspection
  - Contextual UI and background change
- **Return interaction**:
  - Close button restores original state
- **State-safe interaction**:
  - Only one ring can be active at a time
- **Continuous drag-to-rotate**:
  - Y-axis rotation only
  - Rotation is cumulative and proportional to drag distance
- **Minimal, luxury-inspired UI and typography**

---

## 🛠 Tech Stack

- **A-Frame 1.5.0**
- **WebGL / WebXR**
- **HTML, CSS, JavaScript**
- **GLB (gltf-binary) 3D models**

No external interaction libraries or starter templates were used.

---

## 📁 Project Structure

project/
├── index.html
├── resources/
│ └── models/
│ ├── ring1.glb
│ ├── ring2.glb
│ └── ring3.glb
---

## 🧠 Interaction Logic (ECS Approach)

- Each ring is an **A-Frame entity**
- Behaviour and state are managed through:
  - Entity attributes
  - Event listeners
  - Global interaction state
- No pre-built interaction components were used

---

## 🎮 Controls

| Action | Input |
|------|------|
| Select ring | Mouse click |
| Rotate ring | Click + drag (horizontal) |
| Exit focus | Close button |

---

## 🌐 Deployment

The project is deployed using **Netlify** and works directly in modern browsers without installation.

Project is deployed and accessible via a live link

Source code is pushed to GitHub with clear commit history

🔗 Live Demo: (add your deployed link here)
🔗 GitHub Repository: (add your repo link here)

📁 Local Setup Instructions
git clone <repository-url>
cd jewellery-box
open index.html


No additional build steps required.
Runs directly in a modern browser.

## 📌 Notes

- Designed for desktop browsers
- Touch rotation can be added if required
- Focused on visual quality and smooth interaction

---

## 👤 Author
Zaynab Ali