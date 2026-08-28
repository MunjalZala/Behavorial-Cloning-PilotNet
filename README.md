# Behavioral Cloning — PilotNet

**Author:** Munjalsinh Zala
**Course:** SoSe24-ML — Exam 3, Own Machine Learning Project

Predicts steering angle from a single front-facing camera frame in the Udacity Self-Driving Car
Simulator, following NVIDIA's PilotNet architecture (Bojarski et al., 2016).

## Contents

- `behavioral_cloning.ipynb` — loads the data, trains PilotNet, evaluates it with a full metrics
  suite (RMSE/MAE/R², direction accuracy, confusion matrix), and drives the simulator live with it.
- `report/behavioral_cloning_report.pdf` — the full project report: problem relevance, data
  choice, model setup, baseline comparison, evaluation, interpretation, and conclusion, plus
  answers to the exam's two theoretical questions.

## Running

Open `behavioral_cloning.ipynb` in Jupyter or VS Code and run all cells top to bottom. It
downloads the dataset and the Udacity simulator automatically on first run. The final "Run the
trained model live" cell starts a local server that the simulator connects to once you click
Autonomous Mode.

## Reference

Bojarski, M., Del Testa, D., Dworakowski, D., Firner, B., Flepp, B., Goyal, P., Jackel, L. D.,
Monfort, M., Muller, U., Zhang, J., Zhang, X., Zhao, J., & Zieba, K. (2016). *End to End Learning
for Self-Driving Cars.* NVIDIA Corporation. arXiv:1604.07316.
