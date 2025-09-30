# REDD - NILMTK Dataset

The Non-Intrusive Load Monitoring Toolkit (NILMTK) supports 16 dataset, including REDD dataset, a small yet very popular open NILM dataset.

However, the original source http://redd.csail.mit.edu/ has been unavailable for a long time.

## Quick Start

Clone the dataset:

```
$ git clone https://github.com/wuhanstudio/redd-lowfreq/
```

Convert the raw dataset to H5 format, which is supported by NILMTK:

```python
from nilmtk.dataset_converters import convert_redd

convert_redd('./redd-lowfreq', './redd-lowfreq.h5')
```

The converted H5 file is also available on the [release page](https://github.com/wuhanstudio/redd-lowfreq/releases).
