<!-- 
======================================================================
  SHIVA YADAV | GITHUB PROFILE README
====================================================================== 
-->

<!-- DYNAMIC TYPING HEADER -->
<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=26&pause=1000&color=9C27B0&center=true&vCenter=true&width=800&lines=Systems+Software+Engineer;Building+1.58-bit+Ternary+AI+Runtimes;OS+Internals+%26+Binary+Execution;Robotics+%26+Edge+AI+Developer" alt="Typing SVG" />
</div>

<p align="center">
  <a href="https://linkedin.com/in/shiva-yadav1">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:shiva@quantvelozentra.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

<!-- PROFILE VIEW TRACKER -->
<div align="center">
  <img src="https://komarev.com/ghpvc/?username=Shiva-2908&label=Profile%20Views&color=9C27B0&style=for-the-badge" alt="Profile Views Tracker" />
</div>

<br>

<h3 align="center">I build at the absolute boundary where software meets the OS, hardware execution layers, and physical robotics.</h3>

---

## 👨‍💻 About Me & Current Focus

I am a systems developer and AI researcher currently pursuing my **B.Sc. in Artificial Intelligence in Robotics and Intelligent Systems** at **Galgotias University**.

My core engineering philosophy is learning by building from first principles. Rather than relying on heavyweight abstractions or high-level wrappers, I focus on the layers beneath the frameworks: how a model's weights actually sit in memory, how an executable loader maps virtual addresses, and how the OS kernel schedules execution.

Currently, I am architecting solutions across three interconnected domains:

1. **Extreme AI Quantization & Runtimes:** I bridge the gap between high-level Python AI development and low-level hardware execution. My primary focus is converting massive foundation models into highly compressed **1.58-bit ternary formats**, requiring custom runtime architectures in Rust and C++ to execute efficiently on constrained edge devices.
2. **Operating Systems & Binary Execution:** Exploring the internal mechanics of operating systems, specifically cross-platform execution models. I study executable formats (PE, ELF), ABI behaviors, syscall translations, and memory mapping.
3. **Intelligent Robotics & Hardware Integration:** Deploying embedded AI onto physical hardware. I focus on bridging autonomous algorithms with edge compute platforms (like NVIDIA Jetson Nano) to create high-throughput, low-latency robotic telemetry systems.

---

## ⚡ Technical Arsenal

<table>
  <tr>
    <td valign="top" width="33%">
      <h3>Systems & Core</h3>
      <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" alt="Rust" /><br><br>
      <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++" /><br><br>
      <img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black" alt="C" /><br><br>
      <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white" alt="C#" /><br><br>
      <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
    </td>
    <td valign="top" width="33%">
      <h3>AI & Python Dev</h3>
      <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" /><br><br>
      <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch" /><br><br>
      <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy" /><br><br>
      <img src="https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white" alt="SciPy" /><br><br>
      <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV" />
    </td>
    <td valign="top" width="34%">
      <h3>Robotics & OS</h3>
      <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" /><br><br>
      <img src="https://img.shields.io/badge/NVIDIA_Jetson-76B900?style=for-the-badge&logo=nvidia&logoColor=white" alt="NVIDIA Jetson" /><br><br>
      <img src="https://img.shields.io/badge/ROS-22314E?style=for-the-badge&logo=ros&logoColor=white" alt="ROS" /><br><br>
      <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white" alt="Bash" /><br><br>
      <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
    </td>
  </tr>
</table>

---

## 🚀 Flagship Architecture & Research

### 1. TERNOS: 1.58-Bit AI Quantization Engine & Runtime
An independent framework designed to convert standard full-precision foundation models into 1.58-bit ternary weight representations `{-1, 0, 1}`.

* **The Engineering Challenge:** Standard FP16/INT8 inference relies on heavy matrix multiplication operations (MAC units), which drain power and memory on edge computing devices.
* **The TERNOS Solution:** By mapping weights to three discrete states, TERNOS replaces massive matrix-multiplication bottlenecks with highly optimized addition and subtraction routines. The result is a near-lossless compression that vastly accelerates inference latency.

<br>

### 2. QVZ-LOW: Windows on Linux Execution Layer
An independent systems project exploring cross-platform binary execution by re-implementing the Windows PE (Portable Executable) loader and execution model natively on Linux from scratch, completely bypassing standard high-level emulators.

* **Section & Header Mapping:** Custom PE loader handling raw section mapping and header parsing into virtual memory.
* **Symbol Resolution & Relocation:** Dynamic resolution of import directories and manual base relocations.
* **Thread Contexts:** Initialization of runtime thread contexts for PE32/PE32+ binaries.
* **ABI Translation Layer:** Direct ABI translation mapping Microsoft x64 calling conventions to System V AMD64 ABI syscalls.

<br>

### 3. Intelligent Robotics & Autonomous Edge AI
Bridging complex AI software with physical hardware constraints. My robotics work relies heavily on deploying optimized AI and computer vision models directly onto resource-constrained embedded platforms to execute real-time decisions without cloud dependency.

* **Hardware Integrations:** NVIDIA Jetson Nano architecture, drone flight controllers, and embedded sensor suites.
* **Software Pipelines:** Real-time data processing, telemetry analysis, and environmental mapping using Python, OpenCV, and custom C++ acceleration.

---

## 📊 Developer Metrics & Trackers

<div align="center">
  <img src="https://streak-stats.demolab.com?user=Shiva-2908&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</div>

<br>

<div align="center">
  <table>
    <tr>
      <td width="50%" align="center">
        <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Shiva-2908&theme=tokyonight" alt="GitHub Profile Details" width="100%" />
      </td>
      <td width="50%" align="center">
        <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Shiva-2908&theme=tokyonight" alt="Top Languages" width="100%" />
      </td>
    </tr>
    <tr>
      <td colspan="2" align="center">
        <img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=Shiva-2908&theme=tokyonight" alt="Productive Time" width="100%" />
      </td>
    </tr>
  </table>
</div>

---
