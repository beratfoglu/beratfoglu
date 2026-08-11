<div align="center">

# Berat Fettahoglu

**Computer Engineering Student · AI/ML Engineer · Full-Stack Developer**

*Building real systems at the intersection of machine intelligence and human problems.*

[![Portfolio](https://img.shields.io/badge/Portfolio-beratfoglu.github.io-00ff9f?style=flat-square&logo=github&logoColor=black)](https://beratfoglu.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-beratfoglu-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/beratfoglu)
[![Email](https://img.shields.io/badge/Email-beratfettahoglu@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:beratfettahoglu@gmail.com)

</div>

---

I'm a final-year Computer Engineering student with a focus on applied AI — not the research kind, the kind that ships. My projects tend to start from a real frustration: a healthcare system that dismisses you, a digital world that profiles you without consent, research that shouldn't have to leave your machine to be trustworthy. I build tools that push back.

My stack lives in the space between ML engineering and full-stack development. I'm comfortable going from fuzzy inference systems and transformer fine-tuning all the way to Next.js frontends and Dockerized microservice deployments.

---

### 🚀 Highlighted Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🛡️ <a href="https://github.com/beratfoglu/NetRunner">NetRunner — Digital Privacy Arsenal</a></h3>
      <img src="https://img.shields.io/badge/status-active-brightgreen?style=flat-square"/>
      <img src="https://img.shields.io/badge/tools-12-8338ec?style=flat-square"/>
      <img src="https://img.shields.io/badge/AI%20models-2-ff006e?style=flat-square"/>
      <br/><br/>
      <p>A cyberpunk-themed, locally-hosted <strong>digital privacy toolkit</strong>. 12 tools, zero data stored server-side, zero trust assumed.</p>
      <ul>
        <li>🔏 PII anonymization — spaCy NER + Regex hybrid engine</li>
        <li>🎣 Phishing detection — Random Forest URL classifier + fine-tuned DistilBERT email model (97.6% acc)</li>
        <li>🔍 Browser fingerprint analyzer — Shannon entropy model with anti-fingerprint paradox detection</li>
        <li>🍪 Cookie & tracker analyzer — Playwright headless browser, 32+ tracker database</li>
        <li>👣 Digital footprint scanner — Holehe CLI, 121 platforms, weighted exposure scoring</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
        <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white"/>
        <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/>
        <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
        <img src="https://img.shields.io/badge/spaCy-09A3D5?style=flat-square&logo=spacy&logoColor=white"/>
        <img src="https://img.shields.io/badge/Playwright-45ba4b?style=flat-square&logo=playwright&logoColor=white"/>
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🩺 <a href="https://github.com/beratfoglu/biowire">Biowire — Personal Health Companion</a></h3>
      <img src="https://img.shields.io/badge/status-active-brightgreen?style=flat-square"/>
      <img src="https://img.shields.io/badge/modules-11-0891B2?style=flat-square"/>
      <img src="https://img.shields.io/badge/fuzzy%20engine-v2.1-db2777?style=flat-square"/>
      <br/><br/>
      <p>A full-stack health platform built around the idea that you shouldn't need a doctor's permission to understand your own body.</p>
      <ul>
        <li>🧠 5-layer Mamdani Fuzzy Engine — 21 clinical combination rules (STEMI, Stroke, PE, and more)</li>
        <li>🤖 Groq LLaMA 3.3 70B — context-aware clinical reasoning with gender-specific risk modifiers</li>
        <li>📊 Full health dashboard — vitals, medications, symptom log, mood tracking, medical records</li>
        <li>📚 Health Library — 32 conditions across 12 specialties, Wikipedia integration</li>
        <li>📰 Real-time feed — WHO, CDC, PubMed, NewsAPI aggregated in parallel</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white"/>
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
        <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white"/>
        <img src="https://img.shields.io/badge/scikit--fuzzy-F7931E?style=flat-square&logo=scikit-learn&logoColor=white"/>
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
        <img src="https://img.shields.io/badge/Groq-000000?style=flat-square&logoColor=white"/>
      </p>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="100%" valign="top">
      <h3>🌌 <a href="https://github.com/beratfoglu/NYX">NYX — Local Research Intelligence</a></h3>
      <img src="https://img.shields.io/badge/status-active-brightgreen?style=flat-square"/>
      <img src="https://img.shields.io/badge/model-Phi--4--mini%20%2B%20QLoRA-4fd1e8?style=flat-square"/>
      <img src="https://img.shields.io/badge/runs-100%25%20local-0d0d0d?style=flat-square"/>
      <br/><br/>
      <p><em>Ask deeper. Trust your sources.</em> A locally-run research assistant powered by a custom fine-tuned language model, grounded in your own documents via RAG, with real-time streaming, source citations, and knowledge graph extraction — nothing leaves your machine.</p>
      <ul>
        <li>🧠 Fine-tuned <strong>Phi-4-mini-instruct</strong> via QLoRA (Unsloth, 4-bit) on a balanced biomedical/science/math/conversation mix, served locally through a custom FastAPI streaming server</li>
        <li>📄 Document-grounded RAG — PyMuPDF extraction, ChromaDB vector store, relevance-threshold filtering, retrieval/prompt-assembly as an explicit two-node LangGraph pipeline, verified across multiple simultaneous documents</li>
        <li>🏷️ Every answer cites the exact source document(s) it drew from</li>
        <li>🕸️ Knowledge graph — scispaCy biomedical NER + co-occurrence extraction, rendered as an interactive d3-force graph, degrades gracefully if the NER model fails to load</li>
        <li>🔐 Supabase Auth with Row Level Security — per-user conversations, messages, and documents, nothing scoped only to browser memory</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white"/>
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
        <img src="https://img.shields.io/badge/Unsloth-4fd1e8?style=flat-square&logoColor=black"/>
        <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logoColor=white"/>
        <img src="https://img.shields.io/badge/ChromaDB-FF6F00?style=flat-square&logoColor=white"/>
        <img src="https://img.shields.io/badge/scispaCy-09A3D5?style=flat-square&logo=spacy&logoColor=white"/>
        <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white"/>
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
      </p>
    </td>
  </tr>
</table>

---

### 🛠 Skills & Tools

**AI / ML**
<p>
  <img height="40" src="https://skillicons.dev/icons?i=python" title="Python"/>
  <img height="40" src="https://skillicons.dev/icons?i=pytorch" title="PyTorch"/>
  <img height="40" src="https://skillicons.dev/icons?i=tensorflow" title="TensorFlow"/>
  <img height="40" src="https://skillicons.dev/icons?i=sklearn" title="scikit-learn"/>
  <img height="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pandas/pandas-original.svg" title="Pandas"/>
  <img height="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/numpy/numpy-original.svg" title="NumPy"/>
</p>

**Backend & Full-Stack**
<p>
  <img height="40" src="https://skillicons.dev/icons?i=fastapi" title="FastAPI"/>
  <img height="40" src="https://skillicons.dev/icons?i=flask" title="Flask"/>
  <img height="40" src="https://skillicons.dev/icons?i=nextjs" title="Next.js"/>
  <img height="40" src="https://skillicons.dev/icons?i=supabase" title="Supabase"/>
  <img height="40" src="https://skillicons.dev/icons?i=docker" title="Docker"/>
  <img height="40" src="https://skillicons.dev/icons?i=git" title="Git"/>
</p>

**Systems**
<p>
  <img height="40" src="https://skillicons.dev/icons?i=c" title="C"/>
  <img height="40" src="https://skillicons.dev/icons?i=cpp" title="C++"/>
  <img height="40" src="https://skillicons.dev/icons?i=cs" title="C#"/>
  <img height="40" src="https://skillicons.dev/icons?i=java" title="Java"/>
  <img height="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/microsoftsqlserver/microsoftsqlserver-plain.svg" title="SQL Server"/>
</p>

---

### 🔗 Connect

<p align="left">
  <a href="https://linkedin.com/in/beratfoglu" target="_blank"><img height="40" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" /></a>
  <a href="https://instagram.com/berat_foglu" target="_blank"><img height="40" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" /></a>
  <a href="https://github.com/beratfoglu" target="_blank"><img height="40" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/github.svg" /></a>
</p>
