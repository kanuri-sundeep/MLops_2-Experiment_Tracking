# MLops_2-Experiment_Tracking

Execute the pipeline using below command

mlflow run https://github.com/kanuri-sundeep/MLops_2-Experiment_Tracking.git --no-conda --version main -P hydra_options="random_forest_pipeline.random_forest.n_estimators=range(50,100,20) -m"

Here we are doing hyperparameter tuning for n_estimators.

We can track outputs of experiments in weights and biases
