# Welcome to starling-cli 👋
[![Version](https://img.shields.io/npm/v/starling-cli.svg)](https://www.npmjs.com/package/starling-cli)
[![Documentation](https://img.shields.io/badge/documentation-yes-brightgreen.svg)](https://github.com/Jiro-Digital/starling-cli#readme)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/Jiro-Digital/starling-cli/graphs/commit-activity)
[![License: MIT](https://img.shields.io/github/license/JiroUK/starling-cli)](https://github.com/Jiro-Digital/starling-cli/blob/master/LICENSE)

> A CLI tool for querying your Starling Bank account

## Install
Install globally as an NPM module.
```sh
npm install starling-cli -g
```
Run the following command to initialise the connection to Starling. Follow the prompts to generate and set your Personal Access Token from the [Starling Developer portal](https://developer.starlingbank.com).
```sh
starling init
# OR
starling i
```

## Usage
The following commands (and their aliases) can be used.
```sh
starling balance # Fetch your Starling account balance
#OR
starling b

starling transactions # Fetch your Starling account transactions
#OR
starling tx

starling mandates # Fetch the Direct Debit mandates on your Starling account
# OR
starling dd
```

## Author

🏢 **Jiro**

* Website: https://jiro.digital
* Github: [@Jiro-Digital](https://github.com/Jiro-Digital)

## Show your support

Give a ⭐️ if this project helped you!


## 📝 License

Copyright © 2020 [Jiro Digital Ltd](https://github.com/Jiro-Digital).

This project is [MIT](https://github.com/Jiro-Digital/starling-cli/blob/master/LICENSE) licensed.
