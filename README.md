# API Project: URL Shortener Microservice for freeCodeCamp

## User Stories

1. I can POST a URL to `https://sl477-boilerplate-project-urlshortener.glitch.me/api/shorturl/new` and I will receive a shortened URL in the JSON response. Example : `{"original_url":"www.google.com","short_url":1}`
2. If I pass an invalid URL that doesn't follow the valid `http(s)://www.example.com(/more/routes)` format, the JSON response will contain an error like `{"error":"invalid URL"}`. _HINT_: to be sure that the submitted url points to a valid site you can use the function `dns.lookup(host, cb)` from the `dns` core module.
3. When I visit the shortened URL, it will redirect me to my original link.

### Creation Example

POST https://sl477-boilerplate-project-urlshortener.glitch.me/api/shorturl/new - body (urlencoded) : url=https://www.google.com

### Usage

https://sl477-boilerplate-project-urlshortener.glitch.me/api/shorturl/3

#### Will redirect to

https://www.freecodecamp.org/forum/
