
Train model on Module FFF (due to the largest dataset + variance of results)
Tested model for other modules but didnt do so hot, and even after fine tuning (possible overfitting)
I train model based on all other modules (but do it so that dataset for modules with lesser amt has higher weight, so to treat it as if all modules have equal amt of data) [dont ask me why i didn't do this  from the start]
then finetune based on optuna's results.

Next I plan to :
1) Clustering/profiling (This is to cluster students with similar studying pattern to see if there's any category we can place them in) [this is with unsupervised]