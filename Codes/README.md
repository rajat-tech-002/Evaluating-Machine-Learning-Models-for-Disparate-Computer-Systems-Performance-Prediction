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
