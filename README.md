# A Computational Approach for Designing Novel Therapeutics for Osteoarthritis

## 📌 Project Overview
Osteoarthritis (OA) is a progressive joint disorder characterized by cartilage degradation, inflammation, and pain. Current treatments primarily offer symptomatic relief and fail to modify disease progression. This project adopts a **computational drug discovery approach** to identify potential therapeutic lead molecules targeting **Interleukin-17A (IL-17A)**, a pro-inflammatory cytokine implicated in OA pathology.

Using molecular docking and virtual screening techniques, natural compounds and their analogs were screened against IL-17A to explore their binding potential and inhibitory prospects.

---

## 🎯 Aim
To identify and design potential lead molecules targeting IL-17A for osteoarthritis treatment using computational docking and virtual screening methods.

---

## 🧠 Rationale
Existing OA treatments such as NSAIDs, corticosteroids, and analgesics provide only temporary symptomatic relief without halting cartilage degeneration. Targeting IL-17A, which contributes to inflammation and matrix degradation, presents a promising strategy for disease-modifying therapy.

---

## 🧪 Methodology

### 1. Disease & Target Selection
- Evaluated ~10 OA-related targets (e.g., IL-17A, MMP-13, ADAMTS-5)
- Selection criteria included druggability, structural availability, and biological relevance
- **IL-17A** chosen as the final target

### 2. Protein Structure Selection
- Multiple IL-17A structures analyzed from the Protein Data Bank
- **PDB ID: 4HSA** selected based on resolution, missing residues, and structural suitability
- Relevant IL-17A chains extracted for docking

### 3. Receptor Preparation
- Removal of water molecules, heteroatoms, and inhibitors
- Addition of hydrogens and Kollman charges
- Prepared using **AutoDock Tools**

### 4. Ligand Preparation
- ~120 natural compounds and analogs sourced from the **ZINC database**
- Compounds prepared and optimized for docking

### 5. Grid Box Generation
- Defined around the IL-17A binding site
- Coordinates optimized for exhaustive virtual screening

### 6. Virtual Screening
- Docking performed using **AutoDock Vina**
- Batch docking automated using a **Perl script**
- Output included docking poses and log files for each ligand

---

## 📊 Results
- Successful docking of ~120 ligands with IL-17A
- Binding poses visualized using **PyMOL**
- Ligands occupied the predicted binding pocket and interacted with key residues
- Quantitative binding affinity analysis was not completed due to time constraints

---

## 🧩 Tools & Technologies
- AutoDock
- AutoDock Vina
- PyMOL
- Perl scripting
- ZINC Database
- RCSB Protein Data Bank

---

## 🚀 Future Scope
- Detailed binding energy and interaction analysis
- Ranking and optimization of lead compounds
- Molecular dynamics simulations for stability assessment
- Experimental validation of shortlisted compounds

---

## 👩‍🔬 Author
**Asfiya Tehmeen**  
Birla Institute of Technology, Dubai  
Design Project – Pre-Final Year
