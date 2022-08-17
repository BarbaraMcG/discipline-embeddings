# Code for "Investigating patterns of change, stability, and interaction among scientific disciplines using embeddings"
Code for the article "Investigating patterns of change, stability, and interaction among scientific disciplines using embeddings", co-authored with Gard B Jenset, Khalid Salama and Donna Schut.

## Generate embeddings
3-year window FoR mean centroids.ipynb: generate embeddings for FoR codes by averaging article title embeddings

## Evaluate embeddings
FoR embeddings_evaluation.ipynb: intrinsic evaluation of cooccurrence-defined FoR embeddings for different combinations of hyperparameters
FoR embeddings_evaluation_analysis.ipynb: analysis of evaluation results of cooccurrence-defined FoR embeddings to find the best configuration of hyperparameters for the cooccurrence-defined FoR embeddings.

## Similarity analysis
FoR_embeddings_analysis_2.ipynb: analysis of cooccurrence-defined FoR embeddings within each time period, using cosine and neighbourhood similarity measures NOTE: this is not the most recent version, see below.

unified_FoR_embedding_analysis.ipynb: analysis of cooccurrence-defined FoR embeddings within each time period, using cosine and neighbourhood similarity measures, by area, cluster and level 1; analysis of profile change via neighbourhood analysis

## Profile change
Profile_change.ipynb: Analysis of change in profile of cooccurrence-defined FoR adapting semantic change research to FoR embeddings.
Output files are in the “analysis/profile change” directory
Subdirectory: “distance0.5” contains the output files when the cosine similarity threshold for a profile change is 0.5
Selected_FoR_embeddings_analysis_neighbours.ipynb: Qualitative neighbourhood analysis for selected FoRs
