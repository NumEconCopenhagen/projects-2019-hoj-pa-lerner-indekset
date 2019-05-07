# Modelproject: A Solow model with fossil fuels and a climate externality

The motivation for this project is to analyze long-term growth in th presence of finite resources and a negative externality from previously utilized ressource.

We use the following packages:
import numpy as np
from scipy import linalg
from scipy import optimize as opt
from scipy.ndimage.interpolation import shift
import sympy as sm
import pandas as pd
import matplotlib.pyplot as plt
sm.init_printing(pretty_print = True)
from ipywidgets import interact, interactive, fixed, interact_manual
import ipywidgets as widgets
import matplotlib.animation as animation
from matplotlib.widgets import Slider
