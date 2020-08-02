# project
import networkx as nx
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import random
import math
import json

with open(r'/Users/claudia/Desktop/dpc-covid19-ita-province.json') as f:
  data = json.load(f)

print(data)
