# Bitcoin-Cash-MoneyMoney

Fetches balances from bitcoin.com and returns them as securities.

Requires MoneyMoney version **2.3.25** or greater.

## Extension Setup

You can get a signed version of this extension from

* my [GitHub releases page](https://github.com/aaronk6/Bitcoin-Cash-MoneyMoney/releases), or
* the [MoneyMoney Extensions](https://moneymoney-app.com/extensions/) page

Once downloaded, move `Bitcoin Cash.lua` to your MoneyMoney Extensions folder.

## Account Setup in MoneyMoney

* Add a new account of type “Bitcoin Cash”
* Enter one or more Bitcoin Cash addresses (comma-separated, each address needs to start with `bitcoincash:`)

**Note:** If your address doesn’t start with `bitcoincash:`, it is probably in legacy format. If this is the case, you can convert it here: https://cashaddr.bitcoincash.org/

## Known Issues and Limitations

* Always assumes EUR as base currency

## Credits

Powered by [CoinGecko API](https://www.coingecko.com/en/api) and [bitcoin.com](https://bitcoin.com/)

