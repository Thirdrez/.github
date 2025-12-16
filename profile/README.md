<div align="center">

# 🎭 Thirdrez

### **Cryptographically-Verified 3D Generative Motion**

Production-ready motion protocols for game engines, virtual worlds, and digital twin simulations.

[![Version](https://img.shields.io/badge/Release-v2.1.0-cyan?style=for-the-badge&labelColor=000)](https://github.com/Thirdrez/Support/releases/latest)
[![Paper](https://img.shields.io/badge/Research-Kinetiq_Whitepaper-purple?style=for-the-badge&labelColor=000)](https://thirdrez.com/research)
[![Status](https://img.shields.io/badge/System-Operational-emerald?style=for-the-badge&labelColor=000)](https://thirdrez.com/status)

<br/>

[![Website](https://img.shields.io/badge/🌐_thirdrez.com-111?style=for-the-badge&logo=vercel&logoColor=white)](https://thirdrez.com)
[![Discord](https://img.shields.io/badge/💬_Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com/invite/XyGmn4jkn4)

<br/>

![Divider](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

</div>

## 🛡️ MotionPrint™ Protocol

**The Standard for Cryptographic Provenance in 3D Motion.**

Thirdrez introduces **MotionPrint™**, a decentralized, client-side protocol for verifying the authenticity of 3D motion data. Unlike traditional DRM, MotionPrint utilizes **Ed25519 digital signatures** to seal unforgeable proof of authorship directly into animation metadata without altering the kinematic data structure.

### Technical Capabilities
- **Zero-Knowledge Verification**: Authenticates files completely offline/client-side using public key cryptography.
- **Data Integrity**: Ensures kinematic data (quaternions/vectors) has not been tampered with post-signature.
- **Cross-Platform**: Natively supported in `.GLB`, `.GLTF`, and `.BVH` containers. (*.FBX support in v2.0*)
- **Transparent Registry**: Decentralized verification via [thirdrez.com/motionprint/verify](https://thirdrez.com/motionprint/verify).

---

## ⚙️ Kinetiq Engine™

**Hybrid Generative Motion Synthesis.**

Kinetiq Engine represents a paradigm shift in animation authoring. It combines Large Motion Models (LMMs) trained on **Ecological Interaction Data** with deterministic physics solvers to produce production-grade motion that respects biomechanical constraints.

### Core Architecture
- **Neural Synthesis**: Text-to-Motion generation using latent diffusion models.
- **SQUAD Interpolation**: Spherical Quadrangle Interpolation for C2-continuous rotation smoothing, eliminating gimbal lock artifacts.
- **Adaptive Retargeting**: Real-time skeletal mapping for UE5 Mannequin, Unity Humanoid, and R15 rigs.
- **Physics-Aware Clean-up**: Automatic foot-plant detection and center-of-mass stabilization.

👉 **Access the Alpha**: [thirdrez.com/sandbox](https://thirdrez.com/sandbox)

---

## 🔬 Scientific Foundation

Our technology stack is built upon rigorous peer-reviewed research in computer graphics and cryptography.

| Protocol / Engine | Publication Title | Verified DOI |
|:------------------|:------------------|:-------------|
| **MotionPrint™** | *A Client-Side Cryptographic Provenance Protocol for 3D Motion Data* | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17843580.svg)](https://doi.org/10.5281/zenodo.17843580) |
| **Kinetiq Engine™** | *Hybrid Generative Motion Synthesis via Ecological Interaction Data* | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17849581.svg)](https://doi.org/10.5281/zenodo.17849581) |

---

## 🧬 Engineering Stack

We prioritize **safety, performance, and mathematical correctness** over convenience.

| Domain | Systems & Technologies |
| :--- | :--- |
| **Cryptography** | **Ed25519** (Elliptic Curve), **Merkle Trees** (Logs), **Offline Verification Protocol** |
| **Generative AI** | **MDM LoRA Fine-Tuning** (Adult/MF Styles), **NPY/NPZ Direct Translation**, **Biomechanical IK Solvers** |
| **High-Performance** | **Rust** (Cross-platform Bridge), **WebAssembly (WASM)**, **WebGL 2.0** (Three.js Custom Shaders) |
| **Infrastructure** | **Edge Computing Network**, **PostgreSQL** (Relational Data), **Distributed Object Storage** |

---

## 📦 Ecosystem

### Animation Marketplace
A curated library of 50,000+ cryptographically verified assets.
* **Support**: Unreal Engine 5, Unity, Roblox, Second Life.
* **Categories**: Combat, Locomotion, Dance, Athletics.
* [View Marketplace →](https://thirdrez.com/marketplace)

### Universal Converter
Enterprise-grade format conversion supporting 40+ 3D file types.
* **Capabilities**: FBX ↔ GLB ↔ BVH ↔ USC-Z.
* [Launch Converter →](https://thirdrez.com/convert)

---

## 📄 Licensing & IP

**Proprietary Software** — All rights reserved.

The MotionPrint protocol specification is open for review, but the implementation and Kinetiq Engine source code are proprietary. Assets purchased via the marketplace are governed by the [Standard Commercial License](https://thirdrez.com/terms).

---

<div align="center">

![Divider](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

### **Thirdrez Labs**

*Advancing the state of the art in digital motion.*

[Website](https://thirdrez.com) • [Documentation](https://thirdrez.com/motionprint/verified-motion) • [Twitter](https://x.com/ThirdrezHQ)

</div>
