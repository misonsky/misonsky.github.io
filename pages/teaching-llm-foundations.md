---
layout: news
title: Foundations and Applications of Large Language Models
keywords: Yongkang Liu, teaching, large language models
description: Course page for Foundations and Applications of Large Language Models
permalink: /teaching/foundations-and-applications-of-large-language-models/
css:
  - pages/teaching.css
---

<div class="course-hero">
  <p class="teaching-eyebrow">Course Detail</p>
  <h2>Foundations and Applications of Large Language Models</h2>
  <p class="teaching-intro">
    This course examines the theoretical foundations, system design, and real-world uses of large language models.
    It emphasizes both principled understanding and research-driven practice, from pretraining and adaptation to evaluation, safety, and deployment.
  </p>
  <div class="course-actions">
    <a class="course-backlink" href="{{ '/teaching/' | relative_url }}">Back to Teaching</a>
  </div>
</div>

<div class="course-meta">
  <div class="course-meta__item">
    <span class="course-meta__label">Audience</span>
    <span class="course-meta__value">Senior undergraduates, master's students, and research trainees</span>
  </div>
  <div class="course-meta__item">
    <span class="course-meta__label">Format</span>
    <span class="course-meta__value">Lecture + paper reading + project discussion</span>
  </div>
  <div class="course-meta__item">
    <span class="course-meta__label">Goal</span>
    <span class="course-meta__value">Understand the lifecycle and research challenges of LLMs</span>
  </div>
</div>

<div class="course-outline">
  <h3>Lecture Schedule</h3>

  <div class="lecture-card">
    <div class="lecture-card__week">Lecture 1</div>
    <h4>Why Large Language Models Matter</h4>
    <p>The evolution from statistical NLP to pretrained language models, the emergence of scaling laws, and the current research landscape.</p>
    <p><strong>References:</strong> Brown et al. (2020); Kaplan et al. (2020).</p>
  </div>

  <div class="lecture-card">
    <div class="lecture-card__week">Lecture 2</div>
    <h4>Transformer Foundations</h4>
    <p>Self-attention, positional encoding, feed-forward blocks, training objectives, and why transformers became the dominant architecture.</p>
    <p><strong>References:</strong> Vaswani et al. (2017); The Illustrated Transformer.</p>
  </div>

  <div class="lecture-card">
    <div class="lecture-card__week">Lecture 3</div>
    <h4>Pretraining Objectives and Data Pipelines</h4>
    <p>Causal language modeling, masked language modeling, tokenization, web-scale corpora, and data quality considerations.</p>
    <p><strong>References:</strong> Devlin et al. (2019); Raffel et al. (2020); Penedo et al. (2023).</p>
  </div>

  <div class="lecture-card">
    <div class="lecture-card__week">Lecture 4</div>
    <h4>Scaling Laws and Emergent Ability</h4>
    <p>How model size, compute, and data interact; what emergence means; and the debate around capability forecasting.</p>
    <p><strong>References:</strong> Kaplan et al. (2020); Hoffmann et al. (2022); Wei et al. (2022).</p>
  </div>

  <div class="lecture-card">
    <div class="lecture-card__week">Lecture 5</div>
    <h4>Instruction Tuning and Alignment</h4>
    <p>Supervised instruction tuning, preference learning, RLHF, DPO, and the role of alignment data in model behavior.</p>
    <p><strong>References:</strong> Ouyang et al. (2022); Rafailov et al. (2023).</p>
  </div>

  <div class="lecture-card">
    <div class="lecture-card__week">Lecture 6</div>
    <h4>Parameter-Efficient Fine-Tuning</h4>
    <p>Adapters, prefix tuning, LoRA, QLoRA, and practical strategies for adapting LLMs under resource constraints.</p>
    <p><strong>References:</strong> Houlsby et al. (2019); Li and Liang (2021); Hu et al. (2022); Dettmers et al. (2023).</p>
  </div>

  <div class="lecture-card">
    <div class="lecture-card__week">Lecture 7</div>
    <h4>Prompting and In-Context Learning</h4>
    <p>Zero-shot and few-shot prompting, chain-of-thought reasoning, self-consistency, and prompt design patterns.</p>
    <p><strong>References:</strong> Brown et al. (2020); Wei et al. (2022); Wang et al. (2023).</p>
  </div>

  <div class="lecture-card">
    <div class="lecture-card__week">Lecture 8</div>
    <h4>Retrieval-Augmented Generation</h4>
    <p>Knowledge grounding, dense retrieval, indexing, retrieval orchestration, and hallucination reduction.</p>
    <p><strong>References:</strong> Lewis et al. (2020); Gao et al. (2024 survey).</p>
  </div>

  <div class="lecture-card">
    <div class="lecture-card__week">Lecture 9</div>
    <h4>Evaluation of LLMs</h4>
    <p>Automatic metrics, benchmark design, task contamination, human evaluation, and robustness considerations.</p>
    <p><strong>References:</strong> Liang et al. (2022); Chang et al. (2024 survey).</p>
  </div>

  <div class="lecture-card">
    <div class="lecture-card__week">Lecture 10</div>
    <h4>Reasoning and Tool Use</h4>
    <p>Program-aided reasoning, tool calling, agent workflows, planning, and the limits of purely autoregressive reasoning.</p>
    <p><strong>References:</strong> Schick et al. (2023); Yao et al. (2023); Qin et al. (2023).</p>
  </div>

  <div class="lecture-card">
    <div class="lecture-card__week">Lecture 11</div>
    <h4>Efficiency and Deployment</h4>
    <p>Quantization, KV-cache optimization, distillation, serving stacks, and latency-quality trade-offs.</p>
    <p><strong>References:</strong> Dettmers et al. (2022); Xiao et al. (2023); relevant systems papers.</p>
  </div>

  <div class="lecture-card">
    <div class="lecture-card__week">Lecture 12</div>
    <h4>Safety, Security, and Privacy</h4>
    <p>Jailbreaks, prompt injection, unsafe generation, privacy leakage, and defense strategies for safe deployment.</p>
    <p><strong>References:</strong> Ganguli et al. (2022); Zou et al. (2023); OWASP LLM guidance.</p>
  </div>

  <div class="lecture-card">
    <div class="lecture-card__week">Lecture 13</div>
    <h4>Multilingual and Domain-Specific LLMs</h4>
    <p>Cross-lingual transfer, data scarcity, vertical-domain modeling, and adaptation for specialized applications.</p>
    <p><strong>References:</strong> mT5; BLOOM; selected domain adaptation papers.</p>
  </div>

  <div class="lecture-card">
    <div class="lecture-card__week">Lecture 14</div>
    <h4>Multimodal Large Models</h4>
    <p>Vision-language alignment, multimodal instruction tuning, and interfaces that combine text with images and other modalities.</p>
    <p><strong>References:</strong> CLIP; Flamingo; LLaVA; GPT-4V report.</p>
  </div>

  <div class="lecture-card">
    <div class="lecture-card__week">Lecture 15</div>
    <h4>Research Paper Clinic</h4>
    <p>Students present recent papers, compare methods, critique evaluations, and identify promising research directions.</p>
    <p><strong>References:</strong> Selected ACL, EMNLP, ICLR, ICML, and NeurIPS papers.</p>
  </div>

  <div class="lecture-card">
    <div class="lecture-card__week">Lecture 16</div>
    <h4>Open Problems and Final Project Discussion</h4>
    <p>Reasoning reliability, data efficiency, controllability, interpretability, agentic systems, and future research opportunities.</p>
    <p><strong>References:</strong> Recent survey papers and frontier research articles.</p>
  </div>
</div>

<div class="teaching-section">
  <h3>Core References</h3>
  <ul class="teaching-list">
    <li>Vaswani et al. (2017). <em>Attention Is All You Need</em>.</li>
    <li>Brown et al. (2020). <em>Language Models are Few-Shot Learners</em>.</li>
    <li>Ouyang et al. (2022). <em>Training Language Models to Follow Instructions with Human Feedback</em>.</li>
    <li>Raffel et al. (2020). <em>Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer</em>.</li>
    <li>Recent surveys on RAG, evaluation, alignment, and efficient fine-tuning.</li>
  </ul>
</div>

<div class="teaching-section">
  <h3>Assignments and Assessment</h3>
  <ul class="teaching-list">
    <li><strong>Reading Reports:</strong> Short reports on representative LLM papers and surveys.</li>
    <li><strong>Paper Presentation:</strong> Each student or group presents one recent research paper and leads discussion.</li>
    <li><strong>Mini Project:</strong> A small empirical project on prompting, fine-tuning, retrieval augmentation, evaluation, or safety.</li>
    <li><strong>Final Assessment:</strong> Project report, presentation, or research proposal.</li>
  </ul>
</div>

<div class="teaching-section">
  <h3>Lecture Slides and Course Materials</h3>
  <ul class="teaching-list">
    <li>Week 1-4 lecture slides: <em>to be uploaded</em></li>
    <li>Week 5-8 lecture slides: <em>to be uploaded</em></li>
    <li>Week 9-12 lecture slides: <em>to be uploaded</em></li>
    <li>Week 13-16 lecture slides: <em>to be uploaded</em></li>
    <li>Paper list and project guidelines: <em>to be uploaded</em></li>
  </ul>
  <p>You can later replace these placeholders with direct PDF, PPT, notebook, or GitHub resource links.</p>
</div>
