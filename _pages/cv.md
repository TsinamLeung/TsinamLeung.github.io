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

- Cantonese and Yue linguistics
- Language contact and dialectal variation
- Romanization and transcription for Yue varieties
- Corpus linguistics and lexical resource development
- Language technology for under-resourced languages

---

## Publications

<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

---

## Talks

<ul>{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}</ul>

---

## Research & Project Experience

**TypeDuck — Cantonese IME with Multilingual Dictionary**  
*Developer* (Sept 2022 – Dec 2024)  
- Developed IME algorithm logic and dictionary-related tooling for a Cantonese input method.
- Designed and implemented dictionary interface components for multilingual lookup.
- Refined Cantonese lexical entries and filtered low-frequency items for practical input use.

**Chinese Newspaper Corpus System**  
*Developer* (Oct 2020)  
- Designed a crawler and extraction workflow for mainstream online Chinese newspapers across Asia.
- Processed scraped text into cleaner structured data for later corpus use.

**Cantonese Computational Linguistics Infrastructure Development Workgroup (CanCLID)**  
*Contributor* (2020 – Present)  
- Collected and cleaned online Guangzhou Cantonese text data.
- Worked on Cantonese/Mandarin classification using Cantonese and Mandarin corpus data.
- Supported Mozilla Common Voice Cantonese localization through UI translation, corpus curation, audio recording, and validation.
- Contributed to Cantonese IME algorithm and language-resource development.

**Lingnaam Jyutjam Association (嶺南粵音)**  
*Member* (2017 – Present) — [jyutjam.org](https://jyutjam.org)  
- Developed web infrastructure for the Pan-Cantonese Dictionary ([Jyutdict.org](https://jyutdict.org)).
- Collected and analyzed colloquial Cantonese lexical materials for comparative Yue research.
- Proposed and discussed tone-sandhi transcription solutions for Jyutping++.

---

## Computational Methods & Data Skills

- Corpus collection, scraping, cleaning, parsing, and metadata organization.
- Python-based text processing with pandas and regular-expression workflows.
- Lexical data preparation for dictionaries, input methods, and Cantonese language resources.
- Basic NLP workflows, including language-model-based classification for Cantonese/Mandarin data.
- Web and database tooling for language-resource projects, including PHP/MySQL-backed dictionary systems.
- Acoustic analysis with Praat.
- Git/GitHub workflows for collaborative research and open-source language technology projects.

---

## Languages

- **Native:** Cantonese, Dianbai Hokkien, Mandarin
- **Fluent:** Taiwan Hokkien, English
- **Basic conversation:** Japanese, Bahasa Melayu / Indonesian

---

## Service and Community Work

- Lingnaam Jyutjam Association, member and contributor to Cantonese phonetics, phonology, and romanization discussions.
- CanCLID, contributor to Cantonese computational linguistics infrastructure and open-source language technology work.
