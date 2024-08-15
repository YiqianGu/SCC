# PD-1 blockade plus cisplatin-based chemotherapy in patients with small cell / neuroendocrine bladder and prostate cancers
## Overview
Small cell neuroendocrine cancers share biologic similarities across tissue types, including a transient response to platinum-based chemotherapy with rapid progression of disease. We report a phase Ib study of pembrolizumab in combination with platinum-based chemotherapy in 15 patients with stage III-IV small cell bladder (cohort 1) or small cell / neuroendocrine prostate cancers (cohort 2). Overall response rate (ORR) was 43% with two-year overall survival (OS) rate of 86% (95% CI:0.63,1.00) for cohort 1 and 57% (95% CI:0.30,1.00) for cohort 2. Treatment was tolerated well with grade 3 or higher adverse events occurring in 40% of patients with no deaths or treatment cessation secondary to toxicity. Single cell and T cell receptor sequencing of serial peripheral blood samples revealed clonal expansion of a diverse T cell repertoire correlating with progression free survival. Our results demonstrate promising efficacy and safety of this treatment combination and support future investigation of this biomarker.

## Raw data
Raw data are stored at GEO

Bulk RNA sequencing:GSE273798

Single cell RNA sequencing: GSE266079

## Processed data and scripts
Processed data and scripts are stored at [box](https://ucla.box.com/s/6u5y1hheyag7bcx9cq6rolnmlzs1y7uw)

### Bulk RNA sequencing 

Processed data after alignment: SCC_github/bulk_RNA_sequencing/expr/

Input data for CIBERSORTx: SCC_github/bulk_RNA_sequencing/analysis/CIBERSORTx/

Scripts and figures for this paper: SCC_github/bulk_RNA_sequencing/analysis/

## single cell RNA sequancing
Processed data after alignment: SCC_github/single_cell_sequencing/expr_matrices/

TCR clone definition: SCC_github/single_cell_sequencing/analysis/TCR

Seurat objects of T cell, B cell, and Myeloid cell: SCC_github/single_cell_sequencing/analysis/GEX_seurat/subtype/

Scripts and figures about single-cell T cell gene expression matrix to TCR connection: SCC_github/single_cell_sequencing/analysis/GEX_seurat/subtype/T cell/

Aggregated Seurat objects of three major cell types, as well as scripts and figures:  SCC_github/single_cell_sequencing/analysis/GEX_seurat/subsample/

