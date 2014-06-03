 | Fakturor | Mätvärden | Summa
--- | -------- | --------- | -----
test | 271 | 1565 | aa
production | 272 | 1565 | bb


```sh
$ curl --silent -XPOST https://foobar.com/ -d "url=https://en.wikipedia.org/wiki/Henry_Morton_Stanley" | jq .
{
  "status": 200,
  "title": "Henry Morton Stanley - Wikipedia, the free encyclopedia",
  "url": "https://en.wikipedia.org/wiki/Henry_Morton_Stanley"
}
```
