# ScatterProxies
A repository of proxies for use within Scatter

## Adding new proxies

- Create a pull request adding your explorer to the correct blockchain in the "explorers.json" file. 
- **Fill out all of the fields, they are all required.**

```
{
  "name":"",            // The name of your proxy, this should be Title Case
  "description":"",     // A short ( 250 chars ) description of your proxy
  "values":[""],        // An array of up to 5 of your values/beliefs
  "account":""         // The account to be proxied to
```

## Example Entry

```
{
  "name":"Scatter Proxy",
  "description":"Cat on cat humor.",
  "values":["Fruit", "Basket"],
  "account":"scatterproxy"
}
```
