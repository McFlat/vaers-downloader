# VAERS Downloader

```py
import os
import sys
sys.path.insert(0, './src')
from VAERSFileDownloader import updateVAERSFiles

updateVAERSFiles(
        needsUpdate = True,
        years = [2019, 2020, 2021, 2022],
        workingDirectory = os.getcwd())
```

Thanks to Frank Knoll for the original code... https://github.com/KnollFrank/HowBadIsMyBatch

