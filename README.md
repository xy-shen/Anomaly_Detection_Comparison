# Anomaly_Detection_Comparison

A comparison of three anomaly detection methods: [SPE]([https://arxiv.org/pdf/1909.03500v3.pdf](https://github.com/ZhiningLiu1998/self-paced-ensemble)), [a contrastive learning method](https://openreview.net/forum?id=_hszZbt46bT), and [Devnet](https://github.com/GuansongPang/deviation-network).

This respository includes the implementation of the first two methods. Due to the conflicts of the dependencies, the code of Devnet is in [this respository](https://github.com/odilecooper/deviation-network#devnet-an-end-to-end-anomaly-score-learning-network).

## Usage

To train and test the models on the same data that Devnet use, which is the normalised version of Fraud dataset:
```python
python main.py --use_normalised
```

To run on the original Fraud dataset:
```python
python main.py
```

## Results

