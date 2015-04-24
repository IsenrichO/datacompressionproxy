This is an experimental extension for Google Chrome bringing <a href='https://developers.google.com/chrome/mobile/docs/data-compression'>Chrome Data Compression Proxy</a> from mobile to desktop PCs.

**NEW!** Version 2.0 adds statistics, custom bypass and adblock lists.

[![](https://developer.chrome.com/webstore/images/ChromeWebStore_BadgeWBorder_v2_496x150.png)](https://chrome.google.com/webstore/detail/data-compression-proxy/ajfiodhbiellfpcjjedhmmmpeeaebmep)

### How it works ###

The extension sends all HTTP (but not HTTPS) traffic through Chrome Data Compression Proxy server, which uses SPDY protocol to speed up web browsing. Enabled state is indicated by a green icon. You can manually disable the proxy by clicking on it. When the proxy raises an error, it is being automatically disabled for adjustable number of seconds, so that the request can be resent.

The extension uses either `chrome.webRequest` (slower) in Chrome Stable or `chrome.declarativeWebRequest` (faster but wthout the stats) in Chrome Beta/Dev, so ignore any warnings.

### Statistics ###

You can find the savings statistics in Options, based on the content-length header.

### Disclaimer ###

The extension is provided as is with no warranty. Use it at your own risk. It is not affiliated with Google.