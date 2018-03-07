# cash


**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [Features](#features)
- [Usage](#usage)
  - [Usage Examples](#usage-examples)
- [Commands](#commands)
  - [Command Examples](#command-examples)
- [Supported Currencies](#supported-currencies)


## Features

- Converts an amount of a currency to one or several other ones

  
## Usage

$ cash *amount* *currency*
$ cash *command*

### Usage Examples

- `node index 20 usd` // returns
	<div style="text-align: center;"> <img src="../img/screen1.png"></div>
- `node index.js 1 usd eur` // returns 
	<div style="text-align: center;"> <img src="../img/screen2.png"></div>

## Commands

`--save`,  `-s`       Save currencies as default currencies. Basic default currencies are EUR, GBP and PLN
`--help`,  `-h`       Display help message
`--version`,  `-v`     Display version number

### Command Examples

 `node index --save usd eur pln aud` // returns

 	Saved default currencies to ..\AppData\Local\cash-nodejs\Config\config.json


 	`node index --help` // returns
<div style="text-align: center;"> <img src="../img/screen3.png"></div>


## Supported Currencies

  "AUD": "Australian Dollar",
  "RUB": "Russian Rouble",
  "EUR": "Euro",
  "BGN": "Bulgarian Lev",
  "BRL": "Real Brazilian",
  "CAD": "Canadian Dollar",
  "CHF": "Swiss Franc",
  "CNY": "Chinese Yuan",
  "CZK": "Czech Koruna",
  "DKK": "Danish Krone",
  "GBP": "Pound Sterling",
  "HKD": "Hong Kong Dollar",
  "HRK": "Croatian Kuna",
  "HUF": "Hungarian Forint",
  "IDR": "Indonesian Rupiah",
  "ILS": "Israeli Shekel",
  "INR": "Indian Rupee",
  "JPY": "Japanes Yen",
  "KRW": "South Korean Won",
  "MXN": "Mexican Peso",
  "MYR": "Malaysian Ringgit",
  "NOK": "Norwegian Krone",
  "PHP": "Philippine Peso",
  "PLN": "Polish Zloty",
  "RON": "Romanian New Leu",
  "SEK": "Swedish Krona",
  "SGD": "Singapore Dollar",
  "THB": "Thai Baht",
  "TRY": "Turkish Lira",
  "USD": "US Dollar",
  "ZAR": "South African Rand",
  "NZD": "New Zealand Dollar"