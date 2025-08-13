---
dataset_info:
  features:
  - name: text
    dtype: string
  - name: label
    dtype:
      class_label:
        names:
          '0': negative
          '1': positive
  splits:
  - name: train
    num_bytes: 165
    num_examples: 5
  - name: validation
    num_bytes: 62
    num_examples: 2
  - name: test
    num_bytes: 93
    num_examples: 3
  download_size: 3905
  dataset_size: 320
configs:
- config_name: default
  data_files:
  - split: train
    path: data/train-*
  - split: validation
    path: data/validation-*
  - split: test
    path: data/test-*
---
