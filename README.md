# REX2022
## Current Goal:  
1. Download [astrocyte dataset](https://drive.google.com/drive/folders/1BWDbcNg-jz6i7jKuQQWm1-YXYCeAQ0KI?usp=sharing)
2. Import into R using command: `astro <- read.csv("Human_Male_ERC_CTRL_Astrocytes_.csv", row.names = 1)`  
3. Try and run the [Seurat tutorial](https://satijalab.org/seurat/articles/pbmc3k_tutorial.html) on this dataset  
4. Make sure to save the `.R` script you used to analyze the data
5. Save your analyzed data object using: `saveRDS("myfilename.rds")`  
6. This can be re-loaded later via: `readRDS("myfilename.rds")` so that you don't need to re-analyze every time!
**SUGGESTIONS:**  
- try not filtering the data at first, see how filtering it by `nFeature_RNA` and `percent.mt` changes the final data
- try doing a PCA & UMAP on `dims = 1:20`, `dims = 1:10`, `dims = 1:5`, see how this changes the final data
- try changing the clustering resolution, see how this changes the final data
- test out `FindMarkers()` if you have the time!
