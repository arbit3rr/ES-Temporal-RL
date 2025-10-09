# Temporal RL for Energy System Control

The temporal RL agent introduces temporal awareness to RL by integrating forecasts (e.g., load, PV, and wind generation) into decision-making through an attention-based temporal embedding module.
![Temporal RL](https://github.com/user-attachments/assets/d658c1dc-16f2-4958-9237-c7268a6a1f8a)

## Citation
```python
@inproceedings{heydarian2025embedding,
  title={Embedding Temporal Awareness in Reinforcement Learning Models for Energy System Control},
  author={Heydarian Ardakani, Amirhossein and Hurink, Johann and Gibson, Ian and Shirazi, Elham},
  booktitle={Proceedings of the 16th ACM International Conference on Future and Sustainable Energy Systems},
  pages={1002--1004},
  year={2025}
}
```

## Results
![Temporal Embedding](https://github.com/user-attachments/assets/7c0565f3-f8cb-415f-ad64-10bfae5201a6)

## Inference
Run the following notebook:
```
$ 6. attention_TRL.ipynb
```

## Data Sources
| Data | Source |
| --- | --- |
| `PV & Wind Generation` | [ENTSO-E Transparency Platform](https://transparency.entsoe.eu/dashboard/show) |
| `Load` | [ENTSO-E Transparency Platform](https://transparency.entsoe.eu/dashboard/show) |
| `Electricity Price` | [ENTSO-E Transparency Platform](https://transparency.entsoe.eu/dashboard/show) |
| `CO2 Emission` | [Nationaal Energie Dashboard](https://ned.nl) |
