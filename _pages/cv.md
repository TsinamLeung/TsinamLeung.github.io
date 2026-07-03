---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download my academic CV (DOCX)]({{ base_path }}/files/Zinan_Liang_Academic_CV.docx)

---

## Education

**National University of Singapore** — Singapore  
*MA by Research in Linguistics* (2025 – Present)

**Chengyi College, Jimei University** — Xiamen, Fujian, China  
*Bachelor of Engineering in Network Engineering* (2017 – 2021)

---

## Research Interests

- Sinitic linguistics on Yue (Cantonese), focusing on language contact
- Typological variation in Sinitic varieties
- Digital linguistic infrastructure for Yue varieties, including corpora and romanization
- Corpus linguistics and lexical-resource development
- Language technology for under-resourced languages

---

## Publications & Presentations

<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

<ul>{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}</ul>

---

## Research & Employment Experience

**TypeDuck — Cantonese IME with Multilingual Dictionary**  
*Developer / Research Assistant; PI: Dr. Chaak Ming Lau, EduHK* (Sept 2022 – Dec 2024)

- Developed a Cantonese Input Method Engine (IME) to assist Cantonese learners from diverse ethnic backgrounds, planned for introduction in Hong Kong primary and middle schools.
- Built and deployed the IME algorithm server.
- Designed and implemented the dictionary user interface.
- Refined the Cantonese lexicon of the IME dictionary by filtering and removing obsolete or rare terminology.

**Chinese Newspaper Corpus System**  
*Developer; PI: Prof. Sze Wing Tang, CUHK* (Oct 2020)

- Conceived and developed a robust scraping and data-extraction system for mainstream online Chinese newspapers across Asian countries.

---

## Academic & Open-Source Contributions

**Cantonese Computational Linguistics Infrastructure Development Workgroup (CanCLID)**  
*Core Contributor* (2020 – Present)

- Collected and curated a high-quality corpus of online text in Guangzhou Cantonese.
- Trained a Cantonese language model based on Guangzhou and Hong Kong text corpora, subsequently building a Cantonese/Mandarin classifier.
- Led the localization of Mozilla Common Voice into Cantonese, including UI translation, corpus collection/refinement, and audio recording verification.
- Optimized the Cantonese IME algorithm to enhance overall functionality and prediction accuracy.

**Lingnaam Jyutjam (嶺南粵音)**
*Core Contributor* (2017 – Present) — [jyutjam.org](https://jyutjam.org)

- Developed the web application for the Pan-Cantonese Dictionary ([Jyutdict.org](https://jyutdict.org)), which archives pronunciation records of Yue varieties across Guangdong and Guangxi.
- Engaged in academic discussions concerning Yue classification and the reconstruction of Early-Qing Cantonese phonology.
- Conducted extensive collection and analysis of colloquial Cantonese terms, contributing to the construction of proto-Yue phonetics.
- Parsed and filtered Guangzhou Cantonese transcripts using Python for a comprehensive colloquial dictionary.
- Introduced and implemented a Cantonese tone-sandhi transcribing solution for Jyutping++.

---

## Computational Methods & Data Skills

- **Data & NLP workflows:** Corpus collection, web scraping, data cleaning, parsing, metadata organization, and language-model-based classification for Cantonese/Mandarin data.
- **Programming & tools:** C++, Python, pandas, regular expressions, PHP/MySQL, and Git/GitHub.
- **Linguistics tools:** Praat for acoustic analysis and lexical data preparation for dictionaries and input methods.

---

## Languages

- **Native:** Cantonese, Dianbai Min
- **Fluent:** Mandarin
- **Conversational:** Taiwan Hokkien
- **Professional:** English
- **Basic:** Japanese, Bahasa Melayu / Indonesian

---

## Service and Community Work

- Lingnaam Jyutjam, core contributor to Yue classification, Early-Qing Cantonese phonology, romanization, and Pan-Cantonese Dictionary work.
- CanCLID, core contributor to corpus, classifier, Common Voice localization, IME, and open-source language technology work.
