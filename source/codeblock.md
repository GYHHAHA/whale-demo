---
jupytext:
  text_representation:
    format_name: myst
kernelspec:
  display_name: Python 3
  name: python3
---

# 代码块

```{code-cell} ipython3
import numpy as np
```

```{code-cell} ipython3
np.array([1,2,3,4])
```

```{code-cell} ipython3
:tags: [hide-input]
import pandas as pd
```

```{code-cell} ipython3
pd.Series([1,2,3])
```

```{code-cell} ipython3
pd.DataFrame({"A":[1,2,3]})
```

```{code-cell} ipython3
:tags: [hide-input]
import matplotlib.pyplot as plt
_ = plt.scatter([1,2,3],[-1,-5,2])
```

```{code-cell} ipython3
:tags: [remove-input]
import matplotlib.pyplot as plt
_ = plt.scatter([1,2,3],[-1,-5,2])
```

```python
import matplotlib.pyplot as plt
```

```bash
cd Desktop
mkdir whale-demo
```