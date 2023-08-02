

![Star Badge](https://img.shields.io/static/v1?label=%F0%9F%8C%9F&message=If%20Useful&style=style=flat&color=BC4E99)
![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)
[![View Repositories](https://img.shields.io/badge/View-My_Repositories-blue?logo=GitHub)](https://github.com/yaswanthteja?tab=repositories)
[![View My Profile](https://img.shields.io/badge/View-My_Profile-green?logo=GitHub)](https://github.com/yaswanthteja)



# Currency Xchange


Currency Xchange is a user-friendly and efficient currency converter application that allows users to convert between different currencies effortlessly. With real-time exchange rate data sourced from reputable APIs, Currency Xchange provides accurate and up-to-date conversion rates for  currencies worldwide—experience hassle-free currency conversions on the go with Currency Xchange.


<p align="center">
  <img src="https://forthebadge.com/images/badges/built-with-love.svg">
  <img src="https://forthebadge.com/images/badges/made-with-python.svg">
</p>



The app is built for performing currency conversion using data fetched from an 

- open-source API: https://www.frankfurter.app/
- Git hub:- https://github.com/hakanensari/frankfurter
- Api Documentation: https://www.frankfurter.app/docs/#usage


## 🛠️ Installation Steps


- Install python

```
pip install requests
```


## ⚙️ Usage

In the project directory, you can run: 


```bash
python main.py  EUR  INR
```

Here we need to mention the currency codes


```bash

    "AUD": "Australian Dollar",
    "BGN": "Bulgarian Lev",
    "BRL": "Brazilian Real",
    "CAD": "Canadian Dollar",
    "CHF": "Swiss Franc",
    "CNY": "Chinese Renminbi Yuan",
    "CZK": "Czech Koruna",
    "DKK": "Danish Krone",
    "EUR": "Euro",
    "GBP": "British Pound",
    "HKD": "Hong Kong Dollar",
    "HUF": "Hungarian Forint",
    "IDR": "Indonesian Rupiah",
    "ILS": "Israeli New Sheqel",
    "INR": "Indian Rupee",
    "ISK": "Icelandic Króna",
    "JPY": "Japanese Yen",
    "KRW": "South Korean Won",
    "MXN": "Mexican Peso",
    "MYR": "Malaysian Ringgit",
    "NOK": "Norwegian Krone",
    "NZD": "New Zealand Dollar",
    "PHP": "Philippine Peso",
    "PLN": "Polish Złoty",
    "RON": "Romanian Leu",
    "SEK": "Swedish Krona",
    "SGD": "Singapore Dollar",
    "THB": "Thai Baht",
    "TRY": "Turkish Lira",
    "USD": "United States Dollar",
    "ZAR": "South African Rand"

```



## 🏗️ Project Structure
```
├── api.py             <- script contains the code for calling API endpoints 
├── currency.py        <- contains the code for checking if currency code is valid,  store results and formatting final output
├── main.py            <- main program used for entering the input parameters  (currency codes) and display the results
├── test_api.py        <- python script for testing code from api.py
└── test_currency.py   <- Python script for testing code from currency.py
```




## ✨ Contribution

Contributions, issues, and feature requests are welcome!

To contribute to this project, see the GitHub documentation on **[creating a pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request)**.


## 👏 Support

Give a ⭐️ if you like this project!




___________________________________

