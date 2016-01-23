# FCC Full Stack Web Development Challenges

## Overview

This project is a response to [Free Code Camp](http://freecodecamp.com/) full stack and back-end web development challenges.

## Request Header Parser

This sample API service is inteded to show the ability to read and interprete HTTP request headers.

To use this service:
- Point your browser or send a GET request to the following path on our domain: ```/api/whoami```.
- The API responds with a JSON string showing the parsed request header.

Here is an example of the API response:

```
{
ip_address: "100.20.21.70",
language: [
"en-US"
],
browser: "Chrome",
browser_version: "49.0.2623.13",
os: "OS X El Capitan",
platform: "Apple Mac",
header_source: {
host: "timestamp-micro-stellarnode.c9users.io",
accept: "text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,*/*;q=0.8",
upgrade-insecure-requests: "1",
user-agent: "Mozilla/5.0 (Macintosh; Intel Mac OS X 10_11_2) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/49.0.2623.13 Safari/537.36",
accept-encoding: "gzip, deflate, sdch",
accept-language: "en-US,en;q=0.8,ru;q=0.6",
cookie: "connect.sid=s%3A-39HhjHKjhKkGYjKDkJkjHhkDHkjJ.xiusDiudKJHoaDDsd",
if-none-match: "W/"31e-nkjkjhsdfHHKDnsk"",
x-forwarded-proto: "https",
x-forwarded-port: "443",
x-region: "eu",
x-forwarded-for: "100.20.21.70",
connection: "keep-alive"
}
}

```

## License

MIT License. [Click here for more information.](LICENSE.md)
