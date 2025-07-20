# 🔥 BhasadGrid: Real-Time Chaos Dashboard

Welcome to **BhasadGrid**, a 🔊 Firestore-powered zone dashboard that visualizes event chaos in **real-time** using emoji-reactive cards, alert effects, and expressive styling. Designed for DJ-mode vibes, rave-floor tracking, and zone-level monitoring.

Built solo by [@aroraashutosh](https://github.com/aroraashutosh) — blending tech precision with cultural madness 💥

---

## 🌐 Live Demo  
👉 [Click to Experience](https://aroraashutosh.github.io/BhasadGrid/)

---

## ⚙️ Features

- 🧱 **Zone Cards** with emoji and live Firestore data  
- 🚨 **Blink Alerts** for high-status zones  
- 📊 **Tooltips** show density & velocity per zone  
- 🎛️ **Summary Bar** tracks chaos, steady, chill zones  
- 🌈 **Animated Gradient Background**  
- 🔧 Firebase-powered with real-time `onSnapshot()` updates

---

## 📦 Tech Stack

- Firebase & Firestore  
- HTML, CSS, Vanilla JavaScript  
- GitHub Pages Hosting

---

## 🧠 Use-Cases

- 🎧 DJ booth crowd monitor  
- 🎉 Event zone live tracker  
- 🎮 Chaos-powered dashboards  
- 🪩 Gen Z branding experiments  
- 🚪 Entry/exit zone status mapping

---

## 🔧 Setup Guide

1. Clone this repo  
2. Add your Firebase config inside the `<script>` block in `index.html`  
3. Create Firestore collection: `zones`  
4. Add zone documents with fields:

```json
{
  "name": "DJ Booth",
  "status": "high",
  "density": 85,
  "velocity": 3.1
}
