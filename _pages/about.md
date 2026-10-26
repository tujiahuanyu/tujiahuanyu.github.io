---
permalink: /
title: ""
excerpt: "Jiahuanyu Tu, master's student at Nankai University. Research interests: LLM agent memory, experience reuse, RAG, and self-evolving agents."
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class="anchor" id="about-me"></span>

I am **Jiahuanyu Tu (涂佳欢语)**, a first-year master's student in Computer Technology at **Nankai University**, where I also received my bachelor's degree in Information Security in June 2026.

My research focuses on **long-term memory, experience reuse, and execution control for LLM agents**. I am interested in how agents can retrieve useful past experiences, reuse successful behaviors, and adapt through continued interaction. My current interests include:

- **Agent Memory:** bridging the gap between user queries and stored memories to improve long-term recall.
- **Experience Reuse:** learning reusable action chains from interaction histories and deciding when to execute or stop them.
- **Retrieval-Augmented Generation:** organizing and retrieving evidence for grounded reasoning, including multi-hop questions.
- **Self-Evolving Agents:** exploring experience-driven adaptation and improvement over time.

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

<div class="paper-box">
  <div class="paper-box-image">
    <div class="method-figure method-figure-green" role="img" aria-label="JitRL extension overview: retrieve action chains from memory, check applicability, then continue the chain or return control to the action language model.">
      <span class="method-kicker">ACTION-CHAIN MEMORY</span>
      <div class="method-node">Interaction history</div>
      <div class="method-arrow" aria-hidden="true">↓</div>
      <div class="method-node">Retrieve chain · Check conditions</div>
      <div class="method-arrow" aria-hidden="true">↓</div>
      <div class="method-pair"><span>Continue chain</span><span>Return to action LLM</span></div>
      <span class="method-caption">Experience reuse with execution control</span>
    </div>
  </div>
  <div class="paper-box-text" markdown="1">

### Action-Chain Memory and Execution Control

**An extension of JitRL** · *Ongoing research, October 2026–present*

I study reusable action chains with applicability conditions, local goals, and environment rewards. My work covers condition matching, ordered continuation, switching thresholds, cooldown after failures, and fallback to the action LLM.

In a preliminary **Jericho Zork1** comparison using qwen3.7-flash, with **50 episodes per condition**, mean environment score increased from **15.62 to 35.20** against a local JitRL baseline with corrected discounted returns. Memory accumulated across episodes; broader task coverage and ablation studies remain future work.

  </div>
</div>

### Research Discussions

**TaskGraph-RAG — relation-aware retrieval for multi-hop question answering** · *October 2026*

I read and discussed a colleague-led study on entity–sentence–passage indexing, semantic role labeling, and entity-anchored multi-hop retrieval. My involvement was in exchanging research ideas and suggesting improvements to figure layout and manuscript organization. The manuscript was submitted to the October ARR cycle.

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
