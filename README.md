# URL Shortener Microservice :black_heart:

This service accepts a URL as a parameter and will check whether it follows the valid https://<i></i>www<i></i>.<i></i>google.com format. If the URL is valid, it will return both the original URL and shortened URL in the JSON response. If it is not valid, the JSON response will contain an error instead. When you visit that shortened URL, it will redirect you to the original link.


A Full Stack Javascript application built using [MongoDB](https://www.mongodb.org/), [Node.js](https://nodejs.org/) and [Express](https://expressjs.com/). An API Project for FreeCodeCamp.

## Example Creation Usage

Pass the URL to path https://<i></i>https://localhost:3000/new/[URL] as below:

### Valid URL example
```
https://localhost:3000/new/https://www.github.com
```
### Invalid URL example (missing protocol)
```
https://localhost:3000/new/www.github.com
```


Cheers!!! :black_heart:
