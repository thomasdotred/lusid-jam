Use within a LUSID hosted Jupyter notebook as follows: 

```
import os
from lusid.utilities import ApiClientFactory
from lusidjam import RefreshingToken

api_factory = ApiClientFactory(token=RefreshingToken(), api_url=os.getenv("FBN_LUSID_API_URL", None), app_name="Jupyter")
```
