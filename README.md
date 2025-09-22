# Research-Automated-Threat-Modeling-using-AI

This repository provides datasets, figures, and evaluation outputs for the paper:

**"Automated Threat Modeling using Artificial Intelligence on User Stories within the SDLC to Generate Security Tasks"** (submitted to ICCWS 2026).

---

## Repository Structure

### 📂 Dataset
Contains the raw dataset and system configuration used in experiments:
- `Exported_From_Jira.csv` – A dataset of 10 example user stories originally created as Jira issues and exported directly from Jira.  
- `System_Prompt.txt` – The LLM system prompt used for automated threat modeling generation.  
- `User_Prompt.txt` – The exact User Story used in this reseach to generate threat modeling outputs for reproducibility.  

> **Note**: The following user story was generated using AI from the *Add Photos & Files* feature by uploading **Figure 1** in ChatGPT-5, and is used in this research.

---

### 📂 Figures
Figures included in the paper and supporting materials:
- `Figure_1_OWASP_Juice_Shop_Architecture_Diagram.png`  
- `Figure_2_System_Architecture_AI_Driven_Threat_Modeling.png`  
- `Figure_3_OWASP_Juice_Shop_Security_Tasks_ChatGPT5.png`  
- `Figure_4_OWASP_Juice_Shop_Compliance_Alignment_Mapping_ChatGPT5.png`  
- `Figure_5_AI_Output_in_JSON_Format.png`  

---

### 📂 Outputs
Evaluation outputs from different models on the OWASP Juice Shop case study:
- `ChatGPT-5_OWASP_Juice_Shop.json`  
- `Gemini-Pro_OWASP_Juice_Shop.json`  
- `Gemini-Pro_OWASP_Juice_Shop.md`  

---

## Evaluation Setup

The dataset supports three research questions (RQ1–RQ3):

- **RQ1 – Threat Classification Accuracy**  
  Each Jira item is annotated with expected **STRIDE categories**.

- **RQ2 – Standards Compliance Coverage**  
  Security tasks mapped to major compliance frameworks:  
  *NIST CSF, ISO 27001, PCI DSS, HIPAA, SOC 2, OWASP ASVS, GDPR*.

- **RQ3 – Workflow Integration**  
  Subtasks generated in **Jira-compatible structures** (titles, descriptions, acceptance criteria).

---

## Usage

Clone the repository and navigate through the folders:

```bash
git clone https://github.com/ShantuApps/Reseach-Automated-Threat-Modeling-using-AI.git
```

- Explore **Dataset/** for CSV and system prompt.  
- Use **Outputs/** to compare model-generated results.  
- Check **Figures/** for paper-ready visualizations.  

---

## License

This repository is provided for academic and research purposes only.  
Please reference the citation below when using the dataset, figures, or outputs.

---

## How to Cite

If you use this dataset or outputs in your research, please cite:

**APA style (for papers):**  
Hossain, S. A. (2026). *AI-Driven Threat Modeling Integrated in the SDLC: A Case Study*. Proceedings of the 21st International Conference on Cyber Warfare and Security (ICCWS), University of North Carolina Wilmington, USA. Academic Conferences International. (To appear).

**BibTeX (for LaTeX users):**
```bibtex
@inproceedings{Hossain2026AIThreatModeling,
  author    = {Shantu Asif Hossain},
  title     = {Automated Threat Modeling using Artificial Intelligence on User Stories within the SDLC to Generate Security Tasks},
  booktitle = {Proceedings of the 21st International Conference on Cyber Warfare and Security (ICCWS 2026)},
  year      = {2026},
  address   = {University of North Carolina Wilmington, USA},
  publisher = {Academic Conferences International},
  note      = {To appear}
}
```
---
