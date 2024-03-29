Dataset **DAC-SDC 2022** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/B/Q/a4/2ULAjDGFje3eU5YcubxYOhToQxZGRrJdAh9u8G7KmajpWiW2I1QYmKuapV7VjMJYgcPgFqjF5sXaj3VZNTdFsieaxBEU5SddBLFNsCWAiPhHIfxpn1TlEr1ifcKm.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='DAC-SDC 2022', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://byu.box.com/s/hdgztcu12j7fij397jmd68h4og6ln1jw).