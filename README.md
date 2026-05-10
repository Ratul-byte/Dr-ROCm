# 🏥 Dr. ROCm  
### AI-Powered Medical Vision Agent for Rapid Clinical Triage  
Built for **AMD Cloud Hackathon 2026**
## Team: Rurouni-X-RZ10

---

## 🚀 Overview

**Dr. ROCm** is a high-performance **Medical AI Agent** designed to perform rapid **first-pass triage** of medical imagery and clinical documentation using advanced **Vision-Language Models (VLMs)**.

The system is engineered to reduce bottlenecks in clinical workflows by assisting healthcare professionals with:

- ⚡ Fast emergency prioritization  
- 🩻 Medical image understanding  
- 📝 Prescription OCR  
- 📋 Structured triage reporting  
- 🤖 Agentic clinical reasoning  

Rather than replacing doctors, **Dr. ROCm acts as an intelligent triage assistant** — helping clinicians identify urgent cases faster and prepare structured handoffs for downstream medical review.

---

# ✨ Key Features

## 🧠 Multi-Modal Medical Intelligence

Dr. ROCm can analyze multiple types of medical inputs:

### 🩻 Radiology Analysis
- X-rays
- MRIs
- CT-like visual scans

Detects:
- Potential fractures
- Hyperintense lesions
- Abnormal tissue patterns
- Suspicious findings

---

### 📸 Clinical Photo Analysis
Supports medical photograph understanding including:
- Skin lesions
- Visible symptoms
- Dermatological abnormalities

Compatible with datasets such as:
- **HAM10000**

---

### 📝 Prescription OCR
Extracts text from:
- Handwritten prescriptions
- Printed prescriptions
- Clinical notes

Useful for:
- Medication extraction
- Digital record creation
- Structured downstream workflows

---

# ⚙️ Core Technology Stack

| Component | Technology |
|---|---|
| Vision Language Model | `Qwen/Qwen2-VL-7B-Instruct` |
| Inference Engine | `vLLM` |
| GPU Platform | `AMD Instinct™ GPUs` |
| AI Acceleration | `AMD ROCm™ 6.x` |
| Frontend | `Gradio` |
| Quantization | `4-bit`, `bfloat16` |
| Future Memory Layer | `ChromaDB` |

---

# 🔥 Why AMD ROCm?

Dr. ROCm is fully optimized for the **AMD Developer Cloud ecosystem**.

Using:
- **ROCm™ 6.x**
- **AMD Instinct™ GPUs**
- **vLLM acceleration**

the system achieves:
- Low-latency inference
- High-throughput image processing
- Efficient VRAM utilization
- Real-time triage capability

---

# ⚡ High-Performance Inference with vLLM

The project integrates **vLLM** to maximize inference performance.

## Benefits:
- 🚀 Faster response times
- 🧠 PagedAttention memory optimization
- 📉 Reduced GPU memory overhead
- 📷 Efficient high-resolution image processing
- 🔄 Dynamic model execution

This allows the system to operate effectively in:
- Emergency rooms
- Triage desks
- Clinical screening environments
- Research labs

---

# 🤖 Agentic Triage Logic

Dr. ROCm does more than simple image classification.

It acts as an **AI Clinical Agent** that generates a complete:

# 📋 Structured Triage Report

Including:

### ✅ Image Classification
Determines modality:
- X-ray
- MRI
- Clinical photograph
- Prescription

---

### 🚨 Conservative Triage Labeling
Categorizes urgency into:
- `Normal`
- `Monitor`
- `Urgent`
- `Emergency`

---

### 🔍 Clinical Findings
Generates:
- Potential abnormalities
- Risk indicators
- Structured observations

---

### ❓ Follow-Up Questions
Automatically drafts:
- Relevant physician questions
- Additional clinical context prompts
- Suggested next steps

---

# 🖥️ Dynamic Model Switching

The project includes a professional **Gradio dashboard** enabling:

- Live model switching
- Comparative benchmarking
- Research experimentation
- Hardware-performance testing

This allows researchers and clinicians to evaluate different VLMs dynamically.

---

# 🏥 Clinical Workflow

## 1️⃣ Upload
A clinician uploads:
- X-ray
- MRI
- Prescription
- Clinical image

---

## 2️⃣ AI Analysis
Dr. ROCm performs:
- Visual understanding
- Triage classification
- Risk estimation
- Structured extraction

---

## 3️⃣ Structured Handoff
The system generates:
- Markdown report
- JSON-ready clinical output

Compatible with:
- Hospital Information Systems (HIS)
- Downstream consultation agents
- Electronic medical workflows

---

## 4️⃣ Faster Critical Response
Urgent cases are flagged immediately, reducing:
- Time-to-doctor
- Clinical overload
- Triage delays

---

# 🧪 Quantization & Optimization

To maximize efficiency on AMD hardware:

- `4-bit Quantization`
- `bfloat16 Compute`

are utilized for:
- Lower VRAM usage
- Faster deployment
- Larger model support
- Improved scalability

---

# 🔮 Future Roadmap

## 🧠 Long-Term Clinical Memory
Planned integration with:
- **ChromaDB**
- Vector retrieval systems

for:
- Historical case referencing
- Medical literature grounding
- Context-aware triage

---

## 🌐 Open-Ended Agent Architecture
Future versions aim to support:
- Multi-agent medical workflows
- Autonomous consultation pipelines
- Retrieval-augmented clinical reasoning
- Hospital-scale deployment

---

# 📸 Example Use Cases

- Emergency room triage
- Rural healthcare assistance
- Radiology prioritization
- Prescription digitization
- Dermatology pre-screening
- Clinical workflow acceleration

---

# 🛠️ Installation

```bash
git clone https://github.com/yourusername/dr-rocm.git
cd dr-rocm
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
python app.py
```

---

# 📦 Model Used

```python
Qwen/Qwen2-VL-7B-Instruct
```

---

# 🖼️ Interface Preview

> Add screenshots or demo GIFs here.

Example:
- Dashboard UI
- Triage report output
- Prescription OCR results
- X-ray analysis

---

# 👨‍💻 Built For

🏆 **AMD Cloud Hackathon 2026**

Focused on:
- ROCm optimization
- AMD GPU acceleration
- Agentic AI systems
- Real-world healthcare impact

---

# ⚠️ Disclaimer

Dr. ROCm is intended for:
- Research
- Clinical assistance
- Educational purposes

It is **NOT** a replacement for licensed medical professionals or definitive diagnosis.

All outputs must be reviewed by qualified healthcare personnel.

---

# 📜 License

MIT License

---

# ❤️ Vision

Dr. ROCm demonstrates how hardware-optimized AI agents can assist—not replace—the clinical workforce by enabling:

- Faster triage
- Better prioritization
- Structured medical intelligence
- Scalable healthcare support systems

The future of healthcare AI is collaborative, efficient, and accessible.
