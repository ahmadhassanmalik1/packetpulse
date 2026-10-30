# PacketPulse — Real-Time Network Telemetry & Oscilloscope Engine

> A high-performance, client-side network diagnostics suite and live latency oscilloscope built with native browser Performance APIs and 60 FPS HTML5 Canvas.

[![Live Demo](https://img.shields.io/badge/Live_Demo-PacketPulse-00f2fe?style=for-the-badge&logo=googlechrome&logoColor=white)](https://ahmadhassanmalik1.github.io/packetpulse/)
[![Engine](https://img.shields.io/badge/Core-Vanilla_JS_&_Canvas-orange?style=for-the-badge)](https://ahmadhassanmalik1.github.io/packetpulse/)
[![Architecture](https://img.shields.io/badge/Performance-Zero_Dependency-success?style=for-the-badge)](#)

---

## ⚡ Overview

**PacketPulse** is a lightweight, zero-dependency network observability console designed to visualize network latency, jitter, packet stability, and DNS resolution speeds in real time. 

Instead of relying on synthetic or heavy third-party dashboard libraries, PacketPulse leverages the browser's native **Resource Timing API** and an optimized **HTML5 Canvas 2D spline rendering engine** running at a locked 60 frames per second to deliver hardware-accelerated telemetry telemetry visuals.

---

## ✨ Key Features

- **Real-Time Oscilloscope Waveform:** 
  Renders continuous live network jitter and latency curves using bezier interpolation on a hardware-accelerated HTML5 Canvas at 60 FPS.
- **Micro-Telemetry Metrics:** 
  Captures Round Trip Time (RTT), Jitter variance, Packet loss estimation, and throughput consistency.
- **Multi-Region Ping Probes:** 
  Simulates latency telemetry checks against edge points and global CDNs without backend middleware dependencies.
- **Zero-Dependency Architecture:** 
  Built purely with vanilla JavaScript, modern CSS, and HTML5 Canvas — optimized for instant load times and negligible memory overhead.
- **Adaptive Dark Mode UI:** 
  Engineered with high-contrast obsidian backgrounds, neon telemetry waves, and clean tabular monospace readouts for terminal-grade aesthetics.

---

## 🛠️ Architecture & Tech Stack

| Layer | Technology | Purpose |
| :--- | :--- | :--- |
| **Telemetry Engine** | Native Resource Timing & Performance API | High-resolution timestamp collection & latency calculations |
| **Visualizer Pipeline** | HTML5 Canvas 2D API | Low-latency spline waveform rendering at 60 FPS |
| **Logic & State** | Modern ES6+ JavaScript | Rolling data arrays, mathematical jitter calculations |
| **Styling & UI** | CSS3 Grid, Flexbox & Custom Glassmorphism | Responsive telemetry console interface |

---

## 🚀 Live Demo

Experience the live telemetry oscilloscope engine directly in your browser:

👉 **[Launch PacketPulse Telemetry Console](https://ahmadhassanmalik1.github.io/packetpulse/)**

---

## 🔒 Source & Architecture Notes

This repository contains the system documentation, specifications, and architecture notes for PacketPulse. The compiled runtime build is continuously deployed via isolated deployment pipelines.

*Engineered with precision for low-overhead browser performance testing.*
