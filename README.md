# httpResponseCodes
Collection of HTTP response codes, dummy data and examples

Examples 1: [https://httpstat.us/
](httpstat.us/)

General information:

This is a super simple service for generating different HTTP codes. It's useful for testing how your own scripts deal with varying responses. Just add the status code you want to the URL, like this: httpstat.us/**200** or 500, maybe 429...

We'll return a response like this:


```http
HTTP/1.1 200 OK
Content-Type: text/plain or application/json
Content-Length: 123
```
    
You can also add the url sleep parameter (`https://httpstat.us/200?sleep=5000`) and add a mock wait, perhaps to force a callback, asynchronous function, or timeout. It is useful to know this.
