# Clave Lists

## Adding or updating a token in the list

1. Fork the repo
2. Add the token to the list json by following draft json token structure

```json
    [
        ...,
        {
            "chainId": {CHAIN_ID},
            "name": "{NAME}",
            "symbol": "{SYMBOL}",
            "decimals": {DECIMALS},
            "address": "{ADDRESS}", // lowerCase
            "icon": "https://raw.githubusercontent.com/getclave/clave-tokenlists/master/logos/{TOKENADDRESS}.png" // lowerCase
        }
    ]
```

3. Upload your token icon to the repo in the logos folder by following the naming convention

```
    ./logos/{CHAINID}_{TOKENADDRESS}.png
```
