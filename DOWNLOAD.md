Dataset **Tunisian Licensed Plates** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/K/p/J0/51hAyaVzf4LTulLEdThs2TapdygIgBHtux4qEXr5EYpAcxXEtTuwJJaCeNom9foAIZisuRNX6s2b1ZTTYw3kF6RSOiRBL0Sx0wKu6N6ySNdKYpFxNkJ1LmYCIQzv.tar)

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