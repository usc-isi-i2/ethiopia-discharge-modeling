# ethiopia-discharge-modeling

T2WML modeling for Ethiopia discharge dataset

Assumes a regular format for all files (Specifically no typos in names and 
month header rows are 6 rows after year row) 

Output files in `data/results`

## Setup

### Install KGTK (Uses dev branch for Kypher features)
```
git clone git@github.com:usc-isi-i2/kgtk.git
cd ktgk
git checkout dev
python setup.py install
cd ..
```

### Install T2WML API

`
pip install --extra-index-url https://pypi.fury.io/theresearchsoftwarecompany/ t2wml-api
`

### Install T2WML GUI (Optional)

Download latest release at https://github.com/usc-isi-i2/t2wml/releases (At least v2.3.8)

## Usage 

### Notebook to generate all tables

`Generate Results.ipynb`

### Example Notebook on single file 

`KGTK Workflow.ipynb`

### GUI Editing

Created a pre-made project in `t2wml_project/project.t2wml`
Language guide: https://github.com/usc-isi-i2/t2wml-api/blob/master/docs/grammar.md

