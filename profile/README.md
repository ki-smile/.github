# SMAILE — Stockholm Medical Artificial Intelligence and Learning Environments

**Karolinska Institutet's core facility for digital health and artificial intelligence in healthcare**

SMAILE is Karolinska Institutet's dedicated core facility for medical AI, operating within the Department of Clinical Science, Intervention and Technology (CLINTEC). It is a hub for innovation, research, and education at the intersection of medical technology and artificial intelligence — bridging academic research, clinical practice, and industry innovation across the KI–Karolinska ecosystem.

This GitHub organization hosts the open-source research tools and platforms developed by the lab. A recurring theme across our work: **treating model disagreement and uncertainty as a clinical resource, not a defect to be averaged away.**

🌐 Lab website: [smile.ki.se](https://smile.ki.se) · [SMAILE at KI](https://ki.se/en/clintec/stockholm-medical-artificial-intelligence-and-learning-environments-smaile)

---

## Our vision

To be a pioneering university core facility that fosters innovation and supports cutting-edge research projects. By providing a multidisciplinary environment and integrating expertise in digital health and artificial intelligence, SMAILE aims to accelerate the development of transformative healthcare solutions, driving advancements in both academic research and clinical practice.

## Our mission

SMAILE supports the adoption of medical technology, digital health solutions, and artificial intelligence across the KI–Karolinska ecosystem through three objectives:

- **Supporting research and innovation** — technical expertise, infrastructure, and a collaborative environment for world-class medical AI research, from conception to publication.
- **Facilitating regulatory compliance** — expert guidance on the EU AI Act, medical device regulations (MDR/IVDR), and quality management systems, so innovations can move safely from research to clinical application.
- **Providing training in AI and digital health** — from introductory AI literacy to advanced technical workshops for clinicians, researchers, students, and industry practitioners.

---

## Public repositories

| Repository | What it is | Website / Docs |
|---|---|---|
| [medley](https://github.com/ki-smile/medley) | MEDLEY — multi-model medical diagnostic ensemble (31 LLMs from 6 countries) that surfaces bias and minority opinions for clinical oversight | [smile.ki.se](https://smile.ki.se) |
| [medley-bench](https://github.com/ki-smile/medley-bench) | Benchmark for behavioural metacognition in LLMs under social-epistemic pressure (130 instances, 5 domains) | [ki-smile.github.io/medley-bench](https://ki-smile.github.io/medley-bench/) |
| [triage-medley](https://github.com/ki-smile/triage-medley) | Human-in-the-loop ED triage decision support using multi-model disagreement as a safety signal | [triage.medleyai.org](https://triage.medleyai.org) |
| [trustcv](https://github.com/ki-smile/trustcv) | Framework-agnostic trustworthy cross-validation toolkit with leakage/balance checks and regulatory reporting (29 CV methods) | [ki-smile.github.io/trustcv](https://ki-smile.github.io/trustcv/) · [PyPI](https://pypi.org/project/trustcv/) |
| [aegis](https://github.com/ki-smile/aegis) | Operational infrastructure for post-market governance of adaptive medical AI under US & EU regulations | [ki-smile.github.io/aegis](https://ki-smile.github.io/aegis) |
| [healthprocessai](https://github.com/ki-smile/healthprocessai) | Dual-language (Python & R) process-mining framework for healthcare, with multi-model LLM insight synthesis | [ki-smile.github.io/healthprocessai](https://ki-smile.github.io/healthprocessai/website/) |
| [smile_manual](https://github.com/ki-smile/smile_manual) | User manual for connecting to and deploying on the SMAILE Kubernetes cluster at KI | — |

---

## Themes across our work

- **Disagreement as signal.** MEDLEY, Triage-Medley, and MEDLEY-Bench all preserve and analyse divergence between models rather than collapsing it into consensus.
- **Trustworthy & regulated AI.** TrustCV and AEGIS focus on validation rigor, data-leakage detection, and regulatory-aligned governance (EU AI Act, MDR/IVDR, FDA).
- **Healthcare analytics & process mining.** HealthProcessAI brings clinical pathway optimization and AI-powered insight synthesis to healthcare data.
- **Reproducible research infrastructure.** smile_manual documents our DGX Kubernetes environment for medical AI research workflows.

## Services

Beyond open-source tools, SMAILE offers collaborative, educational support across the AI healthcare lifecycle. The following services are available through the [TEF-Health](https://tef-health.kg.ebrains.eu/?category=Service&q=smaile) network — Europe's testing and experimentation facilities for digital health — with subsidized rates for startups and SMEs:

- **AI Imaging Lab** — development & validation of segmentation, detection, and classification models across imaging modalities.
- **AI Readiness Review** — evaluating your pipeline and technical documentation for MDR / AI Act readiness.
- **MDR Navigation Desk** — regulatory guidance for AI and medical devices.
- **Bias Checkpoint** — fairness & equity analysis of AI systems using demographic breakdowns and explainable AI (XAI) tools.
- **Tech Validation Hub** — assessment of custom biomedical devices and hardware.
- **Fit-for-Purpose Tech Check** — evaluating wearables and digital health systems end-to-end, from sensor design to data analysis.
- **BioSignal Suite** — design and validation of biomedical signal-processing pipelines (ECG and other biosignals).

See the [SMAILE Services page](https://ki.se/en/clintec/stockholm-medical-artificial-intelligence-and-learning-environments-smaile/services) and the [TEF-Health service catalogue](https://tef-health.kg.ebrains.eu/?category=Service&q=smaile) for details.

## Contributing

We welcome code, clinical use-case examples, documentation improvements, and bug reports. See the `CONTRIBUTING.md` in each repository.

## About

**SMAILE Lab**, Karolinska Institutet — Department of Clinical Science, Intervention and Technology (CLINTEC)
🌐 [smile.ki.se](https://smile.ki.se) · [SMAILE at KI](https://ki.se/en/clintec/stockholm-medical-artificial-intelligence-and-learning-environments-smaile)

> ⚠️ Our medical AI tools are for research and educational purposes. They are not validated clinical devices and should not be used for diagnosis or treatment decisions without appropriate validation and regulatory review.
