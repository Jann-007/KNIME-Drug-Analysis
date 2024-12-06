# KNIME-Drug-Analysis
Hey this is a drug analysis (Selumetinib) project working on KNIME with few MEK inhibitor library screen.
### **Project Overview**  
This repository contains the workflow and results of a study to identify drugs structurally similar to **Selumetinib**, a MEK inhibitor used for treating **Neurofibromatosis Type 1 (NF1)-associated tumors**. The goal of this project is to explore alternative MEK inhibitors or structurally related compounds using computational tools like KNIME.  

---

### **Problem Statement**  
**Selumetinib** is a key therapeutic agent targeting MEK signaling pathways in NF1-associated tumors. Identifying structurally similar drugs can offer insights into alternative options for improved efficacy, reduced side effects, or drug repurposing. This study employs 2D and 3D conformer analyses to investigate molecular similarities.  

---

### **Workflow and Tools**  

#### **Data Source:**  
- Drug database: PubChem.  
- Drug library: MEK inhibitors.  

#### **Tools Used:**  
- **KNIME** for computational analysis, including feature extraction, similarity scoring, and visualization.  

#### **Analysis Methods:**  
1. **2D Similarity Analysis:** Based on Tanimoto coefficients.  
2. **3D Conformer Analysis:** Using Root Mean Square Deviation (RMSD).  

#### **Key Steps:**  
1. **Data Pre-processing:**  
   - Retrieval of molecules from PubChem.  
   - Conversion to standard formats (e.g., SMILES, SDF).  
   - Structural normalization.  
2. **Feature Extraction:**  
   - Calculation of 2D and 3D molecular descriptors.  
3. **Similarity Analysis:**  
   - Scoring based on Tanimoto (2D) and RMSD (3D).  
4. **Visualization:**  
   - Heatmaps and scatter plots for interpretability.  
5. **Filtering:**  
   - Shortlisting compounds with high similarity scores (e.g., Tanimoto > 0.8).  

---

### **Results**  

#### **Top Similar Drugs:**  
- **2D Similarity:**  
  - Tanimoto Scores: 0.85, 0.90, 0.95, 1.00.  
- **3D Similarity:**  
  - RMSD Scores: 0.00, 0.20, 0.50, 0.80.  

---

### **Conclusion**  
This project highlights the potential of computational tools in drug discovery, particularly for structurally similar drug identification. By integrating 2D fingerprint analysis with 3D spatial alignment, a comprehensive molecular similarity evaluation was performed. The findings contribute to understanding Selumetinib’s molecular space and suggest alternative MEK inhibitors for further investigation.  

---

### **Repository Contents**  
- **workflow/**: KNIME workflows for 2D and 3D analyses, including scatter plots and heatmaps.  
- **visualization/**: Graphical results and visual insights.  
- **data/**: Processed and raw datasets used in the study.  
- **results/**: Summary tables of identified similar compounds.  

---

### **How to Use**  
1. Clone this repository:  
   ```bash  
   git clone https://github.com/Jann-007/KNIME-Drug-Analysis
   ```  
2. Follow the instructions in the **workflow/README.md** to set up and execute the KNIME workflows.  
3. Review the results and visualizations in their respective directories.  

---  
