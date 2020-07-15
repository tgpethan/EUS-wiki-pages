baseURL is a property that is a string.
It's the url that your website is hosted at, for instance the baseURL for EUS is "https://ethanus.ml/".

## Uses
The baseURL property is used when constructing the response URL after a file upload

An example constructed url would be:
```
https://ethanus.ml/XXXXXXXXXXXXXX
```

## Unpredictable Results
The reason the server tells you about unpredictable results when leaving out a / in your baseURL is because the code that generates the URL expects a / the be at the end, this snipit being:
```js
res.end(`${eusConfig.baseURL}${fileOutName}`);
```