rockytrade
==========

RockyTrade exchange tools and docs.

 RockyTrade public API
 
 - Markets data
 
    url : https://rockytrade.net/api-v0.php?method=markets
  return: status
  - "success" on success
  - "error" om error

Sample output:
```
{
  "status": "success",
  "results": [
    {
      "market_id": "112",
      "alt_name": "66Coin",
      "alt_symbol": "66",
      "lasttradeprice": "1.01000000",
      "hi_24": "1.01000000",
      "lo_24": "0.92000000",
      "bid": "0.92000000",
      "ask": "1.01000000",
      "avg_24": "0.99571429",
      "alt_vol": "0.00854856",
      "base_vol": "0.00855015"
    },
    {
      "market_id": "101",
      "alt_name": "Beercoin",
      "alt_symbol": "BEER",
      "lasttradeprice": "0.00000002",
      "hi_24": "0.00000002",
      "lo_24": "0.00000002",
      "bid": "0.00000002",
      "ask": "0.00000004",
      "avg_24": "0.00000002",
      "alt_vol": "7601.00000000",
      "base_vol": "0.00015202"
    },
    ....
  ]
}

```
