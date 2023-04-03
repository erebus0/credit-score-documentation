# credit-score-documentation

Request - 
```cURL
curl --location 'localhost:3000/score' \
--header 'x-api-key: (API Key)' \
--header 'x-public-address: (Public Address)'

```

Response - 
```JSON
 {
    "score": "score",
    "address": "publicAddress"
 }


```