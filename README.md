# Long-term-light-curves

import numpy as np
from matplotlib import pyplot as plt
import pandas as pd
from astroML import time_series as ts
from astroML.time_series import lomb_scargle, lomb_scargle_BIC, lomb_scargle_bootstrap
from astropy.io import fits
from astropy.table import Table

