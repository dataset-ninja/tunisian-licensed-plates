Dataset **Tunisian Licensed Plates** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogImZzOi8vYXNzZXRzLzI4NTFfVHVuaXNpYW4gTGljZW5zZWQgUGxhdGVzL3R1bmlzaWFuLWxpY2Vuc2VkLXBsYXRlcy1EYXRhc2V0TmluamEudGFyIiwgInNpZyI6ICIwTklyMExFVzBQNkhvSnd1aUhrRmtoU1MrbFNRRFRuL0tjZC9ySGsxK1pZPSJ9)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Tunisian Licensed Plates', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://www.kaggle.com/datasets/achrafkhazri/labeled-licence-plates-dataset/download?datasetVersionNumber=1).