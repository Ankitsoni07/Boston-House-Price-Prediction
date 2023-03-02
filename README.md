### Boston House Price Prediction

### Software and Tools Requirements

1. [Github Account](https://github.com)
2. [HerokoAccount](https://heroku.com)
3. [VS Code IDE](https://code.visualstudio.com/)
4. [GitCLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)

Create a new environment

```
python -m pip install --user --upgrade pip
py -m pip install --user virtualenv
py -m venv venv
.\venv\Scripts\Activate
```

Sample JSON

```
{
  "data":{
    "CRIM":0.00632,
    "ZN": 18.0,
    "INDUS": 2.31,
    "CHAS": 0.0,
    "NOX": 0.538,
    "RM": 6.575,
    "AGE": 65.2,
    "DIS": 4.0900,
    "RAD": 1.0,
    "TAX": 296,
    "PTRATIO": 15.3,
    "B": 396.90,
    "LSTAT": 4.98
}
}
```