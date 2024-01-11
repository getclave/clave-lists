# Clave Lists

## Adding or updating a token in the list

1. Fork the repo
2. Include the token/dapp to the list json by following draft json token structure

```json
    [
        ...,
        {
            "chainId": {CHAIN_ID},
            "name": "{TOKEN_NAME}",
            "symbol": "{TOKEN_SYMBOL}",
            "decimals": {TOKEN_DECIMALS},
            "address": "{TOKEN_ADDRESS}",
            "icon": "https://raw.githubusercontent.com/getclave/clave-tokenlists/master/logos/{TOKEN_ADDRESS}.png",
            "isDefault": false
        }
    ]
```

```json
    [
        ...,
        {
        "name": "{DAPP_NAME}",
        "url": "{HOMEPAGE_URL}",
        "description": "{DESCRIPTION}}",
        "chain_ids": [{CHAIN_ID}],
        "tags": ["{TAG}"],
        "image": "https://raw.githubusercontent.com/getclave/clave-lists/master/dapp-list/logos/{DAPP_NAME}.png"
        }
    ]
```

3. Upload your token/dapp icon to the repo in the logos folder by following the naming convention

```
    ./token-list/logos/{TOKEN_ADDRESS}.png

    ./dapp-list/logos/{DAPP_NAME}.png
```
