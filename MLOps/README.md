```bash
kaggle datasets download -d netflix-inc/netflix-prize-data
unzip -f -q "netflix-prize-data.zip" -d netflix-prize-data
```
https://www.kaggle.com/datasets/netflix-inc/netflix-prize-data

```python
import numpy as np
import opendatasets as od

dataset = "https://www.kaggle.com/datasets/netflix-inc/netflix-prize-data"
od.download(dataset)
```
Type the key
