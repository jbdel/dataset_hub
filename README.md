---
dataset_info:
  features:
  - name: text
    dtype: string
  - name: label
    dtype: string
  splits:
  - name: train
    num_bytes: 127
    num_examples: 4
  download_size: 1181
  dataset_size: 127
configs:
- config_name: default
  data_files:
  - split: train
    path: data/train-*
---
