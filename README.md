<p align="center">
  <img src="assets/banner.svg" width="100%" alt="Javidan Bandaliyev — CS student at ELTE building software for embedded systems and automation">
</p>

<p align="center">
  <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=17&duration=2600&pause=900&color=E3A15E&center=true&vCenter=true&width=640&lines=Java+Developer;Automation+%C2%B7+Embedded+Systems;AI+%C2%B7+Computer+Vision;software+that+meets+the+physical+world" alt="Java Developer · Automation · AI · software that meets the physical world"></a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/javidan-bandaliyev-7b3ba6278/"><img src="https://img.shields.io/badge/LinkedIn-connect-8A6A50?style=flat-square&logo=linkedin&logoColor=white&labelColor=161B22" alt="LinkedIn"></a>
  <img src="https://img.shields.io/badge/ELTE-BSc%20CS%20%C2%B7%202025%E2%80%932028-E3A15E?style=flat-square&labelColor=161B22" alt="ELTE BSc Computer Science">
</p>

<br>

<img src="assets/h-01.svg" width="100%" alt="01 About">

I build things, break them, figure out why they broke — and make them better.

My comfort zone is the messy middle between code and hardware: automation, embedded systems, things that blink, beep and occasionally catch fire *(only once)*. I'm just as much at home in AI and machine learning — from training and fine-tuning models to wiring them into systems that actually do something.

Java is my home language (fittingly — friends call me **Java**), but I'll pick up whatever the problem needs.

```text
◆ studying     BSc Computer Science @ ELTE Budapest
◆ worked       PLC development intern @ Holcim Azerbaijan
◆ speaks       Azerbaijani & Russian (native) · English C1 · Turkish B2
```

<br>

<img src="assets/h-02.svg" width="100%" alt="02 Toolbox">

<table align="center">
  <tr>
    <td align="center" colspan="2">
      <sub><b>LANGUAGES</b></sub><br><br>
      <img src="https://skillicons.dev/icons?i=java,c,cpp,cs,py,haskell,js,ts&theme=dark" height="48" alt="Java, C, C++, C#, Python, Haskell, JavaScript, TypeScript">
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <sub><b>WEB · BACKEND · VISION</b></sub><br><br>
      <img src="https://skillicons.dev/icons?i=html,css,fastapi,opencv&theme=dark" height="48" alt="HTML, CSS, FastAPI, OpenCV">
    </td>
    <td align="center" width="50%">
      <sub><b>HARDWARE · AUTOMATION</b></sub><br><br>
      <img src="https://skillicons.dev/icons?i=arduino,raspberrypi&theme=dark" height="48" alt="Arduino, Raspberry Pi"><br>
      <img src="https://img.shields.io/badge/ESP32--S3-B8733F?style=flat-square&logo=espressif&logoColor=white" alt="ESP32-S3">
      <img src="https://img.shields.io/badge/PlatformIO-B8733F?style=flat-square&logo=platformio&logoColor=white" alt="PlatformIO">
      <img src="https://img.shields.io/badge/Embedded_C%2FC%2B%2B-8A6A50?style=flat-square" alt="Embedded C/C++"><br>
      <img src="https://img.shields.io/badge/Siemens_TIA_Portal-8A6A50?style=flat-square&logo=siemens&logoColor=white" alt="Siemens TIA Portal">
      <img src="https://img.shields.io/badge/PLC-8A6A50?style=flat-square" alt="PLC">
      <img src="https://img.shields.io/badge/YOLO-B8733F?style=flat-square" alt="YOLO">
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <sub><b>TESTING · DATA</b></sub><br><br>
      <img src="https://img.shields.io/badge/JUnit-B8733F?style=flat-square&logo=junit5&logoColor=white" alt="JUnit">
      <img src="https://img.shields.io/badge/NumPy-8A6A50?style=flat-square&logo=numpy&logoColor=white" alt="NumPy">
      <img src="https://img.shields.io/badge/SQL-8A6A50?style=flat-square" alt="SQL">
    </td>
    <td align="center" width="50%">
      <sub><b>OPERATING SYSTEMS</b></sub><br><br>
      <img src="https://img.shields.io/badge/macOS-3A2E26?style=flat-square&logo=apple&logoColor=white" alt="macOS">
      <img src="https://img.shields.io/badge/Linux-3A2E26?style=flat-square&logo=linux&logoColor=white" alt="Linux">
      <img src="https://img.shields.io/badge/Windows-3A2E26?style=flat-square" alt="Windows">
    </td>
  </tr>
  <tr>
    <td align="center" colspan="2">
      <sub><b>WORKFLOW · INFRA</b></sub><br><br>
      <img src="https://skillicons.dev/icons?i=git,github,gitlab,githubactions,docker,cloudflare&theme=dark" height="48" alt="Git, GitHub, GitLab, GitHub Actions, Docker, Cloudflare">
    </td>
  </tr>
</table>

<br>

<img src="assets/h-03.svg" width="100%" alt="03 Featured builds">

### 03.1 · Assistive Vision Glasses

Smart glasses that turn camera and distance readings into short spoken directions and left/right buzzer cues.

<a href="https://github.com/ax1le28/assistive-vision-glasses">
  <img src="assets/vision-pipeline.svg" width="100%" alt="Architecture: ESP32-S3 sends frames and ultrasonic distance to a FastAPI backend running YOLO11n, distance fusion and navigation, which drives speech and left/right buzzers">
</a>

<details>
<summary>How it works · stack</summary>

An **ESP32-S3** streams camera frames and **HC-SR04** readings to a **FastAPI** backend. Local **YOLO** detection and distance fusion score left, center and right paths; stair warnings, smoothing and speech throttling keep the cues useful.

`Python` `FastAPI` `Ultralytics YOLO` `OpenCV` `ESP32-S3` `PlatformIO` `ElevenLabs TTS` `GitHub Actions`

</details>

<a href="https://github.com/ax1le28/assistive-vision-glasses"><img src="https://img.shields.io/badge/view_project-%E2%86%97-B8733F?style=for-the-badge&labelColor=161B22" alt="View project"></a>

---

### 03.2 · Sketch2Machine

Turn a hand-drawn state machine into an editable simulation with execution traces and generated test coverage. Four built-in examples run without an API key.

<a href="https://github.com/ax1le28/sketch2machine">
  <img src="assets/sketch-workbench.svg" width="100%" alt="A hand-drawn even-parity state machine becomes a running digital machine with a visible trace and transition coverage">
</a>

<details>
<summary>How it works · stack</summary>

<a href="https://github.com/ax1le28/sketch2machine">
  <img src="assets/sketch-pipeline.svg" width="100%" alt="Sketch2Machine pipeline: Claude Vision transcribes a drawing, Java normalizes it, and the browser simulates, analyzes and tests the machine">
</a>

**Claude Vision** transcribes a photo into a typed Java record. The normalizer resolves labels and logs repairs; the Java engine simulates the machine, flags issues and generates coverage tests. Recognizing your own photos requires an Anthropic API key.

`Java 21` `Claude Vision` `Anthropic Java SDK` `Cytoscape.js` `Maven` `JUnit 5` `GitHub Actions`

</details>

<a href="https://github.com/ax1le28/sketch2machine"><img src="https://img.shields.io/badge/view_project-%E2%86%97-B8733F?style=for-the-badge&labelColor=161B22" alt="View project"></a>

---

### 03.3 · PromptFuzzer

<img src="https://img.shields.io/badge/status-in_development-E3A15E?style=flat-square&labelColor=161B22" alt="Status: in development">

Fuzz testing for LLM features. One seed example becomes dozens of adversarial inputs, each sent to a real model and graded by code first. The result is a reliability report that shows exactly where the prompt breaks.

<a href="https://github.com/ax1le28/fuzzer">
  <img src="assets/fuzzer-pipeline.svg" width="100%" alt="PromptFuzzer: a terminal streams fuzzed inputs with pass and fail marks, next to a sample reliability report comparing two models at 92.6% and 55.3% with 95% confidence intervals and pass rates by category">
</a>

<details>
<summary>How it works · stack</summary>

An LLM writes paraphrases, negations, ambiguous and prompt-injection variants of your examples, and seeded rules add typos and noise. Every answer is parsed, **schema-validated and diffed field by field**. An AI judge is used only for free text, and its verdicts are labelled as such. Failures are grouped by cause, each with a suggested prompt fix. Pass rates come with **95% Wilson intervals**. Budgets, rate limits and fail-fast connection checks keep runs cheap and honest. It works with free Gemini or Groq keys or a local Ollama model, and the demo report needs no key at all.

`Java 21` `Javalin` `Anthropic Java SDK` `OpenAI-compatible APIs` `Ollama` `JUnit 5` `GitHub Actions`

</details>

<a href="https://github.com/ax1le28/fuzzer"><img src="https://img.shields.io/badge/view_project-%E2%86%97-B8733F?style=for-the-badge&labelColor=161B22" alt="View project"></a>

<br><br>

<img src="assets/h-04.svg" width="100%" alt="04 Path">

<img src="assets/timeline.svg" width="100%" alt="Timeline: 2024 PLC Development Intern at Holcim Azerbaijan; 2025 International STEM Olympiad gold; since 2025 BSc Computer Science at ELTE">

<br>

<img src="assets/h-05.svg" width="100%" alt="05 Recognition">

<p align="center">
  <img src="https://img.shields.io/badge/%F0%9F%A5%87%20GOLD-Coding%20%C2%B7%20Int%E2%80%99l%20STEM%20Olympiad%202025-F4C542?style=for-the-badge&labelColor=161B22" alt="Gold in Coding, International STEM Olympiad 2025"><br>
  <img src="https://img.shields.io/badge/%F0%9F%A5%87%20GOLD-Mathematics%20%C2%B7%20Int%E2%80%99l%20STEM%20Olympiad%202025-F4C542?style=for-the-badge&labelColor=161B22" alt="Gold in Mathematics, International STEM Olympiad 2025"><br>
  <img src="https://img.shields.io/badge/%F0%9F%A5%88%20SILVER-Mathematics%20%C2%B7%20SASMO-AAB8CA?style=for-the-badge&labelColor=161B22" alt="SASMO Silver in Mathematics">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/PCAP-Python%20Institute-8A6A50?style=flat-square&logo=python&logoColor=white&labelColor=161B22" alt="PCAP Python certification">
  <img src="https://img.shields.io/badge/Linux%20Essentials-certified-8A6A50?style=flat-square&logo=linux&logoColor=white&labelColor=161B22" alt="Linux Essentials">
  <img src="https://img.shields.io/badge/Cisco-certificate-8A6A50?style=flat-square&logo=cisco&logoColor=white&labelColor=161B22" alt="Cisco certificate">
</p>

<br>

<p align="center">
  <a href="https://www.linkedin.com/in/javidan-bandaliyev-7b3ba6278/"><img src="https://img.shields.io/badge/let%E2%80%99s_build_something-connect_on_LinkedIn-8A6A50?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=161B22" alt="Connect on LinkedIn"></a>
</p>

<img src="assets/footer.svg" width="100%" alt="">
