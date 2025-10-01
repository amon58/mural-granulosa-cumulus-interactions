This repository contains two main types of analysis focusing on mural granulosa cells (MGCs) and cumulus cells (CCs):

1. **Time-course analysis of differentially expressed genes (DEGs)**  
   We identified genes showing temporal expression changes in MGCs and CCs using **DESeq2**.  

2. **Time-specific interactome analysis**  
   We inferred cell–cell communication networks between MGCs and CCs at different time points, using bulk RNA-seq data informed by cell numbers derived from single-cell RNA-seq.  

### Interactome analysis workflow

1. **Cell number estimation**  
   The relative numbers of MGCs and CCs were obtained from single-cell RNA-seq analysis.  

2. **Data expansion**  
   Bulk RNA-seq data were scaled according to the estimated cell numbers, thereby simulating cell-type–specific contributions.  

3. **Interactome inference**  
   Interactome analysis was performed using the expanded bulk RNA-seq dataset to predict potential cell–cell communication networks between MGCs and CCs.  

---

This approach enables bulk RNA-seq data to be interpreted in the context of cellular composition revealed by single-cell data, resulting in a more biologically relevant and time-resolved interactome map.  
