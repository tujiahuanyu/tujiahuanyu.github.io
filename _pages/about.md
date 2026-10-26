---
permalink: /
title: ""
excerpt: "Jiahuanyu Tu, master's student at Nankai University. Research interests: Agent Memory, Self-Evolution, Recursive Self-Improvement (RSI), and Retrieval-Augmented Generation (RAG)."
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class="anchor" id="about-me"></span>

I am **Jiahuanyu Tu (涂佳欢语)**, a first-year master's student in Computer Technology at **Nankai University**, where I also received my bachelor's degree in Information Security in June 2026.

My research interests include:

- **Agent Memory**
- **Self-Evolution**
- **Recursive Self-Improvement (RSI)**
- **Retrieval-Augmented Generation (RAG)**

Feel free to contact me at [tujiahuanyu [at] mail.nankai.edu.cn](mailto:tujiahuanyu@mail.nankai.edu.cn).

<h1 id="research">📝 Research</h1>

<div class="paper-box">
  <div class="paper-box-image">
    <div class="method-figure" role="img" aria-label="GBR overview: supplement the original query with a memory-style retrieval signal, then fuse retrieved memories while preserving order and removing duplicates.">
      <span class="method-kicker">GUESS BEFORE RETRIEVAL</span>
      <div class="method-node">User query</div>
      <div class="method-arrow" aria-hidden="true">↓</div>
      <div class="method-pair"><span>Original query</span><span>Memory-style signal</span></div>
      <div class="method-arrow" aria-hidden="true">↓</div>
      <div class="method-node">Retrieve · Fuse · Deduplicate</div>
      <span class="method-caption">Query augmentation for agent memory</span>
    </div>
  </div>
  <div class="paper-box-text" markdown="1">

### Guess before Retrieval (GBR)

**Agent long-term memory retrieval** · *Under review at SCIS*

I designed and implemented a model-agnostic method that supplements the original query with a memory-style retrieval signal. It reuses existing encoders and memory indexes, and combines auxiliary retrieval with order-preserving deduplication and sub-query gating where appropriate.

I integrated GBR with **A-MEM, SimpleMem, and LightMem** on LoCoMo, with further LightMem evaluation on LongMemEval-S. Reported average F1 improvements on LoCoMo are **3.37–7.00 percentage points** for A-MEM and **1.20–2.64 points** for SimpleMem.

  </div>
</div>

<h1 id="projects">💻 Projects</h1>

### RheaChoice — Skin Health Consultation Agent

*July 2024* · **Frontend interaction, multi-session management, and integration** · [GitHub](https://github.com/ya-yaa/RheaChoice)

RheaChoice is an interactive skin health consultation demo built with GLM-4, LangChain, FastAPI/LangServe, and MySQL/Text-to-SQL. My contribution focused on:

- Adapting the HTML/CSS/JavaScript frontend to connect the product introduction, chat interface, and conversation history.
- Implementing session creation and switching, mapping conversation entries to backend `session_id` values, and restoring message displays.
- Integrating streaming responses and testing the frontend with the model, database, and agent backend.

<h1 id="education">📖 Education</h1>

- **September 2026–present** · **Nankai University**<br>
  Master's student in Computer Technology.
- **September 2022–June 2026** · **Nankai University**<br>
  Bachelor's degree in Information Security.

<h1 id="honors">🎖 Honors and Awards</h1>

- **Outstanding Graduate**, Nankai University.
- **Gongneng Scholarship, First Prize**, Nankai University — awarded twice.
- **Merit Student**, Nankai University — awarded twice.
- **Culture and Sports Scholarship, First Prize**, Nankai University.
- **Second Prize, Tianjin Division**, Contemporary Undergraduate Mathematical Contest in Modeling, 2024.
- **Outstanding Paper**, Shenzhen Cup Mathematical Modeling Challenge, 2024.
- **Second Prize, Natural Sciences Academic Paper Category**, 7th Nankai University President's Cup Innovation and Entrepreneurship Competition, 2025.
- **Third Prize, Outstanding Undergraduate Research Project**, Nankai University, 2025.
- **Champion, Women's Singles, Regular University Division**, Tianjin University Tennis Championships.
- **Fifth Place, Women's Singles, Regular University Division**, National University Tennis Championships Finals.

<h1 id="skills">🛠 Skills</h1>

- **Agent / LLM:** long-term memory, experience reuse, RAG, vector retrieval, LangChain, agent harnesses, and execution control.
- **Programming / Engineering:** Python, C++, FastAPI, MySQL, Git, Linux, HTML, CSS, and JavaScript.
- **Languages:** Chinese; English academic reading and writing (CET-4: 564; CET-6: 517).

<p class="homepage-note">Last updated: October 2026 · Built with <a href="https://github.com/RayeRen/acad-homepage.github.io">AcadHomepage</a> and GitHub Pages.</p>
