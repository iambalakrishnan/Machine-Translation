# Machine-Translation
A Language translation project


# Steps to Run this Projects

## Create Environment

``` bash

conda create --prefix ./env python=3.7 -y
```

## Activate environment

```bash
conda activate ./env
```

## Install requirements

```bash
pip install -r requirements.txt
```

## Execute main.py
Open a postman

Url in POSTMAN
    http://localhost:8000/predict

Select the method as POST

Select the Body section

Inside the Body Section Select Raw and Select format as a JSON

Data which we can send from the postman
    {
    "text" : "I am going to Sillicon Valley today!"
}
