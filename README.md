# VQA Model 

## Requirements

1. keras with theano backend.
2. progressbar2
3. spacy -> Load en_core_web_lg language model.

## Steps to run model.

1. Download VQA training/validation questions and annotations. ( refer data/download.txt )
2. Run dumpText.py to obtain Training and validations QAs.
3. Download MSCOCO image features into features/coco/ ( refer README.md in features/ ).
4. Run mlp.py
