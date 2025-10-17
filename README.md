# fastqc-quality-assessment

### 🧬 Project Overview

This project performs **quality assessment of sequencing data** using the **FastQC** tool.  
It analyzes `.fastq` files and generates detailed reports on sequence quality, GC content, adapter contamination, and other metrics.

---

### ⚙️ Steps to Run

```bash
# 1. Activate the conda environment
conda activate fastqc_env

# 2. Run FastQC on the sample file
fastqc sample_small.fastq -o results/

# 3. View the report
open results/sample_small_fastqc.html ---

Теперь шаги 👇  

### 🔹 Шаг 1.
Поставь курсор **в самый конец** этого текста — после последней строки  
`open results/sample_small_fastqc.html`  

### 🔹 Шаг 2.
Нажми **Enter** (чтобы спуститься на новую строку).

### 🔹 Шаг 3.
Скопируй и вставь **вот этот блок целиком** ↓

---

```markdown
---

### 📊 Output

After running FastQC, two files are generated in the `results/` folder:
- `sample_small_fastqc.html` — interactive quality report  
- `sample_small_fastqc.zip` — compressed data with raw metrics  

---

### 📈 Interpretation

The FastQC report provides information about:
- Per base sequence quality  
- Sequence length distribution  
- GC content  
- Adapter sequences  
- Overrepresented sequences  

You can open the `.html` report in your browser to explore the results.

---

### 🧠 Example Interpretation Summary

Based on the FastQC output:
- **Per base quality** is high — indicating good sequencing performance.  
- **GC content** is slightly deviated — could suggest minor contamination or sequencing bias.  
- **No overrepresented adapters** detected — data is clean and ready for downstream analysis.  

---

### 🧾 Author

**Zubaira Abyzgalikyzy**  
Beginner bioinformatics project for portfolio demonstration.  
Quality control of sequencing reads using FastQC
