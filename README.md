# YouTube Title Generator

## Install Dependencies

## How It Works

```python
!pip install evaluate
```

## Dataset

```python
#https://github.com/chris-lovejoy/youtube-titles-and-transcripts
```

## Import Libraries

```python
import pandas as pd
import torch
from transformers import BertTokenizer, BertModel
import torch.nn.functional as F
from datasets import Dataset
import random
import evaluate
from torch.utils.data import DataLoader, Dataset as TorchDataset
import matplotlib.pyplot as plt
import csv
```