# Machine Learning & Deep Learning: YouTube Channel Code

Source code for the tutorials on my YouTube channel **[Epsilon Delta Italia](https://www.youtube.com/@EpsilonDeltaItalia)**.

Each video explains an AI algorithm from three angles: **the math, the intuition and the code**. Every folder contains the Jupyter notebook used in the video, with derivations, implementations and benchmarks. Videos and notebooks are in Italian.

## Videos and code

| # | Topic | Code | Video |
|---|-------|------|-------|
| 01 | **Optimization**: gradient descent and momentum, in NumPy and PyTorch | [`01_gradient_descent_momentum`](./01_gradient_descent_momentum) | [Channel](https://www.youtube.com/@EpsilonDeltaItalia) |
| 02 | **Tree-based models**: decision trees, random forests and XGBoost, from the math (including XGBoost's second-order Taylor expansion) to Python | [`02_decision_trees_rf_xgboost`](./02_decision_trees_rf_xgboost) | [Watch](https://youtu.be/VpwJVJUcGas) |

More videos are on the way. The time series series has its own repository: [Time-Series](https://github.com/lucasimo2609-stack/Time-Series).

## How to use this repository

### Run locally

```bash
git clone https://github.com/lucasimo2609-stack/youtube-code.git
cd youtube-code

python -m venv venv
source venv/bin/activate        # Windows: venv\Scripts\activate

pip install -r requirements.txt
jupyter notebook
```

Then open the notebook in the folder of the video you are following. The dataset for video 02 (`drug200.csv`) is already in its folder.

### Run on Google Colab

Open any notebook on GitHub and replace `github.com` with `githubtocolab.com` in the URL. For video 02, upload `drug200.csv` to the Colab session before running.

## License

[MIT](LICENSE)
