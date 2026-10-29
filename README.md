<div align="center">

  <!-- Dynamic Waving Capsule Header -->
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=1,11,21&height=220&section=header&text=Rodrigo%20Agreda&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Systems%20Engineer%20%7C%20Distributed%20Systems%20%26%20Applied%20AI&descFontSize=20&descAlignY=62&descAlign=50" width="100%" alt="Header Banner" />

  <!-- Animated Real-Time Typing Role Header -->
  <a href="https://github.com/RAgredaIpar">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=38BDF8&center=true&vCenter=true&random=false&width=650&lines=Distributed+Systems+%26+Backend+Engineer;Applied+AI+%26+Computer+Vision+Researcher;High-Throughput+%26+Zero-Allocation+Go+Architectures;Cloud+Infrastructure+%26+Serverless+Engineering" alt="Typing SVG" />
  </a>

  <p align="center">
    <a href="mailto:r.agredaipar@gmail.com"><img src="https://img.shields.io/badge/Email-r.agredaipar%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email Badge" /></a>
    <a href="https://github.com/RAgredaIpar"><img src="https://img.shields.io/badge/GitHub-RAgredaIpar-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Badge" /></a>
    <a href="https://linkedin.com/in/rodrigo-agreda"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge" /></a>
  </p>

  <img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="100%" alt="Separator" />

</div>

## 🛰️ Executive Summary

I am a **Systems Engineer** specializing in **high-performance backend architectures**, **distributed systems**, and **applied machine learning**. My engineering focus revolves around writing deterministic, low-latency, zero-allocation software, tackling complex concurrency constraints, and building clinical/scientific deep learning models that solve high-impact production problems.

* ⚡ **Distributed Systems:** Architected two-tier rate-limiting engines capable of **100M+ ops/sec** with sub-12ns latency, sharded concurrency, and atomic Redis Lua coordination.
* 🔬 **Computer Vision & Healthcare AI:** Engineered deep learning virtual staining pipelines (Pix2Pix, U-Net) for histopathological cell quantification (Ki-67 & Pan-CK+) deployed for hospital environments.
* 🧠 **Generative AI & LLMs:** Fine-tuned open-source language models (Qwen 2.5) via QLoRA for enterprise IT workflows, quantized to GGUF, and orchestrated with Ollama.
* ☁️ **Cloud & DevOps:** Production experience deploying resilient AWS serverless infrastructures via Terraform (IaC), Jenkins CI/CD automation, and Docker containerization.

---

## ⚡ Featured Engineering Architectures

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center"><a href="https://github.com/RAgredaIpar/distributed-rate-limiter">⚡ Distributed Rate Limiter</a></h3>
      <p align="center"><b>Production-Grade Two-Tier Rate Limiter in Go</b></p>
      <ul>
        <li><b>Latency:</b> ~10ns local checks via 64-shard FNV-1a in-memory cache with zero heap allocations.</li>
        <li><b>Coordination:</b> Atomic remote token leasing via embedded Redis Lua scripts preventing race conditions.</li>
        <li><b>Resilience:</b> 3-state Circuit Breaker (Closed, Open, Half-Open) with graceful fallback and Prometheus telemetry.</li>
      </ul>
      <p align="center">
        <code>Go</code> • <code>Redis Lua</code> • <code>gRPC</code> • <code>Prometheus</code> • <code>Concurrency</code>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center"><a href="https://github.com/RAgredaIpar/PanCK-VirtualStaining-CV">🔬 Virtual Staining & Ki-67 Digital Pathology</a></h3>
      <p align="center"><b>Deep Learning for Automated Histopathological Quantification</b></p>
      <ul>
        <li><b>Computer Vision:</b> Pix2Pix GANs and U-Net architectures for transforming H&E biopsy slides into IHC staining.</li>
        <li><b>Clinical Impact:</b> Automated proliferation scoring for Hospital de Alta Complejidad Virgen de la Puerta (EsSalud).</li>
        <li><b>Validation:</b> Benchmarked against SOTA datasets (DeepLIIF) with spectral decoupling algorithms.</li>
      </ul>
      <p align="center">
        <code>Python</code> • <code>PyTorch</code> • <code>U-Net / Pix2Pix</code> • <code>OpenCV</code> • <code>TypeScript</code>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center"><a href="https://github.com/RAgredaIpar/qwen-helpdesk-qlora">🧠 Autonomous HelpDesk LLM (QLoRA)</a></h3>
      <p align="center"><b>Supervised Fine-Tuning & Local GGUF Orchestration</b></p>
      <ul>
        <li><b>Model Optimization:</b> Fine-tuned Qwen2.5-1.5B-Instruct using 4-bit QLoRA with custom domain datasets.</li>
        <li><b>Local Inference:</b> Quantized weights to GGUF format for low-latency local execution via Ollama.</li>
        <li><b>API Layer:</b> Custom Python orchestration layer handling conversation state and Gradio verification UI.</li>
      </ul>
      <p align="center">
        <code>Python</code> • <code>Hugging Face</code> • <code>QLoRA</code> • <code>Ollama / GGUF</code> • <code>Gradio</code>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center"><a href="https://github.com/RAgredaIpar/aproil-backend">☁️ AWS Serverless Infrastructure</a></h3>
      <p align="center"><b>Enterprise Cloud Infrastructure & CI/CD Pipeline</b></p>
      <ul>
        <li><b>Architecture:</b> Event-driven AWS Lambda microservices backed by Amazon S3 and Amazon RDS (PostgreSQL).</li>
        <li><b>Infrastructure as Code:</b> Declarative cloud provisioning with Terraform for reproducible environments.</li>
        <li><b>DevOps:</b> Automated build, test, and deployment pipelines using Jenkins and Docker.</li>
      </ul>
      <p align="center">
        <code>AWS Lambda</code> • <code>Terraform</code> • <code>PostgreSQL</code> • <code>Jenkins</code> • <code>Docker</code>
      </p>
    </td>
  </tr>
</table>

---

## 🛠️ Technical Stack & Tooling

<div align="center">

  <!-- Interactive Skill Icons Grid -->
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=go,python,java,ts,cpp,c,postgres,redis,aws,terraform,docker,jenkins,pytorch,opencv,fastapi,spring,nextjs,linux,git,bash" alt="My Tech Stack" />
  </a>

</div>

<br/>

<details>
  <summary><b>🔍 Detailed Systems Breakdown (Click to expand)</b></summary>
  <br/>

| Category | Technologies & Tools |
| :--- | :--- |
| **Languages** | Go (Golang), Python, Java, TypeScript, C++, C, SQL, Bash |
| **Distributed Systems & Storage** | Redis (Lua Scripts), PostgreSQL, Amazon RDS, MongoDB, gRPC, Protocol Buffers |
| **AI, Computer Vision & LLMs** | PyTorch, U-Net, Pix2Pix GANs, OpenCV, Hugging Face, QLoRA, Ollama (GGUF), Gradio |
| **Cloud, DevOps & Observability** | AWS (Lambda, S3, RDS), Terraform (IaC), Docker, Jenkins CI/CD, Prometheus, Grafana |
| **Web & Frameworks** | FastAPI, Spring Boot / Spring Cloud, Next.js, Node.js, Tailwind CSS |

</details>

---

## 📊 Telemetry & Engineering Activity

<div align="center">

  <table border="0">
    <tr>
      <td align="center" width="50%">
        <img src="https://github-readme-stats.vercel.app/api?username=RAgredaIpar&theme=tokyonight&show_icons=true&hide_border=true&count_private=true&title_color=38bdf8&text_color=94a3b8&icon_color=38bdf8&bg_color=0f172a" width="100%" alt="GitHub Stats" />
      </td>
      <td align="center" width="50%">
        <img src="https://github-readme-streak-stats.herokuapp.com/?user=RAgredaIpar&theme=tokyonight&hide_border=true&stroke=38bdf8&ring=38bdf8&fire=38bdf8&currStreakLabel=38bdf8&background=0f172a" width="100%" alt="GitHub Streak" />
      </td>
    </tr>
  </table>

  <br/>

  <!-- Top Languages Compact Card -->
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=RAgredaIpar&theme=tokyonight&show_icons=true&hide_border=true&layout=compact&title_color=38bdf8&text_color=94a3b8&bg_color=0f172a" alt="Top Languages" />

</div>

---

## 🐍 Interactive Contribution Stream

<div align="center">
  <img src="https://raw.githubusercontent.com/RAgredaIpar/RAgredaIpar/output/github-contribution-grid-snake.svg" alt="Snake animation" />
</div>

---

<div align="center">
  <sub>Engineered with precision • Powered by Go, PyTorch & Distributed Systems • 2026</sub>
</div>
