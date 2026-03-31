# Mental Health Disorder Detection Beyond Social Media: Datasets

A collection of non-social media, free-text datasets for mental health disorder detection, compiled as part of the first systematic review of such resources.

## 📚 Data Availability

The labels for data availability are explained below:

* **PUB** - The dataset is publicly available and hosted online for anyone to access.
* **DUA** - The data is available only after a Data Use Agreement is signed. Sometimes, authorization from an Institutional Review Board (IRB) may be needed.
* **RSTR** - The dataset is restricted; access requires formal approval from the data owner or institution.
* **UNK** - The dataset availability is unknown; the authors do not mention if the data is available to the research community.

## 📖 Citation

If you found our list of datasets useful, please cite our paper:

[Mental Health Disorder Detection Beyond Social Media: A Systematic Review of Available Datasets](https://github.com/SadiyaPuspo/MHD-Beyond-Social-Media-Datasets-Review)

```bibtex
@inproceedings{puspo2026mental,
    title = "Mental Health Disorder Detection Beyond Social Media: A Systematic Review of Available Datasets",
    author = "Puspo, Sadiya Sayara Chowdhury and Bucur, Ana-Maria and Chancellor, Stevie and Uzuner, Ozlem and Zampieri, Marcos",
    booktitle = "Proceedings of LREC 2026",
    year = "2026",
}
```

---

**Disorder abbreviations:**
SD - Suicidal, DP - Depression, MinDP - Minor Depression, PD - Postnatal Depression, PTSD - Post Traumatic Stress Disorder, OCD - Obsessive Compulsive Disorder, SMI - Severe Mental Illness, MDD - Major Depressive Disorder, MHD - Mental Health Distress, AjD - Adjustment Disorder, BD - Bipolar Disorder, SZ - Schizophrenia, AX - Anxiety, SDI - Suicidal Ideation, FEP - First Episode Psychosis, DEM - Dementia, PA - Panic Attack

**Platform abbreviations:**
CLINIC - Clinical setting (hospitals, clinics), FORUM - Online health/support forums, MIXED - Multiple sources, COLLEGE - University/college setting

**Data type abbreviations:**
EHR - Electronic Health Record, EMR - Electronic Medical Record, DS - Discharge Summary, SD Notes - Suicide/Death Notes

---

## 🗂️ Datasets

| Dataset | Language | Disorder(s) | Platform | Data Type | Annotation Procedure | Annotation Instrument | Labels | Size | Availability |
|---|---|---|---|---|---|---|---|---|---|
| [Pestian et al. (2012)](https://journals.sagepub.com/doi/10.1177/1178222612474502) | EN | SD | CLINIC | SD Notes | Manual | Krippendorff's α | 15 | 1,004 | DUA |
| [Uzuner et al. (2017)](https://www.sciencedirect.com/science/article/pii/S1532046417301302) | EN | DP, PTSD, OCD, BD | CLINIC | Clinical Notes | Manual | — | 4 | 816 | DUA |
| [Jackson et al. (2017)](https://bmjopen.bmj.com/content/7/1/e012012) | EN | SMI | CLINIC | EHR (DS) | Manual | Text Hunter | 50 | 37,211 | RSTR |
| [Low et al. (2010)](https://ieeexplore.ieee.org/document/5575201) | EN | MDD | CLINIC | Interview | Manual | LIFE | 2 | 139 | RSTR |
| [Pestian et al. (2010)](https://journals.sagepub.com/doi/10.1177/117822261000300008) | EN | SD | CLINIC | SD Notes | Manual | Ontology | 2 | 66 | RSTR |
| [Geraci et al. (2017)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5626933/) | EN | MDD & DD | CLINIC | EMR | Manual | DSM-IV | 2 | 861 | RSTR |
| [Zhou et al. (2015)](https://pubmed.ncbi.nlm.nih.gov/26262009/) | EN | DP | CLINIC | EHR (DS) | Manual | — | 3 | 1,200 | UNK |
| [Meng et al. (2021)](https://ieeexplore.ieee.org/document/9119391) | EN | DP | CLINIC | EHR | Manual | ICD-9 & AD | 2 | 10,148 | UNK |
| [Marrie et al. (2018)](https://www.researchprotocols.org/2018/1/e8794/) | EN | DP & AX | CLINIC | Interview | Manual | DSM-IV | — | 308 | UNK |
| [Diederich et al. (2007)](https://www.sciencedirect.com/science/article/abs/pii/S1568494606000743) | EN | SZ | CLINIC | Essay | Manual | — | 2 | 56 | UNK |
| [Poulin et al. (2014)](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0085733) | EN | SD | CLINIC | Clinical Notes | Manual | — | 3 | 210 | UNK |
| [Saini et al. (2014)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4111987/) | EN | SZ, DP, BD, SD & Other | CLINIC | Interview & Clinical Notes | Manual | — | 2 | 198 | UNK |
| [Milne et al. (2016)](https://aclanthology.org/W16-0312/) | EN | MHD | FORUM | Post | Manual | Fleiss's Kappa & Cohen's Kappa | 4 | 1,227 | PUB |
| [He et al. (2017)](https://journals.sagepub.com/doi/10.1177/1073191115569578) | EN | PTSD | FORUM | Essay | Manual | DSM-IV & CAP Scale | 2 | 300 | UNK |
| [Tyshchenko (2018)](https://www.semanticscholar.org/paper/Depression-and-Anxiety-Detection-from-Blog-Posts-Tyshchenko/3e6fddcd9e63a2dc0dab67f5ae2e14a31b8d4b7b) | EN | DP & AX | FORUM | Post | Self-disclosure | — | 2 | 16,975 | UNK |
| [Nguyen et al. (2014)](https://ieeexplore.ieee.org/document/6919289) | EN | DP, BD & SD | FORUM | Post | Self-disclosure | — | 2 | 267,964 | UNK |
| [Aich et al. (2022)](https://aclanthology.org/2022.findings-emnlp.317/) | EN | SZ & BD | COLLEGE | Interview | Manual | DSM-V & DSM-IV | 3 | 644 | DUA |
| [Rude et al. (2004)](https://www.tandfonline.com/doi/abs/10.1080/02699930441000030) | EN | DP | COLLEGE | Essay | Manual | BDI & IDD-L | 3 | 124 | UNK |
| [Rheault (2016)](https://aclanthology.org/W16-5603/) | EN | AX | DEBATE | Political Speech | Manual | — | 2 | 4,000 | PUB |
| [Hull et al. (2020)](https://bmcpsychiatry.biomedcentral.com/articles/10.1186/s12888-020-02721-x) | EN | DP & AX | Telemedicine Platform | Message | Manual | PHQ-9, GAD-7 | 10 | 718 | DUA |
| [Krishnamurti et al. (2022)](https://www.sciencedirect.com/science/article/pii/S1877050922005877) | EN | PD | APP | Essay | Manual | EPDS | 2 | 1,091 | UNK |
| [Nobles et al. (2018)](https://dl.acm.org/doi/10.1145/3173574.3173987) | EN | DP & SD | Phone | SMS | Manual | Self-Disclosure | 2 | 94 | UNK |
| [Howes et al. (2014)](https://aclanthology.org/W14-3212/) | EN | DP & AX | Online Therapy | Chat Dialogue | Mixed | MALLET & LIWC | 2 | 882 | UNK |
| [Ringeval et al. (2019)](https://dl.acm.org/doi/10.1145/3347320.3357384) | EN | DP & PTSD | Virtual Agent | Interview | Manual | PHQ-8 | 5 | 275 | DUA |
| [Schoene and Dethlefs (2016)](https://aclanthology.org/W16-0308/) | EN | DP & SD | MIXED | SD Notes & Articles | Manual | — | 12 | 426 | UNK |
| [Gratch et al. (2014)](https://aclanthology.org/L14-1421/) | EN | DP, AX & PTSD | MIXED | Interview | Manual | — | — | 621 | DUA |
| [Ghosh et al. (2020)](https://aclanthology.org/2020.lrec-1.181/) | EN | DP & SDI | MIXED | SD Notes & Book | Manual | Cohen's Kappa | 15 | 2,393 | PUB |
| [Tasnim et al. (2022)](https://aclanthology.org/2022.clpsych-1.14/) | EN | DP & AX | mTurk | Interview | Manual | PHQ-9, GAD-7 | 2 | 674 | UNK |
| [Caicedo et al. (2020)](https://www.sciencedirect.com/science/article/pii/S2405844020316467) | EN-ES | DP & SDI | Social Network & Forum | Post | Manual | Cohen's Kappa | 4 | 102 | PUB |
| [Wu et al. (2020)](https://www.sciencedirect.com/science/article/abs/pii/S0165032719322748) | EN-ZH | MDD, MinDP, SZ, BD, AjD, DEM & Other | CLINIC | EHR (DS) | Manual | DSM-IV, Sheehan Disability Scale | 9 | 4,836 | RSTR |
| [Zou et al. (2023)](https://ieeexplore.ieee.org/document/9926166) | ZH | MDD | CLINIC | Interview | Manual | HAMD & PHQ-9 | 2 | 78 | PUB |
| [Jiang et al. (2022)](https://ieeexplore.ieee.org/document/9956679) | ZH | DP & AX | CLINIC | Interview | Manual | HAMD & HAMA | 3 | 1,025 | PUB |
| [Xu et al. (2025)](https://www.medrxiv.org/content/10.1101/2025.01.14.25320534v1) | ZH | DP & AX | CLINIC | EMR | Manual | DSM-V & ICD-10 | 4 | 1,160 | PUB |
| [Mao et al. (2023)](https://ieeexplore.ieee.org/document/10108946) | ZH | DP | CLINIC | Interview | Manual | MADRS | 2 | 113 | DUA |
| [Ive et al. (2024)](https://arxiv.org/abs/2501.00129) | ZH | AX | CLINIC | EHR | Manual | ICD-9 & ICD-10 | 2 | 84,426 | RSTR |
| [Li et al. (2023)](https://medinform.jmir.org/2023/1/e50221) | ZH | DP & SD | CLINIC | Interview | Manual | HAMD | 3 | 305 | UNK |
| [Shen et al. (2022)](https://ieeexplore.ieee.org/document/9747054) | ZH | DP | APP | Interview | Manual | SDS | 2 | 162 | PUB |
| [Mo et al. (2024)](https://ieeexplore.ieee.org/document/10373161) | ZH | AX | Phone Recording | Essay | Manual | GAD-7 | 3 | 227 | UNK |
| [Shin et al. (2022)](https://www.frontiersin.org/journals/psychiatry/articles/10.3389/fpsyt.2022.801301/full) | KO | DP, AX & SD | CLINIC | Interview | Manual | PHQ-9, HDRS, BAI & BSS | 2 | 166 | DUA |
| [Figueroa-Barra et al. (2022)](https://www.nature.com/articles/s41537-022-00261-x) | KO | SZ & FEP | CLINIC | Interview | Manual | DSM-V, PANSS | 3 | 133 | RSTR |
| [Wawer et al. (2022)](https://link.springer.com/article/10.1007/s12559-021-09952-y) | PL | SZ | CLINIC | Interview | Manual | ICD-10 | 2 | 94 | UNK |
| [Oh et al. (2024)](https://www.frontiersin.org/journals/psychiatry/articles/10.3389/fpsyt.2023.1256571/full) | ES-CL | DP | CLINIC | Interview | Manual | DSM-V | 8 | 451 | UNK |
| [Hämäläinen et al.](https://aclanthology.org/2021.wnut-1.3/) | TH | DP | FORUM | Post | Manual | Keyword Search | 2 | 944 | PUB |
| [Hiraga (2017)](https://aclanthology.org/P17-3018/) | JA | DP | FORUM | Post | Self-disclosure | — | 2 | 108 | UNK |
| [Alghamdi et al. (2020)](https://ieeexplore.ieee.org/abstract/document/9040556) | AR | DP | FORUM | Post | Self-disclosure & Manual | DSM-5, PHQ-9, QIDS-SR | 2 | 20,000 | UNK |
| [Mulholland and Quinn](https://aclanthology.org/I13-1070/) | EN | SD | Online DB | Song Lyrics | Manual | — | 2 | 810 | UNK |
| [Zervopoulos et al. (2019)](https://link.springer.com/chapter/10.1007/978-3-030-19823-7_47) | EL | SDI | — | Poem | Manual | — | 2 | 90 | UNK |
| [Reynolds and Wilson (2013)](https://journals.sagepub.com/doi/10.1177/0141076813507839) | CF | DP, AX & PA | Tablets | — | — | — | — | — | UNK |

---

For datasets from social media platforms, please refer to [bucuram/depression-datasets-nlp](https://github.com/bucuram/depression-datasets-nlp).
