## Update token information
You can fill [Google form](https://forms.gle/b8dPHFyGqfk5BVjw8) or create a PR on this repository

**How To Update Token Information**
- Follow image requirements
- Proceed to https://github.com/tomochain/tokens
- Press on Fork in the top right corner, wait for process to complete
- Navigate to `tokens` folder on your own fork
- Press on Upload File in the top right corner
- Choose file, make sure it follows requirements above
- Press on Commit changes
- Navigate to `tokens` folder on your own fork
- Press on Create new file in the top right corner
- Follow token information requirements and create the file
- Press on Commit changes
- Press on New pull request on your own fork page and submit it by pressing on Create pull request!
- Press on Create pull request
- Once tests have completed and verified that your image follows all requirements, a maintainer will merge it. In 5-10 minutes your token will have the updated image in TomoChain's products

**Image Requirements**

- file extension: png. Uppercase PNG considered invalid.
- name：contract_address.png in lowercase register. Ex: 0xea8d13af16a33fc5de19c0b1edcf4cd053bd2fa9.png
- size: 256px by 256px
- background: preferably transparent
- use simple drag and drop online service [tinypng](https://tinypng.com/) to optimize image size


**Token Information Requirement**

- file extension: json. Uppercase JSON considered invalid.
- name：contract_address.json in lowercase register. Ex: 0xea8d13af16a33fc5de19c0b1edcf4cd053bd2fa9.json
- required fields: `symbol`, `name`, `site`

**Example**

```json
{
    "symbol": "TOMO",
    "name": "TomoChain",
    "description": "TomoChain's native token",
    "website": "https://tomochain.com",
    "communities": {
        "email": "admin@tomochain.com",
        "telegram": "https://t.me/tomochain",
        "reddit": "https://www.reddit.com/r/Tomochain/",
        "medium": "https://medium.com/tomochain",
        "youtube": "https://www.youtube.com/channel/UCXZ2rmjM84qS80RCj6vQ1gw",
        "twitter": "https://twitter.com/TomoChainANN",
        "facebook": "https://www.facebook.com/tomochainofficial/",
        "github": "https://github.com/tomochain",
        "coinmarketcap": "https://coinmarketcap.com/currencies/tomochain/",
        "coingecko": "https://www.coingecko.com/en/coins/tomochain"
    }
    
}
```

## Token Verification (blue tick)

- Update file `verifiedlist.json`, add the token address and create a pull request

## Token Black List

- Update file `blacklist.json`, add the token address and create a pull request
