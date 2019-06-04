# cwi
Sequence labelling models for complex word identification

This github contains the complex word identification models from Gooding and Kochmar (2019).

The sequence model used is available here: https://github.com/marekrei/sequence-labeler, please also cite this paper if using the CWI models in your research. 

In order to run the CWI models you will need to download the sequence labeller repository, you can then use the additional functions available in complex_word.py with the trained model. 


```python
from complex_word import Complexity_labeller 

model_path = './gpu_attention.model'
temp_path = './temp_file.txt'

labeller = Complexity_labeller(model_path, temp_path)
```

todo:
include bibtex?
also show example
