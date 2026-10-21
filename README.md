<div align="center">

# Rui Jin

**Senior AI/ML Engineer** · LLM Evaluation & RLHF · Computer Vision · On-Device ML

I train and evaluate large language models, and I test evaluation methods in the open.<br>
Before that, 7 years of ML and full-stack software, including on-device body tracking at Nex.

Surigao del Norte, Philippines · **Open to AI/ML Software Engineer roles**

[![Portfolio][b-portfolio]][portfolio]
[![Resume][b-resume]][resume]
[![Medium][b-medium]][medium]
[![X][b-x]][x]
[![Email][b-email]](mailto:ruijin.developer@gmail.com)

</div>

<br>

## Right now

**AI Training & Evaluation Specialist** with [Outlier](https://outlier.ai) and [AfterQuery](https://www.afterquery.com) (since Mar 2025), platforms that AI companies use to train and evaluate their models.

- Write prompts built to expose where models fail, across classification, summarization, code generation, and multi-step reasoning.
- Grade and compare model answers against detailed rubrics for RLHF, with a justification for every rating.
- Flag hallucinations and factual errors, and rewrite weak answers into correct reference responses.
- Review generated code for correctness and readability.

On [my portfolio][portfolio] you can try a **live pose-tracking demo with a rep counter** that runs in your browser, or **chat with my AI assistant** about my work. It answers only from the site.

## By the numbers

| | |
| :--- | :--- |
| **7+** | years building ML and software |
| **20+** | full-stack and AI projects for clients, with a 5-star rating |
| **62%** | of RepCount-A test videos counted within one rep by my on-device rep counter (best published pose-based method: 56%) |
| **0.57** | correlation with human rubric grades from Qwen3.5 4B judging on a 4 GB GPU (GPT-4 as judge: 0.56) |

## Open projects

| Project | Result | Built with |
| :--- | :--- | :--- |
| **[On-Device Rep Counter][rep]**<br><sub>[Try it live][demo]</sub> | A small model trained from scratch reads MediaPipe body landmarks and counts exercise reps in the browser on INT8 weights. **62%** of RepCount-A test videos within one rep, vs. 56% for the best published pose-based method. 106 KB model, 0.35 ms per frame | PyTorch, MediaPipe, ONNX, INT8 quantization, TypeScript |
| **[Small LLM Judges vs. Human Rubric Grades][judge]** | Can a small open model on a 4 GB GPU grade answers like a person? On 320 human-scored BiGGen-Bench answers, Qwen3.5 4B (4-bit) reached **r = 0.57**, matching GPT-4 (0.56). A cross-validated calibration brought it within one point on 86% of answers | Python, llama.cpp, LLM-as-a-judge |
| **[EmbeddingGemma 2 Code Search Benchmark][gemma]** | Google's EmbeddingGemma 2 vs. the first EmbeddingGemma at 768, 512, 256, and 128 dimensions. At 256 dimensions it matched the original at 768 (**90.2 vs. 90.1** NDCG@10) with a third of the storage, and led by 4.7 points on CosQA | Python, PyTorch, sentence-transformers |

## Experience

### AI Training & Evaluation Specialist · [Outlier](https://outlier.ai) & [AfterQuery](https://www.afterquery.com)

*Mar 2025 – Present* · LLM evaluation, prompt engineering, RLHF, code review

### AI/ML Engineer · [Nex](https://www.nex.inc)

*Dec 2022 – Mar 2025*

Real-time body tracking behind Nex's motion-controlled games, where players control the game by moving in front of their phone's camera.

- Built and optimized lightweight computer vision models for real-time pose and gesture tracking on iOS and Android phones, targeting 30 fps with all inference running on-device.
- Worked on two of the hardest parts of the pipeline: encoding high-quality video on the phone and keeping the network connection stable.
- Wrote low-latency code for camera input, sensor fusion, and model inference, connected to the SDK that game designers and outside Unity developers used.
- Set up data pipelines and MLOps tooling to train, evaluate, and deploy models, plus debugging tools to check tracking accuracy across different lighting and room setups.

### Earlier roles

| Role | Company | Highlights |
| :--- | :--- | :--- |
| **Freelance Software Developer**<br><sub>Jun 2021 – Nov 2022</sub> | Upwork | 20+ full-stack and AI integration projects for SaaS, e-commerce, and analytics clients on AWS and Google Cloud, with a 5-star rating |
| **Full-Stack Developer**<br><sub>Sep 2019 – Nov 2022 · Part-time</sub> | Customized Limited | Platform features in Java, Python, and Node.js, plus the Python integration with the company's computer vision and ML models |
| **Software Engineer Intern**<br><sub>Jun 2018 – Aug 2019</sub> | Cloudbreakr | Influencer analytics features and ROI dashboards for brand clients, built with PHP, Laravel, and React |

### Client work under NDA

| Project | What it does | Built with |
| :--- | :--- | :--- |
| **Marine Object Detection** | Real-time detection of kelp, plastic bottles, surfers, whales, boats, and containers for a marine company, stable enough to run on phones and drones | Python, PyTorch, YOLO26, OpenCV, Drone SDK |
| **Instagram Avatar Protection** | Image recognition and watermarking that catch and prevent unauthorized reuse of users' Instagram profile photos | Python, TensorFlow, OpenCV, Instagram API |

## Writing

- **[Anthropic Asked Its Own Staff How Fast AI Is Moving. Their Answers Look Nothing Like the Public's.][w-anthropic]** · *Oct 2026*
- **[Google Is Paying Publishers for AI Content. Meta Rewrote Its Terms Instead.][w-google]** · *Oct 2026*
- **[Microsoft-Decision-1 Makes Decisions Almost Free. Someone Still Has to Check Them.][w-msft]** · *Oct 2026*
- **[EmbeddingGemma 2 at 256 Dimensions Matches the Original at 768][w-gemma]** · *Oct 2026*

More on [Medium][medium]. What I'm reading lately, from daily.dev:

<a href="https://daily.dev/ruijin"><img src="https://api.daily.dev/devcards/v2/8Vv3LBPKdik1Is1F8MAke.png?type=wide&r=7e5" width="652" alt="Rui Jin's Dev Card"/></a>

## Tech stack

| Area | Tools |
| :--- | :--- |
| **Languages** | ![Python][b-python] ![TypeScript][b-typescript] ![JavaScript][b-javascript] ![Java][b-java] ![C#][b-csharp] ![SQL][b-sql] |
| **ML & computer vision** | ![PyTorch][b-pytorch] ![TensorFlow][b-tensorflow] ![scikit-learn][b-sklearn] ![OpenCV][b-opencv] ![YOLO][b-yolo] ![ONNX][b-onnx] |
| **LLMs** | ![LLM evaluation][b-llmeval] ![RLHF][b-rlhf] ![Prompt engineering][b-prompt] |
| **Web** | ![React][b-react] ![Next.js][b-nextjs] ![Node.js][b-nodejs] ![Flask][b-flask] ![Tailwind CSS][b-tailwind] |
| **Cloud & DevOps** | ![AWS][b-aws] ![Google Cloud][b-gcp] ![Docker][b-docker] ![Kubernetes][b-kubernetes] ![Git][b-git] |

## Education

**Bachelor of Computer Science** · City University of Hong Kong\
*2016 – 2020 · Graduated with honors · Thesis on AI-driven web applications*

## Get in touch

I'm open to AI/ML Software Engineer roles. Email is the quickest way to reach me, or you can book a short call.

- **Email:** [ruijin.developer@gmail.com](mailto:ruijin.developer@gmail.com)
- **Book a call:** [cal.com/rui-jin/short-call](https://cal.com/rui-jin/short-call)
- **X:** [@invictusDev0][x] · **Medium:** [ruijin9981.medium.com][medium] · **FILLI.ME:** [filli.me/builders/ruijin](https://www.filli.me/builders/ruijin)

<p align="right"><img src="https://komarev.com/ghpvc/?username=devstar9981&label=Profile%20views&color=262626&style=flat-square" alt="Profile views"></p>

<!-- Links. If your portfolio address changes, update the first three lines. -->
[portfolio]: https://ruijin2026.vercel.app
[demo]: https://ruijin2026.vercel.app/#demo
[resume]: https://ruijin2026.vercel.app/Rui_Jin_Resume.pdf
[medium]: https://ruijin9981.medium.com
[x]: https://x.com/invictusDev0
[rep]: https://github.com/devstar9981/pose-rep-counter
[judge]: https://github.com/devstar9981/llm-judge-agreement
[gemma]: https://github.com/devstar9981/embeddinggemma2-benchmark
[w-anthropic]: https://medium.com/@ruijin.developer/anthropic-asked-its-own-staff-how-fast-ai-is-moving-their-answers-look-nothing-like-the-publics-d93d6e264c20
[w-google]: https://medium.com/@ruijin.developer/google-is-paying-publishers-for-ai-content-meta-rewrote-its-terms-instead-6dfe18f7578d
[w-msft]: https://medium.com/@ruijin.developer/microsoft-decision-1-makes-decisions-almost-free-someone-still-has-to-check-them-63bcc8a53e08
[w-gemma]: https://medium.com/@ruijin.developer/embeddinggemma-2-my-take-on-googles-new-multimodal-embedding-model-e2c14f848970

<!-- Badges. Simple Icons has no AWS or C# logo, so those are text only. -->
[b-portfolio]: https://img.shields.io/badge/Portfolio-262626?style=for-the-badge&logo=vercel&logoColor=white
[b-resume]: https://img.shields.io/badge/Resume-262626?style=for-the-badge&logo=googledocs&logoColor=white
[b-medium]: https://img.shields.io/badge/Medium-262626?style=for-the-badge&logo=medium&logoColor=white
[b-x]: https://img.shields.io/badge/X-262626?style=for-the-badge&logo=x&logoColor=white
[b-email]: https://img.shields.io/badge/Email-262626?style=for-the-badge&logo=gmail&logoColor=white
[b-python]: https://img.shields.io/badge/Python-262626?style=flat-square&logo=python&logoColor=white
[b-typescript]: https://img.shields.io/badge/TypeScript-262626?style=flat-square&logo=typescript&logoColor=white
[b-javascript]: https://img.shields.io/badge/JavaScript-262626?style=flat-square&logo=javascript&logoColor=white
[b-java]: https://img.shields.io/badge/Java-262626?style=flat-square&logo=openjdk&logoColor=white
[b-csharp]: https://img.shields.io/badge/C%23-262626?style=flat-square
[b-sql]: https://img.shields.io/badge/SQL-262626?style=flat-square
[b-pytorch]: https://img.shields.io/badge/PyTorch-262626?style=flat-square&logo=pytorch&logoColor=white
[b-tensorflow]: https://img.shields.io/badge/TensorFlow-262626?style=flat-square&logo=tensorflow&logoColor=white
[b-sklearn]: https://img.shields.io/badge/scikit--learn-262626?style=flat-square&logo=scikitlearn&logoColor=white
[b-opencv]: https://img.shields.io/badge/OpenCV-262626?style=flat-square&logo=opencv&logoColor=white
[b-yolo]: https://img.shields.io/badge/YOLO-262626?style=flat-square&logo=yolo&logoColor=white
[b-onnx]: https://img.shields.io/badge/ONNX-262626?style=flat-square&logo=onnx&logoColor=white
[b-llmeval]: https://img.shields.io/badge/LLM%20evaluation-262626?style=flat-square
[b-rlhf]: https://img.shields.io/badge/RLHF-262626?style=flat-square
[b-prompt]: https://img.shields.io/badge/Prompt%20engineering-262626?style=flat-square
[b-react]: https://img.shields.io/badge/React-262626?style=flat-square&logo=react&logoColor=white
[b-nextjs]: https://img.shields.io/badge/Next.js-262626?style=flat-square&logo=nextdotjs&logoColor=white
[b-nodejs]: https://img.shields.io/badge/Node.js-262626?style=flat-square&logo=nodedotjs&logoColor=white
[b-flask]: https://img.shields.io/badge/Flask-262626?style=flat-square&logo=flask&logoColor=white
[b-tailwind]: https://img.shields.io/badge/Tailwind%20CSS-262626?style=flat-square&logo=tailwindcss&logoColor=white
[b-aws]: https://img.shields.io/badge/AWS-262626?style=flat-square
[b-gcp]: https://img.shields.io/badge/Google%20Cloud-262626?style=flat-square&logo=googlecloud&logoColor=white
[b-docker]: https://img.shields.io/badge/Docker-262626?style=flat-square&logo=docker&logoColor=white
[b-kubernetes]: https://img.shields.io/badge/Kubernetes-262626?style=flat-square&logo=kubernetes&logoColor=white
[b-git]: https://img.shields.io/badge/Git-262626?style=flat-square&logo=git&logoColor=white
