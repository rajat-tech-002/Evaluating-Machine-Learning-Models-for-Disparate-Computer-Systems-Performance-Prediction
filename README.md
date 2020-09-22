# Evaluating-Machine-Learning-Models-for-Disparate-Computer-Systems-Performance-Prediction
Performance prediction is an active area of research
due to its applications in the advancements of hardware-software
co-development. Several empirical machine-learning models such
as linear models, tree-based models, neural network etc are used
for performance prediction each having different prediction accuracy.
Furthermore, the prediction model’s accuracy may differ
depending on performance data collected for different software
types (compute-bound, memory-bound) and different hardware
(simulation-based or physical systems). We have studied fourteen
machine-learning models on simulation-based hardware and
physical systems by executing several benchmark programs with
different computation and data access patterns. Our results show
that the tree-based machine-learning models outperform all other
models with median absolute percentage error (MedAPE) of
less than 5% followed by bagging and boosting models that
help to improve weak learners. We have also observed that
prediction accuracy is higher on simulation-based hardware due
to its deterministic nature as compared to physical systems.
Moreover, in physical systems, prediction accuracy of memorybound
algorithms is higher as compared to compute-bound
algorithms due to manufacturer variability in processors.

# Folders
##  Dataset_CSV: Folder Containing input dataset: Please contact the authors for full dataset. 
### Physical Systems Dataset: 
1. dijkstra_lab.csv
2. matmul_lab_omp.csv
3. montecarlo_lab_omp.csv
4. mser_lab.csv
5. qsort_actual_lab_omp.csv
6. runtimes_final_mantevo_miniFE.csv
7. runtimes_final_npb_ep.csv
8. runtimes_final_npb_mg.csv
9. sha_lab.csv
10. stitch_lab.csv
11. svm_lab.csv
12. tracking_lab.csv


### Simulated Dataset using Gem5": 
1. dijsktra.csv
2. matmul.csv
3. montecarlocalcpi.csv
4. mser.csv
5. qsort.csv
6. sha.csv
7. stitch.csv
8. svm.csv
9. tracking.csv

## Codes: Contain all Experimental Codes
## data: Contains saved models and cross-folds data, which is available as a link to google drive. 
## Images: Contains images used for Paper
## Results_CSV: Contains Metircs Scores for each Dataset application
## Results_Plots_Code: Contains code used for plotting and saving images for paper

