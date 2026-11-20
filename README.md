# Kingdom Communication Solutions (KCS) Media Studio
**Course:** Transversal ISI Project (ING4187)  
**Institution:** Saint Jean Ingenieur, Eyang, Cameroon  
**Authors:**
* 1st Wriwiya Abba (`abba.wriwiya@saintjeaningenieur.org`)
* 2nd Robine Donfack (`donfack.robine@saintjeaningenieur.org`)
* 3rd Natacha Djiofack (`maurelle.djiofack@saintjeaningenieur.org`)
* 4th Thomas Nguisseu (`nguisseu.thomas@saintjeaningenieur.org`)
* 5th Abraham Noumsi (`simo.abraham@saintjeaningenieur.org`)
* 6th Manuel Yombo (`tagne.manuel@saintjeaningenieur.org`)
* 7th Thierry Tene (`tsafack.thierry@saintjeaningenieur.org`)

This repository contains the LaTeX source code for the academic engineering elaboration introducing the **Kingdom Communication Solutions (KCS) Media Studio**, a web-based platform for AI-assisted video transcription and multilingual caption editing for low-resource Cameroonian tonal languages (Gh\textopeno m\'al\'a', Ewondo, and Basaa).

## Document Structure & Chapter Roadmap
The elaboration follows the **Systems Development in Information Systems (SDIS)** research methodology by Nunamaker et al. (1990):

* **`chapter0.tex` — Chapter 0: Project Charter and Foundational Blueprint:** Foundational project scope, dialect selections, offline mobile field recording protocols via KoboToolbox, ethical double-validation, and 9-parameter audio metadata naming convention.
* **`chapter1.tex` — Chapter 1: Introduction and Research Formulation:** Societal motivation (MS1, MS2), preliminary exploratory diagnostic audit, problem statements (PS1, PS2), research questions (RQ1, RQ2), and Nunamaker research objectives (RO1.1.O to RO2.4.E).
* **`chapter2.tex` — Chapter 2: State of the Art (Observation Phase):** PRISMA-guided Systematic Literature Review (SLR) across 41 primary peer-reviewed studies and empirical software audits, answering 9 review questions ($\text{RQ}_{\text{Rev}}1$--$\text{RQ}_{\text{Rev}}9$) and extracting 10 practical system challenges ($C_1$--$C_{10}$).
* **`chapter3.tex` — Chapter 3: Cumulative Research Paper & System Design:** Cumulative IEEE conference paper synthesizing all preceding chapters (Motivation, Diagnostics, PRISMA State of the Art, 10 Challenges) and establishing the Theory Building System Design scaffolding.
* **`chapter3_report.tex` — Chapter 3: Standalone Report (Theory Building Phase):** Comprehensive chapter elaboration formatted in standard article layout with full UML diagrams, requirement matrices, and operational specifications.
* **`chapter4.tex` — Chapter 4: Implementation and Proof-of-Concept (Systems Development Phase):** *(Upcoming)* Browser Web Audio API waveform rendering, GACL UTF-8 font fallback engine, and containerized FastAPI/CTC inference service.
* **`chapter5.tex` — Chapter 5: Evaluation and Results (Evaluation Phase):** *(Upcoming)* Controlled quantitative ASR benchmarks (WER, CER), subtitling throughput speed trials ($<$3.5 min/min), and NASA-TLX/SUS usability metrics.
* **`chapter6.tex` — Chapter 6: Conclusion and Future Work:** *(Upcoming)* Project synthesis, threats to validity, and roadmap toward neural speech synthesis (TTS).

## Compilation Instructions
To compile the PDFs locally, ensure you have a standard TeX distribution (such as MiKTeX or TeX Live) with Biber installed.
Run the following commands in the terminal:
```bash
pdflatex chapter3.tex && biber chapter3 && pdflatex chapter3.tex
pdflatex chapter3_report.tex && biber chapter3_report && pdflatex chapter3_report.tex
```

## Overleaf
For collaborative editing, upload this directory as a zip file to Overleaf. The documents can be compiled individually (`chapter0.tex`, `chapter1.tex`, `chapter2.tex`, `chapter3.tex`, `chapter3_report.tex`).
