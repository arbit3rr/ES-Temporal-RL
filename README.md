# Temporal RL for Energy System Control

The temporal RL agent introduces temporal awareness to RL by integrating forecasts (e.g., load, PV, and wind generation) into decision-making through an attention-based temporal embedding module.
![Temporal RL](https://github.com/user-attachments/assets/d658c1dc-16f2-4958-9237-c7268a6a1f8a)

## Citation
```python
@inproceedings{ardakani2024TRL,
  title={Attention-Based Temporal Reinforcement Learning for Energy System Control},
  author={Ardakani, Amirhossein Heydarian and Hurink, Johann and Gibson, Ian and Shirazi, Elham},
  booktitle={2025 IEEE PES Innovative Smart Grid Technologies Europe (ISGT EUROPE)},
  pages={1--5},
  year={2025},
  organization={IEEE}
}
```

## Results
![Temporal Embedding](https://github.com/user-attachments/assets/3feb3b5c-a6b7-431a-9eeb-4cc71ade899f)

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
