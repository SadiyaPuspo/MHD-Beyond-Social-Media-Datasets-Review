# Mental Health Disorder Detection Beyond Social Media: Datasets

A collection of non-social media, free-text datasets for mental health disorder detection, compiled as part of the first systematic review of such resources.

## 📚 Data Availability

The labels for data availability are explained below:

* **PUB** - The dataset is publicly available mentioned in teh paper.
* **DUA** - The data is available only after a Data Use Agreement is signed. 
* **RSTR** - The dataset is restricted; access requires formal approval from the data owner or institution.
* **UNK** - The dataset availability is unknown; the authors do not mention if the data is available to the research community.


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
| [Pestian et al. (2012)](https://journals.sagepub.com/doi/full/10.4137/BII.S9042) | EN | SD | CLINIC | SD Notes | Manual | Krippendorff's α | 15 | 1,004 | DUA |
| [Uzuner et al. (2017)](https://pmc.ncbi.nlm.nih.gov/articles/PMC5705440/) | EN | DP, PTSD, OCD, BD | CLINIC | Clinical Notes | Manual | — | 4 | 816 | DUA |
| [Jackson et al. (2017)](https://bmjopen.bmj.com/content/7/1/e012012.abstract) | EN | SMI | CLINIC | EHR (DS) | Manual | Text Hunter | 50 | 37,211 | RSTR |
| [Low et al. (2010)](https://pubmed.ncbi.nlm.nih.gov/21075715/) | EN | MDD | CLINIC | Interview | Manual | LIFE | 2 | 139 | RSTR |
| [Pestian et al. (2010)](https://journals.sagepub.com/doi/full/10.4137/BII.S4706) | EN | SD | CLINIC | SD Notes | Manual | Ontology | 2 | 66 | RSTR |
| [Geraci et al. (2017)](https://mentalhealth.bmj.com/content/20/3/83) | EN | MDD & DD | CLINIC | EMR | Manual | DSM-IV | 2 | 861 | RSTR |
| [Zhou et al. (2015)](https://pubmed.ncbi.nlm.nih.gov/26262127/) | EN | DP | CLINIC | EHR (DS) | Manual | — | 3 | 1,200 | UNK |
| [Meng et al. (2021)](https://pubmed.ncbi.nlm.nih.gov/32749975/) | EN | DP | CLINIC | EHR | Manual | ICD-9 & AD | 2 | 10,148 | UNK |
| [Marrie et al. (2018)](https://www.researchprotocols.org/2018/1/e15) | EN | DP & AX | CLINIC | Interview | Manual | DSM-IV | — | 308 | UNK |
| [Diederich et al. (2007)](https://www.sciencedirect.com/science/article/abs/pii/S1568494606000457) | EN | SZ | CLINIC | Essay | Manual | — | 2 | 56 | UNK |
| [Poulin et al. (2014)](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0085733) | EN | SD | CLINIC | Clinical Notes | Manual | — | 3 | 210 | UNK |
| [Saini et al. (2014)](https://econtent.hogrefe.com/doi/abs/10.1027/0227-5910/a000277?journalCode=cri) | EN | SZ, DP, BD, SD & Other | CLINIC | Interview & Clinical Notes | Manual | — | 2 | 198 | UNK |
| [Milne et al. (2016)](https://aclanthology.org/W16-0312/) | EN | MHD | FORUM | Post | Manual | Fleiss's Kappa & Cohen's Kappa | 4 | 1,227 | PUB |
| [He et al. (2017)](https://journals.sagepub.com/doi/abs/10.1177/1073191115602551) | EN | PTSD | FORUM | Essay | Manual | DSM-IV & CAP Scale | 2 | 300 | UNK |
| [Tyshchenko (2018)](https://www.semanticscholar.org/paper/Depression-and-anxiety-detection-from-blog-posts-Tyshchenko/1bb124de4453065a333254396ed439fa662229ce) | EN | DP & AX | FORUM | Post | Self-disclosure | — | 2 | 16,975 | UNK |
| [Nguyen et al. (2014)](https://www.computer.org/csdl/journal/ta/2014/03/06784326/13rRUx0xPgz) | EN | DP, BD & SD | FORUM | Post | Self-disclosure | — | 2 | 267,964 | UNK |
| [Aich et al. (2022)](https://aclanthology.org/2022.findings-emnlp.208/) | EN | SZ & BD | COLLEGE | Interview | Manual | DSM-V & DSM-IV | 3 | 644 | DUA |
| [Rude et al. (2004)](https://www.tandfonline.com/doi/abs/10.1080/02699930441000030) | EN | DP | COLLEGE | Essay | Manual | BDI & IDD-L | 3 | 124 | UNK |
| [Rheault (2016)](https://aclanthology.org/W16-5612/) | EN | AX | DEBATE | Political Speech | Manual | — | 2 | 4,000 | PUB |
| [Hull et al. (2020)](https://link.springer.com/article/10.1186/s12888-020-02721-x?a5a27e8f_page=2) | EN | DP & AX | Telemedicine Platform | Message | Manual | PHQ-9, GAD-7 | 10 | 718 | DUA |
| [Krishnamurti et al. (2022)](https://www.sciencedirect.com/science/article/pii/S1877050922009656) | EN | PD | APP | Essay | Manual | EPDS | 2 | 1,091 | UNK |
| [Nobles et al. (2018)](https://dl.acm.org/doi/abs/10.1145/3173574.3173987) | EN | DP & SD | Phone | SMS | Manual | Self-Disclosure | 2 | 94 | UNK |
| [Howes et al. (2014)](https://aclanthology.org/W14-3202/) | EN | DP & AX | Online Therapy | Chat Dialogue | Mixed | MALLET & LIWC | 2 | 882 | UNK |
| [Ringeval et al. (2019)](https://dl.acm.org/doi/abs/10.1145/3347320.3357688) | EN | DP & PTSD | Virtual Agent | Interview | Manual | PHQ-8 | 5 | 275 | DUA |
| [Schoene and Dethlefs (2016)](https://aclanthology.org/W16-2116/) | EN | DP & SD | MIXED | SD Notes & Articles | Manual | — | 12 | 426 | UNK |
| [Gratch et al. (2014)](https://aclanthology.org/L14-1421/) | EN | DP, AX & PTSD | MIXED | Interview | Manual | — | — | 621 | DUA |
| [Ghosh et al. (2020)](https://aclanthology.org/2020.lrec-1.201/) | EN | DP & SDI | MIXED | SD Notes & Book | Manual | Cohen's Kappa | 15 | 2,393 | PUB |
| [Tasnim et al. (2022)](https://aclanthology.org/2022.clpsych-1.1/) | EN | DP & AX | mTurk | Interview | Manual | PHQ-9, GAD-7 | 2 | 674 | UNK |
| [Caicedo et al. (2020)](https://www.sciencedirect.com/science/article/pii/S2405844020312561) | EN-ES | DP & SDI | Social Network & Forum | Post | Manual | Cohen's Kappa | 4 | 102 | PUB |
| [Wu et al. (2020)](https://www.sciencedirect.com/science/article/pii/S0165032719306172?casa_token=URI-0qlU1sEAAAAA:fHBZgOFJSWkiJRkbYcWnB6VQAHRQNmZlsDU7lrFwCuQxfBqvGeEivu68GgRaud_UijOHkHjmUQ) | EN-ZH | MDD, MinDP, SZ, BD, AjD, DEM & Other | CLINIC | EHR (DS) | Manual | DSM-IV, Sheehan Disability Scale | 9 | 4,836 | RSTR |
| [Zou et al. (2023)](https://dl.acm.org/doi/abs/10.1109/TAFFC.2022.3181210) | ZH | MDD | CLINIC | Interview | Manual | HAMD & PHQ-9 | 2 | 78 | PUB |
| [Jiang et al. (2022)](https://link.springer.com/chapter/10.1007/978-3-031-37660-3_49) | ZH | DP & AX | CLINIC | Interview | Manual | HAMD & HAMA | 3 | 1,025 | PUB |
| [Xu et al. (2025)](https://www.nature.com/articles/s44184-025-00175-1) | ZH | DP & AX | CLINIC | EMR | Manual | DSM-V & ICD-10 | 4 | 1,160 | PUB |
| [Mao et al. (2023)](https://pubmed.ncbi.nlm.nih.gov/37399151/) | ZH | DP | CLINIC | Interview | Manual | MADRS | 2 | 113 | DUA |
| [Ive et al. (2024)](https://arxiv.org/abs/2501.00129) | ZH | AX | CLINIC | EHR | Manual | ICD-9 & ICD-10 | 2 | 84,426 | RSTR |
| [Li et al. (2023)](https://medinform.jmir.org/2023/1/e50221/) | ZH | DP & SD | CLINIC | Interview | Manual | HAMD | 3 | 305 | UNK |
| [Shen et al. (2022)](https://arxiv.org/abs/2202.08210) | ZH | DP | APP | Interview | Manual | SDS | 2 | 162 | PUB |
| [Mo et al. (2024)](https://www.researchgate.net/publication/369300842_A_Multimodal_Data-driven_Framework_for_Anxiety_Screening) | ZH | AX | Phone Recording | Essay | Manual | GAD-7 | 3 | 227 | UNK |
| [Shin et al. (2022)](https://www.frontiersin.org/journals/psychiatry/articles/10.3389/fpsyt.2022.801301/full) | KO | DP, AX & SD | CLINIC | Interview | Manual | PHQ-9, HDRS, BAI & BSS | 2 | 166 | DUA |
| [Figueroa-Barra et al. (2022)](https://pubmed.ncbi.nlm.nih.gov/35853943/) | KO | SZ & FEP | CLINIC | Interview | Manual | DSM-V, PANSS | 3 | 133 | RSTR |
| [Wawer et al. (2022)](https://link.springer.com/article/10.1007/s12559-021-09834-9) | PL | SZ | CLINIC | Interview | Manual | ICD-10 | 2 | 94 | UNK |
| [Oh et al. (2024)](https://www.frontiersin.org/journals/psychiatry/articles/10.3389/fpsyt.2023.1256571/full) | ES-CL | DP | CLINIC | Interview | Manual | DSM-V | 8 | 451 | UNK |
| [Hämäläinen et al.](https://aclanthology.org/2021.wnut-1.3/) | TH | DP | FORUM | Post | Manual | Keyword Search | 2 | 944 | PUB |
| [Hiraga (2017)](https://aclanthology.org/P17-3018/) | JA | DP | FORUM | Post | Self-disclosure | — | 2 | 108 | UNK |
| [Alghamdi et al. (2020)](https://www.semanticscholar.org/paper/Predicting-Depression-Symptoms-in-an-Arabic-Forum-Alghamdi-Mahmoud/c32965d654b4a16c4fd1bfe947b0a0d6c6697ea6) | AR | DP | FORUM | Post | Self-disclosure & Manual | DSM-5, PHQ-9, QIDS-SR | 2 | 20,000 | UNK |
| [Mulholland and Quinn](https://aclanthology.org/I13-1079/) | EN | SD | Online DB | Song Lyrics | Manual | — | 2 | 810 | UNK |
| [Zervopoulos et al. (2019)](https://link.springer.com/chapter/10.1007/978-3-030-19909-8_15) | EL | SDI | — | Poem | Manual | — | 2 | 90 | UNK |
| [Reynolds and Wilson (2013)](https://journals.sagepub.com/doi/full/10.1177/0141076813486262) | CF | DP, AX & PA | Tablets | — | — | — | — | — | UNK |

---

