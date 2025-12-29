# CellFuse_Manuscript_Reproduce
This repo contains code and data to reproduce CellFuse manuscript's figure.
As a starter install CellFuse pacakges from https://github.com/karadavis-lab/CellFuse and then download this repo.
Fig 2
Bone marrow (Fig 2A, C, D, E, I, Supplementary Fig 1 and 2)
1.	Fig 2/BM/Reference/ Fig2_BM_prepare_data.R: Prepare bone marrow for CellFuse
2.	Fig 2/BM/ BM_CellFuse_Integration.R: Run CellFuse
3.	Fig 2/BM/BM_Running_Benchmark_Methods.R:  Run benchmarking methods (Harmony, Seurat, FastMNN)
4.	Fig 2/BM/BM_scVI_scnorama.ipynb: Run scanorama and scVI
5.	Fig 2/BM/BM_scIB.ipynb: Evaluate methods using scIB and save results
6.	Fig 2/BM/BM_Data_visualisation.R: tSNE visualization
7.	Fig 2/BM/Sequential_Feature_drop/Prepare_data.R: Prepare data for evaluating sequential feature drop
8.	Fig 2/BM/Sequential_Feature_drop/ Run_FastMNN_Seurat_Harmony.R: Run CellFuse, Harmony, Seurat and FastMNN for sequential feature drop
9.	Fig 2/BM/Sequential_Feature_drop/ BM_scVI_scnorama_feature_drop.ipynb: Run scVI and Scanorama for sequential feature drop
10.	Fig 2/BM/Sequential_Feature_drop/ BM_scIB_feature_drop.ipynb: Evaluate feature dropping methods using scIB and save results
11.	Fig 2/BM/Sequential_Feature_drop/ BM_scIB_Data_viz.R: visualize scIB results
PBMC (Fig 2B,F,G, H, Supplementary Fig: 3 and 4)
1.	Fig 2/PBMC/Reference/ Fig2_PBMC_prepare_data.R: Prepare PBMC data for CellFuse
2.	Fig 2/ PBMC / PBMC_CellFuse_Integration.R: Run CellFuse
3.	Fig 2/ PBMC /PBMC_Running_Benchmark_Methods.R:  Run benchmarking methods (Harmony, Seurat, FastMNN)
4.	Fig 2/PBMC/PBMC_scVI_scnorama_feature_drop.ipynb: Run scVI and Scanorama
5.	Fig 2/PBMC/PBMC_scIB.ipynb: Evaluate methods using scIB and save results
6.	Fig 2/PBMC/PBMC_Data_visualisation.R: tSNE visualization

7.	Fig 2/ PBMC/ RunTime_benchmark/ Prepare_data.R: Prepare data
8.	Fig 2/ PBMC/ RunTime_benchmark/ run_all_methods.txt.R: This file contain info how to run time and memory usage for each method. This file requires following files:
a.	cellfuse_run_measure.R
b.	fastmnn_run_measure.R
c.	seurat_run_measure.R
d.	harmony_run_measure.R
e.	scanorama_runtime.py
f.	scvi_scanvi_runtime.py
9.	Fig 2/ PBMC/ RunTime_benchmark/ Runtime_Data_viz.R:  Visualize runtime and memory usage data
Fig 3
Good et al. CART: Fig 3A-F and Supplementary Fig 5, 6A and B
1.	Fig 3/ Good_et_al/Reference/ Fig3_CyTOF_prepare_data.R: Prepare CyTOF and CITE-Seq data for CellFuse
2.	Fig 3/ Good_et_al/CellFuse_Integration_CyTOF.R: Run CellFuse to remove batch effect and integrate CyTOF data from day 7 post-infusion
3.	Fig 3/ Good_et_al/CellFuse_Integration_CITESeq.R: Run CellFuse to integrate CyTOF and CITE-Seq data
4.	Fig 3/ Good_et_al/CART_Data_visualisation.R: Visualize data
Domizi et al. CART: Fig 3G and H and Supplementary Fig 6C
1.	Fig3/Domizi_et_al/ Data_Analysis.R: this file contains all code for prepaprocessing, CellFuse run and data visualization

Fig 4 
HuBMAP CODEX data (Fig. 4A, B, C, D and Supplementary Fig 7)
1.	Fig 4/CODEX_colorectal/Reference/ CODEX_HuBMAP_prepare_data.R: Prepare CODEX data from annotated and unannotated donor
2.	Fig 4/ CODEX_colorectal/ CODEX_HuBMAP_CellFuse_Predict.R: Run CellFuse on cells from from annotated and unannotated donor
3.	Fig 4/ CODEX_colorectal/CODEX_HuBMAP_Data_visualisation.R: Visualize data and prepare figures.
4.	Fig 4/ CODEX_colorectal/ Benchmarking/Astir/Astrir.ipynb: Run Astir 
5.	Fig 4/ CODEX_colorectal/ Benchmarking/SpatialAnno.R: run SpatialAnno
6.	Fig 4/ CODEX_colorectal/ CODEX_HuBMAP_Benchmark.R: Benchmarking CellFuse against CELESTA, SVM, SpatialAnno, Astir and Seurat using cells from annotated donors and prepare figures.
7.	Fig 4/ CODEX_colorectal/CODEX_HuBMAP_Suppl_figure_heatmap.R: F1score calculation per celltype per Benchmarking methods and heatmap comparing celltypes from annotated and unannotated donors (Supplementary Fig 7)
IMC Breast cancer data (Fig. 4E,F, G and Supplementary Fig 7)
1.	Fig 4/ IMC_Breast_Cancer/ IMC_prepare_data.R: Prepare CODEX data from annotated and unannotated donor
2.	Fig 4/ IMC_Breast_Cancer/ IMC_CellFuse_Predict.R: Run CellFuse to predict cell types
3.	Fig 4/ IMC_Breast_Cancer/ IMC_dat_visualization.R: Visualize data and prepare figures.
4.	Fig 4/ IMC_Breast_Cancer/ Suppl_Per_Patient_Confusion_Matrix.R: Suppl. Fig8
5.	Fig 4/ IMC_Breast_Cancer/ Benchmark_random_split.R: Suppl. Fig 9B
6.	Fig 4/ Concordance.R: Spatial concordance analysis for IMC and CODEX data
Fig 5
1.	Fig5/ Reference/ Fig5_CyTOF_Data_prep.R: Prepare CyTOF data from healthy PBMC and healthy colon single cells
2.	Fig5/ MIBI_CellFuse_Predict.R: Run CellFuse to predicte cells from colon cancer patients
3.	Fig5/ MIBI_PostPrediction.R: Visualize data and prepare figures
4.	Fig5/ Predicted_Data/ mask_generation.ipynb: Post CellFuse prediction annotated cell types in segmented images. This will generate Fig5C and D


