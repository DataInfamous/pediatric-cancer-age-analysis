# Pediatric Cancer Age Incidence Analysis

## Overview

This project explores **age-related incidence patterns of pediatric cancer subtypes** using data from the Pediatric Cancer Knowledgebase (PeCan). The goal is to visualize how different cancers emerge across developmental stages from infancy through adolescence.

The analysis demonstrates exploratory data science techniques including data cleaning, distribution analysis, smoothing, and multiple forms of visualization to better understand developmental timing patterns in pediatric cancers.

---

## Dataset

The dataset used in this project comes from the **Pediatric Cancer Knowledgebase (PeCan)**, an integrated resource for pediatric cancer genomics and clinical data.

PeCan provides curated information on pediatric tumor subtypes, molecular variants, and clinical characteristics.

Fields used in this analysis include:

* `diagnosis_subtype_name`
* `age_at_diagnosis_yrs`
* `diagnosis_subtype_code`

### Source

Zhang, J., Walsh, M. F., Wu, G., Edmonson, M. N., Gruber, T. A., Easton, J., Hedges, D., Ma, X., Zhou, X., Yergeau, D. A., Wilkinson, M. R., Vadodaria, B., Chen, X., McGee, R. B., Hsieh, C. L., Lu, C., Ding, L., Wilson, R. K., Downing, J. R., & St. Jude Children’s Research Hospital–Washington University Pediatric Cancer Genome Project. (2015). **Germline Mutations in Predisposition Genes in Pediatric Cancer.** *New England Journal of Medicine*, 373(24), 2336–2346.

PeCan Portal:
https://pecan.stjude.cloud

---

## Methods

The analysis follows a typical **exploratory data analysis workflow** used in biomedical data science.

### 1. Data Cleaning

* Removed missing age values
* Converted age fields to numeric format
* Filtered the most common cancer subtypes for visualization

### 2. Frequency Analysis

Cancer subtype frequencies were computed to identify the most common pediatric tumor categories in the dataset.

### 3. Age Distribution Analysis

Age distributions were analyzed using smoothed density curves and histogram aggregation.

### 4. Visualization Techniques

The notebook generates multiple visualization types:

* Heatmaps of cancer incidence by age
* Relative risk heatmaps
* 3D incidence landscape plots
* Ridge plots showing smoothed age distributions

Gaussian smoothing was applied to better visualize distribution patterns.

---

## Key Observations

The analysis reveals clear developmental patterns in pediatric cancers.

### Early Infancy

* Neuroblastoma
* Retinoblastoma

These cancers frequently occur in infants and toddlers.

### Early Childhood

* Wilms Tumor
* Acute Lymphoblastic Leukemia (ALL)

These cancers peak between ages 3–6.

### Childhood Brain Tumors

* Medulloblastoma
* Pilocytic Astrocytoma
* Posterior Fossa Ependymoma

These show broader distributions across childhood.

### Adolescence

* Osteosarcoma

This cancer demonstrates a strong peak during adolescence, consistent with rapid bone growth during puberty.

These findings align with established pediatric oncology literature.

---

## Visualizations

### Ridge Plot

Shows smoothed age distributions for major pediatric cancer subtypes.

### Heatmap

Displays absolute counts of cancer diagnoses across age groups.

### Relative Risk Heatmap

Highlights which cancers are disproportionately associated with certain developmental stages.

### 3D Incidence Landscape

Provides a three-dimensional view of how cancer subtype incidence changes across age.

---

## Tools and Libraries

Python
Pandas
NumPy
Matplotlib
SciPy
Jupyter Notebook

---

## Potential Extensions

Future analyses could include:

* survival analysis of pediatric cancers
* clustering of developmental cancer patterns
* machine learning models predicting cancer subtype
* integration with genomic mutation data

---

## References

Zhang, J., Walsh, M. F., Wu, G., Edmonson, M. N., Gruber, T. A., Easton, J., et al. (2015). Germline mutations in predisposition genes in pediatric cancer. *New England Journal of Medicine*, 373(24), 2336–2346.

Downing, J. R., Wilson, R. K., Zhang, J., Mardis, E. R., Pui, C. H., Ding, L., et al. (2012). The Pediatric Cancer Genome Project. *Nature Genetics*, 44(6), 619–622.

St. Jude Cloud. Pediatric Cancer Knowledgebase (PeCan).
https://pecan.stjude.cloud

---

## Author

Benjamyn Wilson
Data Science Student
University of Maryland Global Campus
