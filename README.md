# uncors

PHP proxy that injects wildcard CORS headers into the HTTP response.

> [!CAUTION]
> This script is unthrottled and makes no security checks, do not run it on a public server!

### Example

Install `index.php` at path /uncors in your web server, then use proxy URL:

    https://your.hostname/uncors/?url=URL

to retrieve URL with CORS-enabled headers.

### Credits

Based on [proxy.php](https://p.cweiske.de/656) by Christian Weiske.
